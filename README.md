
<!-- README.md is generated from README.Rmd. Please edit that file -->

# rstanbmcm

<!-- badges: start -->

[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)
<!-- badges: end -->

The goal of rstanbmcm is to jointly model two event time distributions
(e.g. time to disease progression and time to death) within a Bayesian
relative survival mixture cure model framework, using the Stan engine
called from R.

## Installation

You can install the the development version from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("StatisticsHealthEconomics/rstanbmcm")
```

## Motivation

Mixture cure models are increasingly popular in health problem in
particular oncology. A Bayesian paradigm allows the explicitly
incorporation of uncertainties and principled synthesis of prior
knowledge such as via expert elicitation or previous trials. By
extending current methods to account for the dependence between event
times we leverage additional information to make better inferences and
decisions.

## Example

## Code of Conduct

Please note that the `york.course.excel.model.in.R` project is released
with a [Contributor Code of
Conduct](https://contributor-covenant.org/version/2/0/CODE_OF_CONDUCT.html).
By contributing to this project, you agree to abide by its terms.
