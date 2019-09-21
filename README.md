
<!-- README.md is generated from README.Rmd. Please edit that file -->

# codinglab

<!-- badges: start -->

<!-- badges: end -->

The goal of codinglab is to store learnr tutorials in a package for
students to run on their local machines. These tutorials were developed
to teach introductory programming concepts as part of a statistics
course.

## Installation

You can install the development version of codinglab from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("harris-coding-lab/codinglab")
```

## Running Tutorials

To run a tutorial in this package, install the codinglab package, then
use the learnr function `run_tutorial` to launch the interactive
tutorial in your browser:

``` r
library(codinglab)
library(learnr)

# Run the first tutorial
run_tutorial("basic-syntax", package = "coding-lab")
```

The tutorials in order are:

1.  `basic-syntax`
2.  `reading-files`
3.  `if-statements`
4.  `loops`
5.  `functions`

Replace the first argument of `run_tutorial` with the appropriate
tutorial name to run it.
