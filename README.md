# Zenika Pandoc Template

## Installation

Install `pandoc` on your computer. See https://pandoc.org/installing.html
Install Latex that is used to generate PDF from Markdown via pandoc.

* Windows : [MiKTeX](https://miktex.org/)
* MacOs: [MacTeX](https://tug.org/mactex/)
* Linux: texlive package 

## Usage

Generate the report with the following command :

```shell
pandoc compte_rendu.md -o compte_rendu.pdf --template=template.tex
```

The template is defined in the template.tex file. This file is based on the default template used
by pandoc. An exemple markdown file with the name `compte_rendu.md` can be used as a starter.

## CI

.drone.yml and .travis.yml are CI's pipeline configurations that can be used with DroneCI and Travis.
The DroneCI pipeline generates a new PDf when a tag is pushed and save it to a gitea instance repository.
This was the original CI for this projet. The travis pipeline should be upgrade to match this functionalities.