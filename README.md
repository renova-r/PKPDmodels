# PKPDmodels

Functions to evaluate common pharmacokinetic and pharmacodynamic models and their gradients.

Compatibility updates by Renova.

Version 0.3.2.9001 declares the `deriv` import from `stats` in `NAMESPACE` and updates `DESCRIPTION` metadata: title capitalization, an `Authors@R` entry equivalent to the existing authors and maintainer, and removal of the stale optional `Date` field. No R function was changed.

## Install

```r
install.packages("PKPDmodels", repos = c(
  Renova = "https://renova-r.r-universe.dev",
  CRAN = "https://cloud.r-project.org"
))
```

Or install this exact release from its tag:

```r
install.packages("remotes")
remotes::install_github("renova-r/PKPDmodels@renova-0.3.2.9001")
```

[Release notes](NEWS.md) · [Renova package directory](https://github.com/renova-r/revival-catalog)

PKPDmodels is by Anne Dubois, Julie Bertand, France Mentre and Douglas Bates (maintainer); the original project is at <http://PKPD.R-forge.R-project.org>. License: GPL (>= 2); see [COPYING](COPYING).
