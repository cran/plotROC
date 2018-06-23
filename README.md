
[![Build Status](https://travis-ci.org/sachsmc/plotROC.png?branch=master)](https://travis-ci.org/sachsmc/plotROC)
[![DOI](https://zenodo.org/badge/9473/sachsmc/plotROC.svg)](http://dx.doi.org/10.5281/zenodo.14678)
[![](http://cranlogs.r-pkg.org/badges/plotROC)](https://CRAN.R-project.org/package=plotROC)

# Generate interactive ROC plots from R using ggplot

Most ROC curve plots obscure the cutoff values and inhibit
    interpretation and comparison of multiple curves. This attempts to address
    those shortcomings by providing plotting and interactive tools. Functions
    are provided to generate an interactive ROC curve plot for web use, and
    print versions. An interacive Shiny application is also included.
    
## Installation

This is the development version of the package. It can be installed from github with

```r
devtools::install_github("hadley/ggplot2")
devtools::install_github("sachsmc/plotROC")
```

## Basic usage

See examples live [here](http://sachsmc.github.io/plotROC)

# Acknowledgements

This package would not be possible without the following:

  - [ggplot2](http://ggplot2.org/)
  - [gridSVG](http://sjp.co.nz/projects/gridsvg/)
  - [d3.js](http://d3js.org)
  
# Citation

Read the code snippet article at JSS! (Coming soon)
  
# License
The MIT License (MIT)

Copyright (c) 2017 Michael C Sachs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.


  
