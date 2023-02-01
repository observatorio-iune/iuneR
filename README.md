# IUNEverse

This R package is a metapackage, which integrates all the R packages we use for our analysis and work.

## Installation
Simply install from GitHub using the package `remotes` from CRAN.

```r
if (!require("remotes")) install.packages("remotes")
remotes::install_github("observatorio-iune/iuneverse")

# And then load into your current session
library(iuneverse)
```

## Information
A detailed list of the packages included on this metapackage can be found in DESCRIPTION file.
