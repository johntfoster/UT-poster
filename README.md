# UT Engineering Poster Template

Conforms to both The University of Texas [Visual Style Guide](https://www.utexas.edu/brand-guidelines/visual-style-guide) and the Cockrell School of Engineering [Visual Guidelines](http://www.engr.utexas.edu/visualguidelines).

To get my `include` folder:

````
git submodule init
git submodule update
````

Currently only works with the `latex -> dvips -> ps2pdf` workflow.  To build run:

````
latex poster.tex
latex poster.tex
latex poster.tex
bibtex poster
latex poster.tex
latex poster.tex
dvips poster.dvi
ps2pdf poster.ps
````

Or alternatively use `latexmk poster.tex`
