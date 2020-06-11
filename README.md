
<!-- README.md is generated from README.Rmd. Please edit that file -->

# r2dii.banks <a href='https://github.com/2DegreesInvesting/r2dii.banks'><img src='https://imgur.com/A5ASZPE.png' align='right' height='43' /></a>

<!-- badges: start -->

[![lifecycle](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)
[![CRAN
status](https://www.r-pkg.org/badges/version/r2dii.banks)](https://CRAN.R-project.org/package=r2dii.banks)
<!-- badges: end -->

This is a meta package to easily install and load the tools we build for
banks. Run `library(r2dii.banks)` to see the name of the packages in
this collection. Learn more about each package at a link of the form
`https://2degreesinvesting.github.io/<package name goes here>/` – for
example, <https://2degreesinvesting.github.io/r2dii.data/>, or
<https://2degreesinvesting.github.io/r2dii.match/>.

## Installation

You can install r2dii.banks from GitHub with:

``` r
# install.packages("devtools")
devtools::install_github("2DegreesInvesting/r2dii.banks")
```

[How to minimize installation
errors?](https://gist.github.com/maurolepore/a0187be9d40aee95a43f20a85f4caed6#installation)

And you can load it with:

``` r
library(r2dii.banks)
#> Loading required package: r2dii.analysis
#> Loading required package: r2dii.data
#> Loading required package: r2dii.match
```

Notice that r2dii.banks automatically loads other r2dii packages for
banks.
