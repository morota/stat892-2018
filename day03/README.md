## Overview

This is an interacitive tutorial for [R](https://www.r-project.org/) based on the [learnr](https://cran.rstudio.com/web/packages/learnr/index.html) package. 
You can start the tutorial by executing the following R code. 

```r
download.file("https://raw.githubusercontent.com/morota/stat892-2018/gh-pages/day03/day03.Rmd", destfile = "day03.Rmd")
install.packages("learnr")
library(learnr)
rmarkdown::run("day03.Rmd")
```