METHimpute
==========


A tutorial is available [here](https://github.com/ataudt/methimpute/blob/master/vignettes/methimpute.pdf).

Installation
------------

### Development version from Github
To install the *development* version from Github, follow the steps given below. The installation has only been tested on Ubuntu so far, if you need to install on Windows or Mac additional steps might be necessary (e.g. installation of Rtools from https://cran.r-project.org/bin/windows/Rtools/)

1. Install a recent version of R (>=3.3.0) from https://www.r-project.org/
2. Optional: For ease of use, install Rstudio from https://www.rstudio.com/
3. Open R and install all dependencies. Please ensure that you have writing permissions to install packages. Execute the following lines one by one:

   install.packages("devtools")  
	 source("http://bioconductor.org/biocLite.R")  
	 biocLite(c("GenomicRanges"))  
	 library(devtools)  
	 install_github("ataudt/methimpute")  

How to use METHimpute
---------------------

Please refer to the [vignette](https://github.com/ataudt/methimpute/blob/master/vignettes/methimpute.pdf) for a tutorial.

Report Errors
-------------

If you encounter errors of any kind, please file an [issue here](https://github.com/ataudt/methimpute/issues/new). I will try to react within one day.
