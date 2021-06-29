# metajdt

metajdt is an R package built to accompany my blog post, ["Creating Your Own R Package 'verse'"](https://jdtrat.com/blog/creating-your-own-package-verse/). 

It was created with [metamakr](https://github.com/jdtrat/metamakr) and combines two of my CRAN packages, [shinysurveys](https://shinysurveys.jdtrat.com/) and [ghee](https://jdtrat.com/project/ghee).

It can be installed and loaded as follows:

```r
if (!require(remotes)) install.packages("remotes")
remotes::install_github("jdtrat/metajdt")
library(metajdt)
#> ── Attaching packages ──────────────────────────────────── metajdt 0.0.0.9000 ──
#> ✓ shinysurveys 0.1.2     ✓ ghee         0.1.0
```
