This repository contains the LaTeX code of my MSc dissertation project with title "Evaluating the Performance and Anonymity of Mix Networks". You can find the pdf version of my project [here](https://github.com/Erodotos/msc-dissertation/blob/master/skeleton.pdf)

To compile the `skeleton.pdf` report, with all cross-references resolved:
```
pdflatex skeleton.tex
bibtex skeleton.aux
pdflatex skeleton.tex
pdflatex skeleton.tex
```

Many TeX distributions have (or can install) a `latexmk` command that will
automatically compile everything that is needed:
```
latexmk -pdf skeleton.tex
```

If the logo causes compilation problems (errors related to `eushield`), it isn't
necessary, you may remove the `logo` option from the first line of code.
Although check first that you are using `pdflatex` or the `-pdf` option above.
