# Thesis LaTeX Template
This template can be used for anything STEM related. An example can be found [here](example/example.pdf).

This works for the current version of [TeXstudio](https://www.texstudio.org/) in combination with [MiKTeX](https://miktex.org/).

thesis.tex is the main file which has to be executed. This imports your different sections/chapters, the title page, the declaration of authorship and all of the custom packages of doc_cfg.tex.

## Notable Packages:

- `pdfpages` to simplify the inclusion of external multi-page PDF documents
- `tikz` & `tikz-3dplot` to create (complex) graphics/drawings with 3D functionality
- `libertinus` which is a nice font, there are many fonts available
- `fancyhdr` for fancy headers, which for example can show the sections/chapters of your thesis
- `mathtools` is based on `amsmath` and fixes various deficiencies of `amsmath`

## Changed Settings:

- The automatic indentation when starting a new line has been removed
- Subsections until depth five will be enumerated
- Up to five subsections will be listed in the table of contents

## Custom Colors:

These are only a few of the new custom colors:

- `dkgreen` dark green
- `deepgreen` deep green
- `deepblue` deep blue
- `lava` dark red/orange, will be currently used for hyperlinks

## Code:

Code is used with `lstlisting` where the default language is Python. This can be changed when you give different parameters. It has a light and a dark theme.

## New Commands:

- new `\bar` and `\tild` commands because the bar/tilde were weirdly offset in math mode
