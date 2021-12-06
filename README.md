# Term Paper Template for Uni Mannheim
This R package provides a template for writing term papers for Uni Mannheim in R Markdown, and compiling to PDF via the LaTeX.


## Installation
``` r
# The package isn't on CRAN - install the development version from GitHub:
# install.packages("devtools")
devtools::install_github("vktrsmnv/unima")
```

## Usage
The easiest way to use the template is with RStudio, via File -> New File -> R Markdown...
In the dialog box, click 'From Template', then find the new 'Uni Mannheim Term Paper' option, choose a name for your manuscript (e.g. 'Test'), then click OK:

A new folder named *Test* is created, and you see an open **Test.Rmd** file:

If you click 'Knit', it compiles to the example PDF output with the illustration content from **Test.Rmd**:

