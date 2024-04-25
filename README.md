# A toolset for Reliability, Availability, and Maintainability analysis

`RAM`, standing for Reliability, Availability, and Maintainability, serves as a toolset for RAM analysis. This method is instrumental in accurately estimating a system's production parameters, encompassing factors such as failure modes, frequencies, and their respective consequences.


## The package

The stable version of `RAM` can be installed from CRAN using:
```r
install.packages("RAM")
```

The development version of `RAM` can be installed from GitHub (`remotes` needed):
```r
if (!requireNamespace("remotes", quietly = TRUE))
   install.packages("remotes")
   
remotes::install_github("mariochacano/RAM")
``` 

Finally load the package in your current R session with the following R command:
```r
library(RAM)
```

## Authors & Contacts

Issues can be reported on https://github.com/mariochacano/RAM/issues.

- Mario Chacano: mchacano@ubiobio.cl
