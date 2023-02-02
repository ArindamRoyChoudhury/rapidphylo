# Package ‘rapidphylo’

## Overview

`rapidphylo` is an R package for rapid estimation of tree-topology from large allele frequency data using Root Distances Method, under a Brownian Motion model. This is achieved by first computing the maximum likelihood estimates of the root distances, and then inferring the tree-topology from them. 

## Installation

Install the released version of this package from CRAN

```r
install.packages("rapidphylo")
```

Or install the development version of this package from GitHub

```r
remotes::install_github('ArindamRoyChoudhury/rapidphylo', upgrade="never")
```


## Example

```r
# A dataset "Human_Allele_Frequencies" is loaded with the package; 
# it has allele frequencies in 31,000 sites for 4 human populations and one outgroup human population.

# check data dimension
dim(Human_Allele_Frequencies)

# run RDM function
rd_tre <- RDM(Human_Allele_Frequencies, outgroup = "San", use = "pairwise.complete.obs")

# result visualization
plot(rd_tre, use.edge.length = FALSE, cex = 0.5)
```
