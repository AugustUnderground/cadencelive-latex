# CadenceLIVE LaTeX Template

This is a public service.
Over [16 million](https://www.microsoft.com/investor/reports/ar21/index.html)
people have to use Microsoft Word everyday. If you, or someone you know, needs
help use this LaTeX template for the next CadenceLIVE. You are not alone.

## Overleaf Template

There is a _slightly_ out of date Template for 
[Overaleaf](https://www.overleaf.com/latex/templates/cadencelive-latex/shdqpqqmgjyt). 
Generally, the title graphic needs adjustment for the current year.

## Usage

Compile the paper with `pdflatex`:

```{shell}
$ pdflatex paper.tex
```

## Convert PNG Logo

Convert a current/different CadenceLIVE logo from png to pdf.

```{shell}
$ convert logo.png -quality 100 -density 150x150 logo.pdf
```
