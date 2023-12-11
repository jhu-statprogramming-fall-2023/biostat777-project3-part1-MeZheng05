[![R-CMD-check](https://github.com/taiyun/corrplot/workflows/R-CMD-check/badge.svg)](https://github.com/taiyun/corrplot/actions)
[![codecov.io](https://codecov.io/github/taiyun/corrplot/coverage.svg?branch=master)](https://codecov.io/github/taiyun/corrplot?branch=master)
[![CRAN Status](https://www.r-pkg.org/badges/version/corrplot)](https://cran.r-project.org/package=corrplot)
[![CRAN Downloads](https://cranlogs.r-pkg.org/badges/corrplot)](https://www.r-pkg.org/pkg/corrplot)

# URL to the GitHub link to where the original R package came from.

Please click on the [link here](https://github.com/taiyun/corrplot)/

# URL to the deployed website that you will do in Part 1E

https://jhu-statprogramming-fall-2023.github.io/biostat777-project3-part1-MeZheng05.


# Description of the 5 things you customized in your pkgdown website.


In bslib, I added bg to change the page background color to black.

I also added fg for text color to be white.

I also used code-bg to change the code chunk color.

I added an icon in the navbar for people to easily navigate to the introduction page of the website.

I also added an icon in the navbar for people to go to the original github website that has this corrplot package. 




## Summary

R package **corrplot** provides a visual exploratory tool on correlation matrix that 
supports automatic variable reordering to help detect hidden patterns among variables.

corrplot is very easy to use and provides a rich array of plotting options in 
visualization method, graphic layout, color, legend, text labels, etc. 
It also provides p-values and confidence intervals to help users determine the 
statistical significance of the correlations.

For examples, see its
[online vignette](https://taiyun.github.io/corrplot/).


This package is licensed under the MIT license, and available on CRAN:
<https://cran.r-project.org/package=corrplot>.



## Basic example

```r
library(corrplot)
M = cor(mtcars)
corrplot(M, order = 'hclust', addrect = 2)
```
![Basic example](https://raw.githubusercontent.com/taiyun/corrplot/master/vignettes/webimg/rectangles-1.png)

## Download and Install

To download the release version of the package on CRAN, type the following at the R command line:

```r
install.packages('corrplot')
```

To download the development version of the package, type the following at the R command line:

```r
devtools::install_github('taiyun/corrplot', build_vignettes = TRUE)
```

## How to cite

To cite `corrplot` properly, call the R built-in command
`citation('corrplot')` as follows:

```r
citation('corrplot')
```

## List of Exported Function

`COL1()` Get sequential colors

`COL2()` Get diverging colors

`colorlegend()` Draw color legend.

`cor.mtest()` Significance test which produces p-values and confidence intervals for each pair of input features.

`corrMatOrder()` Reorder a correlation matrix.

`corrplot-package` Visualization of a correlation matrix

`corrplot.mixed()` Using mixed methods to visualize a correlation matrix.

`corrplot()` A visualization of a correlation matrix.

`corrRect.hclust()` Draw rectangles on the correlation matrix graph.

`corrRect()` Draw rectangle(s) on the correlation matrix graph.


## Reporting bugs and other issues

If you encounter a clear bug, please file a minimal reproducible example on 
[github](https://github.com/taiyun/corrplot/issues).

