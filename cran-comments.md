## Test environments
* local macOS (10.12) install, R 3.3.1
* ubuntu 12.04 (on travis-ci), R 3.3.1
* win-builder (release and devel)

## R CMD check results
* For macOS and ubuntu there were no ERRORs, WARNINGs or NOTEs. 

* for win-builder release and devel versions there was one note:
   
   * checking CRAN incoming feasibility ... NOTE
   Maintainer: 'Andrew C. Hooker <andrew.hooker@farmbio.uu.se>'
   Possibly mis-spelled words in DESCRIPTION:
     pharmacometric (19:9)
     
   - The first portion is just stating that I am the maintainer.  
   - The second portion does not recognize the well known word "pharmacometric",
     see for example: https://en.wikipedia.org/wiki/Pharmacometrics
   
   
## Downstream dependencies
There are currently no downstream dependencies for this package.
