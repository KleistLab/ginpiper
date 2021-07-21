# ginpiper - Package for smooth curve estimation, R_e computation and plotting

[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![DOI:10.1101/2021.05.14.21257234](http://img.shields.io/badge/DOI-10.1101/2021.05.14.21257234-blue.svg)](https://doi.org/10.1101/2021.05.14.21257234)

This R package is used by GInPipe [[1]](#1) - Genome-based Incidence Estimation Pipeline - to draw a smooth incidence trajectory estimate, calculate the corresponding effective reproduction number and make correspoonding plots and tables.

## Dependencies

*ginpiper* uses the following packages:

  - ggplot2
  - R0
  - scales

## Installation

*ginpiper* can be installed in R using **devtools**:

```
install.packages("devtools")

library(devtools)
devtools::install_github("trofimovamw/ginpiper")
```
 
## Reference
<a id="1">[1]</a> 
Smith, M. R. and Trofimova, M., et al. (2021). Rapid incidence estimation from SARS-CoV-2 genomes reveals decreased case detection in Europe during summer 2020. medRxiv, https://github.com/KleistLab/GInPipe
