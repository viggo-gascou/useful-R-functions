# useful-R-functions

A collection of R functions that I found useful for calculating, visualizing all sorts of different things in [R](https://www.r-project.org/about.htm).

Made in preparation to Applied Statistics Exam.

## Required libraries

If you want to knit the `.Rmd` files yourself make sure you have all the required libraries installed.
By running the following commands you can make sure that the required libraries are installed correctly:
```R
packages <- c("dplyr", "knitr",
              "kableExtra", "RColorBrewer",
              "UsingR", "ggplot2", "here", "rmarkdown")

install.packages(setdiff(packages, rownames(installed.packages())))
```
