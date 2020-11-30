# A short intro to LaTeX course

This is material for a short introduction workshop to LaTeX. It is mainly based upon ["The Not So Short Introduction to LaTeXe" by Tobias Oetiker, Hubert Partl, Irene Hyna and Elisabeth Schlegl](https://tobi.oetiker.ch/lshort/lshort.pdf). If you have any recommendations or remarks feel free to contact me.

## Installation of LaTeX distribution

There are different LaTeX distributions for several OS available (a overview can be found [here](https://www.latex-project.org/get/)), we suggest to install one of the following:

### Linux

TeX live: https://www.tug.org/texlive/ . Most Linux distributions provide collections of several LaTeX packages and you can install a basic setup by e.g. using:

```
sudo apt install texlive-base
```

### Mac

MacTeX: https://www.tug.org/mactex/ and some informations on the installer [here](https://www.tug.org/mactex/theinstaller.html)

### Windows

MiKTex: https://miktex.org/ they have a installation tutorial available [here](https://miktex.org/howto/install-miktex)

### TinyTex

TinyTex works across different OS and does not require admin privileges to install. It is interesting especially for R users (but also for others) as it can automatically install missing packages from within R. There are installation instructions and some general information about LaTeX distributions [here](https://yihui.org/tinytex/).

## LaTeX Editor

In general you could just use any text editor (e.g. [Emacs](https://www.gnu.org/software/emacs/) or [notepad++](https://notepad-plus-plus.org/downloads/)), but there are a lot of good [integrated development environments (IDE)](https://en.wikipedia.org/wiki/Integrated_development_environment) and we suggest to use [TeXstudio](https://www.texstudio.org/). It is worth noticing that also RStudio can be used as a LaTeX IDE. But feel free to find out your own preferred work flow.

## Online Editor

If you have trouble to install a LaTeX distribution on your computer there are some online services that provide a editor and LaTeX distribution with most packages readily installed. The most popular one is [overleaf](https://www.overleaf.com/).
