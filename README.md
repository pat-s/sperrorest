
<!-- README.md is generated from README.Rmd. Please edit that file -->
[![CRAN\_Status\_Badge](http://www.r-pkg.org/badges/version/sperrorest)](http://cran.r-project.org/package=sperrorest)
[![Build Status](https://travis-ci.org/pat-s/sperrorest.svg?branch=master)](https://travis-ci.org/pat-s/sperrorest) (master)
[![Build Status](https://travis-ci.org/pat-s/sperrorest.svg?branch=dev)](https://travis-ci.org/pat-s/sperrorest) (dev)
[![Downloads](http://cranlogs.r-pkg.org/badges/sperrorest?color=brightgreen)](http://www.r-pkg.org/pkg/sperrorest)

sperrorest
==========

Spatial Error Estimation and Variable Importance

This package implements spatial error estimation and permutation-based spatial variable importance using different spatial cross-validation and spatial block bootstrap methods. To cite `sperrorest` in publications, reference the paper by A. Brenning (2012).

Installation
------------

Get the released version from CRAN:

``` r
install.packages("sperrorest")
```

Or the development version from Github:

``` r
devtools::install_github("pat-s/sperrorest", build_vignettes = TRUE)
```

References
==========

Brenning, A. (2005). Spatial prediction models for landslide hazards: Review, comparison and evaluation. *Natural Hazards and Earth System Science*, *5*(6), 853–862. doi:[10.5194/nhess-5-853-2005](https://doi.org/10.5194/nhess-5-853-2005)

Brenning, A. (2012). Spatial cross-validation and bootstrap for the assessment of prediction rules in remote sensing: The R package sperrorest. In *2012 IEEE International Geoscience and Remote Sensing Symposium* (pp. 5372–5375). doi:[10.1109/IGARSS.2012.6352393](https://doi.org/10.1109/IGARSS.2012.6352393)

Russ, G., & Brenning, A. (2010a). Data mining in precision agriculture: Management of spatial information. In E. Hüllermeier, R. Kruse, & F. Hoffmann (Eds.), *Computational Intelligence for Knowledge-Based Systems Design: 13th International Conference on Information Processingand Management of Uncertainty, IPMU 2010, Dortmund, Germany, June 28 - July 2, 2010. Proceedings* (pp. 350–359). Berlin, Heidelberg: Springer Berlin Heidelberg. doi:[10.1007/978-3-642-14049-5\_36](https://doi.org/10.1007/978-3-642-14049-5_36)

Russ, G., & Brenning, A. (2010b). Spatial variable importance assessment for yield prediction in precision agriculture. In *Lecture notes in computer science* (pp. 184–195). Springer Science + Business Media. doi:[10.1007/978-3-642-13062-5\_18](https://doi.org/10.1007/978-3-642-13062-5_18)