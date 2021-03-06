# abpackage

#### An R package for AB testing leveraging pre-period information

The abpackage implements PrePost, a Bayesian approach for the
estimation of the treatment effect in A/B testing.
When pre-period data are available, the method leverages the pre-period to
get a more accurate estimate of the treatment effect.

The abpackage assumes that the observations are Normally distributed
both in the pre-period and the post-period.
Furthermore, the package assumes that the observations in treatment and
control groups are identically distributed in the pre-period.

#### Installation

```r
install.packages("devtools")
library(devtools)
devtools::install_github("google/abpackage")
library(abpackage)
```
