# IFOSS Law Book

## Introduction

Open source has travelled a long way from its beginnings as a way to share software between engineers. The evolution has been long and occasionally winding, though in retrospect the result was inevitable. Open source is now a process approach for collaboration. It has clearly known effective approaches, governance and supportive international standards. Underlying all this, of course, is law. Law provides the framework from which parties who do not know each other may engage with a degree of certainty. It provides pillars of structure and redress. It is the formal and stilted language that transcends normal discourse, and allows impartial judgement where necessary. 

This book contains law as it pertains to open source with an optic that reflects the global nature of the field. It illustrates the nuance of law as it applies to open source country by country, and in doing so it allows us to follow the thin threads of structure that highlight both the similarities and the differences necessitated by different geographies and cultures. While not conclusive, this book can act as an adequate guide in this field, and delivers a resource intended to be of equal use to those new and experienced.

## What You Will Find Here

This repository contains the printable and source files of the second edition of the IFOSS Law Book.

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

