# latex-cv
[![Build Status](https://travis-ci.org/Blightwidow/CV.svg?branch=master)](https://travis-ci.org/Blightwidow/CV)

My Curiculum Vitae in Latex :rocket:. Compiled result are located in the build branch.

## Instructions

To modify this resume, install the dependencies:

```bash
sudo apt-get -qq update
sudo apt-get install -y texlive texlive-xetex xzdec texlive-fonts-recommended texlive-latex-extra texlive-fonts-extra dvipng texlive-latex-recommended
```
Modify the _cv.tex_ file and then build with:

```bash
rm -rf public
mkdir public
cd src
xelatex -interaction=nonstopmode -halt-on-error -output-directory ../public cv.tex
cd ..
```

Feel free to contact me to show me your work

## Licence

Derivated from the work of [Carmine Spagnuolo](mailto:cspagnuolo@unisa.it) under MIT License.
