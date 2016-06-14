# D&D 5e LaTeX Template

This is cloned attempt of Anodery's attempt at creating a D&D 5e LaTeX template.

The template compiles with pdflatex.

[Original Version by Anoderay](https://github.com/anoderay/DND-5e-LaTeX-Template/)


### Installation

This assumes you have already installed a LaTeX environment with the pdflatex executable.

Just clone the repo. From terminal:

```sh
$ git clone https://github.com/almightynassar/rpg-latex-template.git 5e-template
$ cd 5e-template
$ pdflatex example.tex
```

If you don't have LaTeX installed, the following should help you out:
#### Ubuntu
```sh
sudo apt-get install texlive-full
```
#### Arch
```sh
sudo pacman -S texlive-bin texlive-core texlive-latexextra
```
It's a bit unclear exactly what subset of features this module needs. As a general rule, we'd recommend installing one of larger ones.

### Package Options
- bg-letter: Loads a letter-sized background-image
- bg-a4: Loads an A4-sized background-image
- bg-print: Loads a printer-friendly background-image (only decal at the bottom)
- bg-full: Loads the full background-image

Per default "bg-letter" and "bg-full" are loaded.

### Image Credit

 - Credit for the background image goes to http://lostandtaken.com/
 - Credit for the fantasy icon goes to https://commons.wikimedia.org/wiki/File:Fantasy_icon.svg

### License
The MIT License (MIT)

Copyright (c) 2016 Evan Bergeron

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
