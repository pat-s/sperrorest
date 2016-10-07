# sperrorest 0.3 (04 Oct 2016)

* add `sperrorest.par`: This function lets you exexute `sperrorest` in parallel. 
It uses a `doParallel` and `foreach` setup and works on all major platforms with
some constraints on Windows (no console output). This function is useful for 
running CV setups with many repetitions and/or models with take quite long to 
converge. 

* add `partition.factor.cv`: This resampling method enables partitioning based 
on a given factor variable. This can be used, for example, to resample 
agricultural data that is grouped by fields, at the agricultural field level 
in order to preserve spatial autocorrelation within fields.

* create github repo of `sperrorest` at 
[https://github.com/pat-s/sperrorest/](https://github.com/pat-s/sperrorest/)

* add package NEWS

* add package vignette

# sperrorest 0.2-1 (19 June 2012)

* First release on CRAN

# sperrorest 0.2-0 (19 June 2012)

* last pre-release version
* replaced Stoyan's data set with Jannes Muenchow's data, adapted examples


# sperrorest 0.1-5 (1 Mar 2012)

* made training set estimation optional
* robustified code using try()


# sperrorest 0.1-2 (29 Jan 2012)

* internal release 0.1-2
* some bug fixes, e.g. in err.* functions
* improved support of pooled versus unpooled error estimation
* changed some argument names
* this version was used for Angie's analyses

# sperrorest 0.1-1 (29 Dec 2011)

* built internal release 0.1-1

# sperrorest 0.1

* general code development (2009 - 2011)
* package project and documentation created (Oct-Dec 2011)