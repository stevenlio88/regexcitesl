
<!-- README.md is generated from README.Rmd. Please edit that file -->

\*\*NOTE: This is a test package created for learning purposes.

# regexcitesl

<!-- badges: start -->
<!-- badges: end -->

This package contain one function for parsing a string using user
defined delimiter.

## Installation

You can install the released version of regexcitesl from
[GitHub](https://github.com/stevenlio88/regexcitesl) with:

``` r
#install.packages("devtools")
devtools::install_github("stevenlio88/regexcitesl")
```

## Example

This is a basic example which shows you how to use the function
`str_split_one()`:

``` r
library(regexcitesl)

x <- "a, b, c"
str_split_one(x, pattern = ",")
#> [1] "a"  " b" " c"
```
