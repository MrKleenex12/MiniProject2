# Reflection: ph-rast_bmgarch

bmgarch is an R package for Bayesian time series models, maintained by Philippe Rast. Its timeline is declining with 2 gaps of at least three months. The project works in cycles: a burst of work to get a release onto CRAN, then a long quiet period once it is out.

The longest gap was 20 months, from January 2022 to August 2023, and it was easy to interpret. Every commit before it is CRAN submission prep, like "adressing rhub issues" and "cran comment," so the package was released and considered done. There was also a second cause. Issue #19 sat for six months with no reply, and when the maintainer finally answered he wrote, "I did not get any emails from this repo - this went unnoticed."

The recovery came from outside pressure. Andrew Johnson submitted PR #20, "Update deprecated syntax for future rstan compatibility," because a new version of rstan was going to break the package. After that, Philippe fixed the rest of the CI and CRAN checks. The same people drove it, since Andrew had also contributed before the gap. The project is Active with a v2.1.0 release in 2026. This means bmgarch wakes up when its dependencies force it to.
