# wrspathrow

[![Build Status](https://travis-ci.org/azvoleff/wrspathrow.png)](https://travis-ci.org/azvoleff/wrspathrow)

## Overview

The `wrspathrow` package includes the full Worldwide Reference System (WRS) 1 
and WRS 2 grids used by NASA for cataloging Landsat scenes. The package allows 
fetching the path and row numbers for a given spatial object, or conversely,
allows fetching a SpatialPolygonsDataFrame of the area covered by a given path
and row.

## Package Installation

As `wrspathrow` contains the full WRS-1 and WRS-2 polygon datasets, the packages 
is quite large (over 26MB when installed). For this reason it is not hosted on 
[CRAN](http://cran.r-project.org). The easiest way to install the package is to 
download it directly from GitHub (within R) using the
[devtools](http://cran.r-project.org/web/packages/devtools/index.html) package 
from Hadley Wickham. After installing `devtools` from CRAN, type:

```R
install_github('wrspathrow', username='azvoleff')
```

at the R prompt to install `wrspathrow`.

## Author Contact Information

[Alex Zvoleff](mailto:azvoleff@conservation.org)  
Postdoctoral Associate  
Tropical Ecology Assessment and Monitoring (TEAM) Network  
Conservation International  
2011 Crystal Dr. Suite 500  
Arlington, VA 22202  
USA
