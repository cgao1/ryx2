# rxy

<img src="image.jpg" width="200"/>

<!-- badges: start -->

[![Lifecycle: experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental)

<!-- badges: end -->

The goal of rxy is to provide an easy way to obtain results for correlation.

## Installation

You can install the development version of rxy like so:

``` r
if(!require("remotes")){
install.packages("remotes")
}
remotes::install_github(cgao0/rxy)
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(rxy)
library(MASS)
x<-ryx(Boston,"medv")
print(x)
summary(x)
plot(X)
```
