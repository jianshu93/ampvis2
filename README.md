
[![Travis-CI Build Status](https://travis-ci.org/MadsAlbertsen/ampvis2.svg?branch=master)](https://travis-ci.org/MadsAlbertsen/ampvis2)

Tools for visualising amplicon data
===================================

ampvis2 is an R-package to conveniently visualise and analyse 16S rRNA amplicon data in different ways.

Installing ampvis2
------------------

First, install [R (3.4.1 or later)](https://mirrors.dotsrc.org/cran/) and [RStudio](https://www.rstudio.com/products/rstudio/download/#download). Windows users should also install [RTools](https://mirrors.dotsrc.org/cran/bin/windows/Rtools/). Then open RStudio as administrator (!) and run the commands below to install ampvis2 from the console:

``` r
install.packages("remotes")
remotes::install_github("MadsAlbertsen/ampvis2")
```

Get started
-----------

For a quick guide on how to use ampvis2 go to the [Get Started](https://madsalbertsen.github.io/ampvis2/articles/ampvis2.html) page. Detailed documentation of all ampvis2 functions can be found at the [Functions](https://madsalbertsen.github.io/ampvis2/reference/index.html) page.

Shiny
-----

An interactive Shiny app with some of the basic functionality of ampvis2 can be found at: <https://kasperskytte.shinyapps.io/shinyampvis>

Releases
--------

To install a specific (older) release of ampvis2 use `"@release"` as suffix, fx `remotes::install_github("madsalbertsen/ampvis2@2.0")` to install the first release (2.0) of ampvis2. The latest stable release can be installed with `remotes::install_github("madsalbertsen/ampvis2@*release")`.
