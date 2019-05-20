<p align="center"><img width=25% src="https://github.com/AranBorkum/Latex-Template/blob/master/Pictures/sussexLogo.png"></p>

# Latex-Template for disertations/thesis
![Latex](https://img.shields.io/badge/latex-current-brightgreen.svg) ![Dependencies](https://img.shields.io/badge/dependencies-up%20to%20date-brightgreen.svg)      ![issues](https://img.shields.io/badge/issues-none-brightgreen.svg) ![Contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg) ![Licence](https://img.shields.io/badge/licence-to_thrill-brightgreen.svg) 

# Basic Overview:
  - Basic template for writing large, properly formatted documents using LaTeX
  - Constructed as a multi document system, compiled through the `main.tex` file

## Features
  - All sections formed seperately to aid organisation
  - Fancy header pre-formatted as an added stylistic feature

### Initialisation

This templated can be downloaded from  [here](https://github.com/AranBorkum/Latex-Template). Addionally, if you have a GitHub account you can get one [here](https://github.com/) and then clone the template directory using the command
```sh
$ cd /where/you/want/the/files/to/be/
$ git clone https://github.com/AranBorkum/Latex-Template.git
```

### Bibliography

It is recomended that you use bibtex to make your bibliography. The structure by which a bibtex file is made can be complicated, therefore it is recomended that you use some kind of front end GUI, such as BibDesk. The file bibliography.bib is included in this folder and so you can use that as a reference on how to construct a bibtex style reference. Furthermore, there are online generators such as [this](http://www.bibme.org/bibtex).

### Compilation

Your computer or server will require a LaTeX compiler to run the document constructor. My recomendation is MacTex for OSX, however, you can also use Overleaf or your preferred variant. It is also possible to compile this document through the command-line using the command:

```sh
$ pdflatex main.tex
$ bibtex main
$ pdflatex main.tex
$ pdflatex main.tex
```
This may look like a strange sequence of commands, but LaTeX is strange. This will produce a file `main.pdf`, amongst a number of other files which are not important.

### Issues and Development

Want to contribute? Awesome!

If you find any issues with this template, or you have a stylistic feature you think the template would benifit from, feel free to contact me at A.Borkum@sussex.ac.uk and we can discuss additions and fixes further.


