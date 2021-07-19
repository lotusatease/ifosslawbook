# IFOSS Law Book

This repository contains the source files (in Markdown format) of the second edition of the IFOSS Law Book.

Any pull request will be authorized only by the copyright holders of the individual contributions.

> **NOTE**: **_Good, you are working on the `bugfix` branch_** 
> 
> Please always make pull requests to the `bugfix` branch first. 


For information on how to contribute, read `CONTRIBUTING.markdown`.


## Generating the PDF with Pandoc

Generating a full-book PDF now works by running (requires Pandoc 2.0 or later):

```
pandoc --top-level-division=chapter --number-sections --latex-engine=xelatex -s -f markdown_strict+footnotes+auto_identifiers+implicit_header_references+header_attributes+yaml_metadata_block metadata.yaml src/*markdown -o IFOSSLB.pdf
```

Useful explanations:

- `--top-level-division=chapter` treats the top level headings as separate chapters and makes them start on a new page.
- `--number-sections` adds number to the sections so it is possible to determine the level of each heading


## Generating the ePub with Pandoc

Generating a full-book ePub now works by running (requires Pandoc 2.0 or later):

```
pandoc --top-level-division=chapter --number-sections -s -f markdown_strict+footnotes+auto_identifiers+implicit_header_references+header_attributes+yaml_metadata_block metadata.yaml --epub-cover-image='cover.png' src/*markdown -o IFOSSLB.epub
```

