# How to contribute to IFOSSLB

Thank you for your willingness to contribute to IFOSSLB.

To keep the quality and coherence of this publication high, here are some easy guidelines that should be followed.


## Files

This are the working parts:

- `src/` contains the current sources in MarkDown
- `IFOSSLB.pdf` is the PDF of the whole book
- `IFOSSLB.epub` is the ePub the whole book


## Git branches

- `master` branch is always stable and always contains the latest actual release
- `bugfix` branch is the development version – ideally a cutting-edge, but working version
- any specific fixes and additions should go into their own branches before they are approved to be merged into the `bugfix` branch – a good idea to give it a descriptive name (e.g. `intro-2021-update` or `pandoc-automation`)


## Pull requests

After you fixed something in a branch, create a pull request to the `bugfix` branch.

Once it was tested in the `bugfix` branch for a while, a pull request can be made from `bugfix` to `master`.

The pull request to `master` has to be approved by at least 2 project members, and include no objections from project members.

Any changes to the content of a chapter need to be approved by at least one original chapter author.


## Naming convention

The individual source files are named according to the following convention:

```
10-Intro.markdown
20-History.markdown
50-Belgium.markdown
50-China.markdown
50-...

```

The position of the chapters Intro, History and is predetermined and the country chapters can simply be added as `50-$country_name.markdown` and they will be generated in the right order without the need to manually keep track of the order in a separate file. This also leaves space to introduce new groups of chapters before or after, as well.
