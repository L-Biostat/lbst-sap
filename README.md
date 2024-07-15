# L-Biostat SAP <img align="right" height="100" src="https://ibiostat.be/images/IBiostat-logo.png/@@images/image/preview">

Quarto extension for a template to generate a PDF (or an html file) for a 
statistical analysis plan (SAP) for a L-Biostat project.

The document has SAP-specific styling, including headers and footers, the logo
of L-Biostat, ...

## Installation and use

To install the Quarto extension, create a directory, and use the template file:

``` bash
quarto use template L-Biostat/lbst-sap
```

To use the extension in an existing project without installing the template 
file:

``` bash
quarto install extension L-Biostat/lbst-sap
```

To use the template in a project, simply use

```
format:
  pdf: lbst-sap
```

for pdf outputs, or 

```
format:
  html: lbst-sap
```

for html outputs, in the `yaml` header of your main quarto file.

## Adjusting details

For the moment, the address field in the footer still needs to be customized by
hand in the `_extension/lbst-sap/header.tex` file.


## Example

Here is the source code for a minimal sample document: 
[template.qmd](template.qmd).

