# FreescaleDocumentation

Here you can find the needed Sphinx code to generate documentation regarding the Freescale Cup. It is meant to be a Getting Started guide for competitors completely new to programming and Matlab/Simulink.

## Prerequisites

* Python (as a prerequisite for Sphinx)
* Sphinx ([homepage](http://sphinx-doc.org))
* LaTeX distribution (**optional**, for building the *pdf* version)

## Usage

To compile the source into HTML or LaTeX:
* run `make html` to obtain the HTML output in `build/html`
* run `make latex` to obtain LaTeX building files in `build/latex`, then run `make pdflatex` to compile

The documentation has been optimized for HTML and LaTeX outputs. However, Sphinx offers multiple other formats. Run `make` in the root folder to obtain a list of all possible output formats.
