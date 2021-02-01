
# simpLin

<!-- badges: start -->
<!-- badges: end -->

The goal of simpLin is to conduct linear regression with C++ implementation. This package should be quicker than the `lm` function prepackaged in `R`.

## Installation

Install this package from GitHub. You will need to install `devtools` if you do not already have it.

``` r
# install.packages('devtools')
devtools::install_github('ConGibbs10/simpLin')
```

## Example

This is a basic example which shows you how to conduct linear regression with `simpLin`:

``` r
library(simpLin)
# predictor
x <- 1:10
# response
y <- 1:10 + rnorm(10)
# fit linear model
mlm <- simp_lin_R(x = x, y = y)
# explore results
mlm
```
