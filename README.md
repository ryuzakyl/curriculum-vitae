# curriculum-vitae
The LaTeX source code for my CV.

## Available languages

* English (EN)
* Spanish (ES)

## Supported templates

* `fancy-cv`
    * English version file (`./fancy-cv/cv-en-normal.tex`)
    * Spanish version file (`./fancy-cv/cv-es-normal.tex`)
* other templates are still a work in progress.

## How to generate/build pdf file

### From the command line

For example, generating the .pdf for the english version of my regular CV in a `fancy` template

```bash
xelatex ./fancy-cv/cv-en-normal.tex
```

### Using Texmaker

When using texmaker for editing/build the CV, we must first change the `Quick Build` command. The instructions are the following:

* Go to `Options > Configure Texmaker > Quick Build`
* Choose `XeLaTeX + View PDF`
