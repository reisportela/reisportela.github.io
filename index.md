---
title: "A bookdown Example"
author: "BPLIM staff"
date: "2019-05-27"
site: "bookdown::bookdown_site"
output: bookdown::gitbook
documentclass: book
bibliography: [book.bib, packages.bib]
biblio-style: apalike
link-citations: yes
github-repo: rstudio/bookdown-demo
description: "This is a minimal example of using the bookdown package to write a book. The output format for this example is bookdown::gitbook."
---
<img src="media/logo.png" width="32.8%" />

# Prerequisites

This is a _sample_ book written in **Markdown**. You can use anything that Pandoc's Markdown supports, e.g., a math equation $a^2 + b^2 = c^2$.

The **bookdown** package can be installed from CRAN or Github:


```r
install.packages("bookdown")
# or the development version

## devtools::install_github("rstudio/bookdown")
## bookdown::render_book("index.Rmd", "bookdown::epub_book")
## bookdown::render_book("index.Rmd", "bookdown::pdf_book")
```

Remember each Rmd file contains one and only one chapter, and a chapter is defined by the first-level heading `#`.

To compile this example to PDF, you need XeLaTeX. You are recommended to install TinyTeX (which includes XeLaTeX): <https://yihui.name/tinytex/>.


