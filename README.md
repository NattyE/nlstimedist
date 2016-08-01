# nlstimedist

[![Travis-CI Build Status](https://travis-ci.org/PlymouthUniversitySD/nlstimedist.svg?branch=master)](https://travis-ci.org/PlymouthUniversitySD/nlstimedist)

Installation
------------

To install the package, first ensure you have `devtools` installed. 

``` r
install.packages("devtools")
```

Then use the following code:

``` r
devtools::install_github("PlymouthUniversitySD/nlstimedist", 
                         auth_token = "26c2099ce9d1cad34c85951733fd23d11ce63c55")
```

To install the package with the vignettes:

``` r
devtools::install_github("PlymouthUniversitySD/nlstimedist",
                         auth_token = "26c2099ce9d1cad34c85951733fd23d11ce63c55",
                         build_vignettes = TRUE)
```
