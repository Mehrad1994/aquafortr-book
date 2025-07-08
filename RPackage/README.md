# AquaFortR

<!-- badges: start -->
[![R-CMD-check](https://github.com/ahomoudi/AquaFortR/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/ahomoudi/AquaFortR/actions/workflows/R-CMD-check.yaml)
[![Quarto Publish](https://github.com/ahomoudi/AquaFortR/workflows/Quarto%20Publish/badge.svg)](https://github.com/ahomoudi/AquaFortR/actions?query=workflow:"Quarto+Publish")
[![GitHub tag](https://img.shields.io/github/tag/ahomoudi/AquaFortR?include_prereleases=&sort=semver&color=blue)](https://github.com/ahomoudi/AquaFortR/releases/)
[![License](https://img.shields.io/badge/License-CCBY-blue)](#license)
<!-- badges: end -->


The project's [repository](https://github.com/ahomoudi/AquaFortR/) is structured as follows:

 - QuartoBook  
 - RPackage  
 - AquaFortR_Swirl

## Installation & Materials

### Package

To install the AquaFortR package, please use: 

```r
remotes::install_github("ahomoudi/AquaFortR", subdir = "RPackage")
```
### Swirl
To install the AquaFortR Swirl Course, please download the compressed course from 
<a href="AquaFortR_Swirl.zip">here</a> and use the code below. 

```r
swirl::install_course_zip("path/to/AquaFortR_Swirl.zip")
```

### Book 

Materials for the chapter 2 are available <a href="AquaFortR_Codes.zip">here</a>. Please, 
revise the path to the shared libraries files in the R-Fortran functions.


## Funding

This work has been funded by the German Research Foundation (DFG) through the 
project NFDI4Earth (DFG project no. 460036893, <https://www.nfdi4earth.de/>) 
within the German National Research Data Infrastructure (NFDI, <https://www.nfdi.de/>).

<!-- ## Citation -->

<!-- ``` -->
<!-- @book{AquaFortR, -->
<!--   author = {Ahmed Homoudi}, -->
<!--   year = 2024, -->
<!--   title = {AquaFortR: Streamlining Atmospheric Science, Oceanography, Climate, and Water Research with Fortran-accelerated {R}}, -->
<!--   URL = {https://doi.org/10.5281/zenodo.xxxxxxx}, -->
<!--   doi = {10.5281/zenodo.xxxxxxxx} -->
<!-- } -->
<!-- ``` -->

## Acknowledgement

Appreciation is extended to Dr. Klemens Barfus for providing invaluable 
Fortran routines to estimate CAPE. 

## License

This book is licensed under the Creative Commons Attribution-NonCommercial 4.0 
International (CC BY-NC 4.0) License (<https://creativecommons.org/licenses/by-nc/4.0/>).


<!---  setwd("C:\\Projects\\AquaFortR") --->
