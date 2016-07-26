# avm-bibliography

This repository contains a BibTeX file for papers that have used or are related to the Alternating Variable Method (AVM).
It was created by Phil McMinn and Gregory M. Kapfhamer, the researchers who created the open source AVM framework,
[AMVf](http://avmframework.org). You are free to use any of the entries in this file if you are interested in
citing one of these research papers in your own LaTeX document.

If you have used the AVM or the AVMf in your research, and you have papers that you would like included in the bibliography please email me (p.mcminn@sheffield.ac.uk) with the details, and we will add your paper(s) to the repository. Also, if you find any papers you know of using the AVM, please let me know also!

## Installation Instructions

You can type the following command if you want to clone this repository:

```shell
git clone https://github.com/AVMf/avm-bibliography.git
```

Now, you can type `cd avm-bibliography` and use the BibTeX file in your own LaTeX project.

Alternatively, you can use the repository as a git submodule of another repository. To do this, use the following command:

```shell
git submodule add -b master  https://github.com/AVMf/avm-bibliography.git avm-bibliography
```

Furthermore, a document that cites all of the entries in this bibliography can be created using `pdflatex` and `bibtex`; you may also compile to a PDF file using a wide variety of other tools, such as `latexmk`. You can type the following commands to create the summary document:

```shell
pdflatex avm-bibliography
bibtex avm-bibliography
pdflatex avm-bibliography
pdflatex avm-bibliography
```

## Problems or Praise?

If you find that some of the entries are incorrectly formatted and thus your LaTeX and BibTeX tools are not processing
them correctly, then please open a new issue and one of us will attempt to resolve your concerns.  Finally, if you find
this repository useful, then we hope that you will star it.
