# minimal-r-package-discuss

Discussion place for R packages built with "extras", special libraries and bindings. 

This [GitHub diminutive organization](https://github.com/diminutive) holds a collection of *minimal R packages*, designed to illustrate special cases. 

Use this repo to [discuss issues](https://github.com/diminutive/minimal-r-package-discuss/issues), contribute fixes or enhancements, and contribute your own examples.

## Minimal R packages

These examples vary in quality and currency. (A definite problem right now is that some will point to the wrong organization for CI badges and installation instructions - please submit a PR if you use one and make updates!). 

Package | Description
-------------------------------------------------------------- | ----------------------------------
[depbioc](https://github.com/diminutive/depbioc.git)           | minimal R package with import from a Bioconductor package
[depsf](https://github.com/diminutive/depsf.git)               | Minimal R package importing sf with CI testing on Travis
[earcut.cpp](https://github.com/diminutive/earcut.cpp.git)     | Minimal C++ bindings of Mapbox earcut.hpp for R
[gdalmin](https://github.com/diminutive/gdalmin.git)           | Minimal R package with bindings to GDAL, built from source a la rgdal
[gdalosx](https://github.com/diminutive/gdalosx.git)           | Test a system package install of GDAL on OSX with Travis
[ncdep](https://github.com/diminutive/ncdep.git)               | CI testing for NetCDF with R
[rgdalwinhdf4](https://github.com/diminutive/rgdalwinhdf4.git) | Build rgdal on Windows with Appveyor, and read HDF4
[rglmin](https://github.com/diminutive/rglmin.git)             | minimal R package importing rgl

## Miscellaneous package tests and other stuff

These packages were created to prove a point, or demonstrate something in the *works on x machine* sense

Package | Description
-------------------------------------------------------------- | ----------------------------------
[brwsrchk](https://github.com/diminutive/brwsrchk.git)         | Does R CMD check warn / error on browser() calls?
[dputtruncat](https://github.com/diminutive/dputtruncat.git)   | R package to show dput truncation

These are probably not worth mentioning, see gdalmin and gdalosx and rgdalwinhdf4 as more current examples for gdal stuff. 

[gdal.rhub](https://github.com/diminutive/gdal.rhub.git), [hdf4.rhub](https://github.com/diminutive/hdf4.rhub.git), [hdf5.rhub](https://github.com/diminutive/hdf5.rhub.git), [anc](https://github.com/diminutive/anc.git) 


## Why maintain minimal packages? 

The repos grew naturally out of informal and "scatter gun" testing and exploration. When I finally learn how to get something to work I like to have a tiny example, because *I know it worked once* and an actual package is good proof. It's extremely easy to move on from that simple example, complicate things and get lost - and then you're in git hell or worse. It's also hard to fork a functional package and strip it back to just that part you need, it's exactly this *getting started* core that I'm often looking for. 

Ideally these might be canonical, the perfect starting point if you need *library IJK* in an R package - just fork it, test it, and starting specializing it. These examples are definitely not good enough for that, yet. 

## Other minimal R package resources

https://github.com/ropenscilabs/tic  (this one's fantastic, stands out as minimal example gold mine on its own)

https://github.com/rstudio/bookdown-demo  (minimal bookdown)

https://github.com/rstudio/blogdown (Blogdown will create a functional project for you)

https://github.com/yihui/rmini

http://kbroman.org/pkg_primer/pages/minimal.html

https://github.com/b4winckler/reverse

https://github.com/yixuan/miniGPU

https://github.com/metacran/mason.rpkg

https://github.com/metacran/mason

