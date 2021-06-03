# forked r-quantities/errors with custom printing of uncertainties

The original package prints 12.34 +- 3.78 as "12.34(378)". This fork has been modified to print instead "12.34(3.78)".
## Installation

The installation of this forked package requires the
[remotes](https://cran.r-project.org/package=remotes) package.

```r
# install.packages("remotes")
remotes::install_github("alusiani/errors")
```
# original documentation: errors: Uncertainty Propagation for R Vectors

[![Build Status](https://github.com/r-quantities/errors/workflows/build/badge.svg)](https://github.com/r-quantities/errors/actions)
[![Coverage Status](https://codecov.io/gh/r-quantities/errors/branch/master/graph/badge.svg)](https://codecov.io/gh/r-quantities/errors)
[![CRAN\_Status\_Badge](https://www.r-pkg.org/badges/version/errors)](https://cran.r-project.org/package=errors)
[![Downloads](https://cranlogs.r-pkg.org/badges/errors)](https://cran.r-project.org/package=errors)
[![DOI](https://img.shields.io/badge/doi-10.32614/RJ--2018--075-informational.svg)](https://doi.org/10.32614/RJ-2018-075)

The **errors** package provides support for easurement errors in R
vectors, matrices and arrays: automatic uncertainty propagation and
reporting.

## Documentation

See [the initial blog post](https://www.enchufa2.es/archives/errors-0-0-1.html).
The package includes a vignette that is an up-to-date version of the following
R Journal publication, which should be used for citations:

- Iñaki Ucar, Edzer Pebesma and Arturo Azcorra (2018). "Measurement Errors in R." _The R Journal_, 10 (2), 549--557. DOI: [10.32614/RJ-2018-075](https://doi.org/10.32614/RJ-2018-075)

## Installation

```r
install.packages("errors")
```

and from github, using the [remotes](https://cran.r-project.org/package=remotes) package:

```r
# install.packages("remotes")
remotes::install_github("r-quantities/errors")
```
