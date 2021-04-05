# Ifoss law book

This repository contains the sources in various formats of the second edition of the IFOSS Law Book.

Any pull request will be authorized only by the copyright holders of the individual contributions.

> **NOTE**: **_if you see this note you are working on the master branch_** please always work on the bugfix branch and make a pull request from there, so that the original version is untouched until we merge all the changes. On your local filesystem, you can do

>        git -b bugfix
>        git branch --set-upstream-to=origin/bugfix bugfix

> and work from there

## Some useful commands to generate Markdown:

**Requires ASCIIDOC**

To generate an intermediary docbook document for all .txt (asciidoc) documents in the directory.

    asciidoc -b docbook *.txt

**Requires Pandoc** (any version).


Assuming you have all the docbook documents in the same place (directory)

    find *.xml -exec pandoc -Ss -f docbook -t markdown_strict+footnotes {} -o {}.xml \;

That creates a number of Markdown documents for all docbook documents in the directory

To generate a single HTML file from the Markdown documents, you need to change the internal footnotes references (as you cannot have two identical footnote reference in the same file) I use this simple substitution script, to be add to a subdirectory, which adds a random number to the footnote references across all files and writes them in the subdirectory:

    #/bin/bash!

    for f in ../*.xml.md

    do

     sed "s/\(\[\^\)\([0-9]\|[0-9][0-9]\|[0-9][0-9][0-9]\)\(\]\)/\1_$RANDOM\_\2\3/g" $f > $(basename $f)

     echo "done with $(basename $f)"

    done

**NOTE**: check that the script went well and copy the resulting documents to the main directory.


Some documents have internal references. There is only a handful of them. You can count how many with:

    grep -c "<<sec" *.txt

So instead of scripting it, you will be content with changing them by hand. You only need to seek for something like

    [section\_title](#sec_finland_moral_rights)

and to do two things:

a) Change the referenced text (the text between square brackets) so to have it look like:  
  `  [Moral Rights](#sec_finland_moral_rights) and`
b) Ad the exact part between round brackets next to the relevant section title (where the reference points to) so it looks like:  
`#### Moral Rights {#sec_finland_moral_rights}`


Now you are ready to produce a full HTML or PDF with

    pandoc -Ss -f markdown_strict+footnotes+auto_identifiers+implicit_header_references+header_attributes -o file.html file.pdf *.xml.md

Thank you

Carlo Piana

---

Notes during migration to MarkDown and Pandoc (by Matija Šuklje):

This are the working parts:

- `src/` contains the current sources in MarkDown
- `sorting.meta` seems to be a list of in which order the files should be generated – or at least, that is how I am using it :)
- `IFOSSLB.pdf` is the PDF of the whole book
- `PDF_per_chapter/` contains a PDF for each chapter
- `README.markdown` is this file

These seem to be obsolete, but I am keeping them here just in case for now:

- `archive_XML` contains old sources in XML
- `archive_TXT` contains old sources in plain text
- `main.markdown` _seems_ to be a concatenation of all the files in `src/*.markdown`, but I am unsure
- `main.pdf` is the PDF generated from it – may be useful to compare with the `IFOSSLB.pdf`
- `main-docinfo.markdown` _seems_ to be some metainfo or cover of some sorts, but I am unsure

Generating a full-book PDF works by running:

```
cat sorting.meta | xargs pandoc --pdf-engine=xelatex -s -f markdown_strict+footnotes+auto_identifiers+implicit_header_references+header_attributes+smart -o IFOSSLB.pdf
```

Generating all the PDF per chapter works by running in Fish shell (need someone to port it to basic POSIX shell):

```fish
for file in (cat sorting.meta);
	pandoc --pdf-engine=xelatex -s -f markdown_strict+footnotes+auto_identifiers+implicit_header_references+header_attributes+smart -o PDF_per_chapter/(basename $file .markdown).pdf $file;
end
```


## Naming convention

The individual files are named according to the following convention:

```
10-Intro.markdown
20-History.markdown
50-Belgium.markdown
50-China.markdown
50-...

```

The position of the chapters Intro, History and is predetermined and the country chapters can simply be added as `50-$country_name.markdown` and they will be generated in the right order without the need to manually keep track of the order in a separate file. This also leaves space to introduce new groups of chapters before or after, as well.

The file `sorting.meta` is therefore no longer needed.

## Author biographies in separate files

The author biographies are divided into separate files. They can be found in the `src/authors/` directory.

## Generating the PDF

### Generating the PDF with pandoc (old method)

Generating a full-book PDF now works by running (requires pandoc 2.0 or later):

```
pandoc --number-sections --pdf-engine=xelatex -s -f markdown_strict+footnotes+auto_identifiers+implicit_header_references+header_attributes+smart src/*markdown -o IFOSSLB.pdf
```

### Generating the PDF with include-pandoc

The author biographies are in separate files and are linked at the beginning of each chapter with the use of [include-pandoc](https://github.com/alpianon/include-pandoc).

```
'!include authors/$author_name.markdown
```

The PDF is then generated by running:

```
include-pandoc --top-level-division=chapter --number-sections --latex-engine=xelatex -s -f markdown_strict+footnotes+auto_identifiers+implicit_header_references+header_attributes src/*markdown -o IFOSSLB.pdf
```

Useful explanations:

- `--top-level-division=chapter` treats the top level headings as separate chapters and makes them start on a new page.
- `--number-sections` adds number to the sections so it is possible to determine the level of each heading
