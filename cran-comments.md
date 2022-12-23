# Resubmission

This is a resubmission. In this version (0.1.1), several new features were added (see NEWS.md for details).

## Test environments

- R-hub windows-x86_64-devel (r-devel)
- R-hub ubuntu-gcc-release (r-release)
- R-hub fedora-clang-devel (r-devel)

## R CMD check results

- There were no ERRORs or WARNINGs. 

- NOTE:    

    > On fedora-clang-devel (r-devel)  
    > checking HTML version of manual ... NOTE  
    > Skipping checking HTML validation: no command 'tidy' found  
    > Skipping checking math rendering: package 'V8' unavailable  

    Response: This note does not seem to be related to our R package and can likely be ignored. 

## Downstream dependencies

There are currently no downstream dependencies for this package.

# Previous cran-comments

## Test environments

- R-hub windows-x86_64-devel (r-devel)
- R-hub ubuntu-gcc-release (r-release)
- R-hub fedora-clang-devel (r-devel)

## R CMD check results

- There were no ERRORs or WARNINGs. 

- NOTE:    

    > checking for detritus in the temp directory ... NOTE  
    > Found the following files/directories:  
    > 'lastMiKTeXException'  

    Response: This is a known Rhub issue (https://github.com/r-hub/rhub/issues/503) and can likely be ignored.
    
    > On fedora-clang-devel (r-devel)  
    > checking HTML version of manual ... NOTE  
    > Skipping checking HTML validation: no command 'tidy' found  
    > Skipping checking math rendering: package 'V8' unavailable  

    Response: This note does not seem to be related to our R package and can likely be ignored. 
    
    > checking CRAN incoming feasibility ... [6s/13s] NOTE  
    > Maintainer: ‘Arindam RoyChoudhury <arr2014@med.cornell.edu>’  
    > New submission  
    > Possibly misspelled words in DESCRIPTION:  
    > Peng (17:5)  
    > Phylogenetics (17:32)  
    > al (17:13)  
    > et (17:10)  


    Response: This is a new submission. These words are not misspelled.
    
## Downstream dependencies

There are currently no downstream dependencies for this package.
