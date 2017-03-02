---
title: "Spatial data in R: new directions"
author: |
   | Edzer Pebesma^1^ 
   |
   | 1. Institute for Geoinformatics, University of Muenster, Germany
institute: 
   - $^1$Heisenbergstrasse 2, 48149 Muenster, Germany
output: html_document
---

**Keywords**: Spatial data, simple features, raster data, time series, tidyverse


# Introduction

Working with spatial data in R goes back to the early days
of R itself. For many spatial statistics and spatial analysis
methods, R provides reference implementations. Spatial classes and
methods in packages [sp](https://cran.r-project.org/package=sp)
and [raster](https://cran.r-project.org/package=raster),
together with interfaces to GEOS and GDAL in
[rgeos](https://cran.r-project.org/package=raster),
[rgdal](https://cran.r-project.org/package=raster) along with a
few hundred packages depending on those have formed the cornerstone
for many analysts for a long time.

Recent developments in the areas of data standardisation, web-based
visualisation and computing, spatial databases, scalability,
as well as R developments such as pipe-based workflows and
the tidyverse have stimulated to rethink the way we handle
spatial data in R. This has for instance resulted in package
[sf](https://cran.r-project.org/package=sf), a package that has
been developed with support from the R consortium.

This workshop will illuminate old and the new ways of handling
spatial data in R, will put some focus on handling simple features,
and will discuss challenges ahead.

# Learning objectives

After this workshop, participants should understand

* what simple features are, where they come from, and how they can be handled in R
* how spatial data can be imported and exported in R
* what spatial reference systems and coordinate transformations are
* what geometrical operations are
* how simple features can be used in pipe-based workflows
* what the current options and limitations are for handling time series, raster, and spatial time series data

# Tutorial content

A tentative overview of the tutorial content is:

* A short history of handling spatial data in R
* Simple feature access
* Tidyverse and list-columns
* Package sf
* Methods for simple features
* Coordinate reference systems, and where to put them
* Pipe-based workflows
* Array data: rasters and time series
* Spatial time series
* Outlook

# Pre-requisites

It is assumed that participants are familiar with R, and have some
notion of spatial data. It is not required that they have a working
knowledge of all the terms mentioned in this workshop description.

# Potential attendees

Potential workshop attendees include data scientists and people
working in a domain where they are faced with spatial data,
e.g. ecologists, hydrologists, climate scientists, epidemiologists,
social scientists, geographers, geoscientists, business intelligence
analysts, and so on.

# Instructor biography

[Edzer
Pebesma](https://www.uni-muenster.de/Geoinformatics/en/institute/staff/index.php/119/Edzer_Pebesma)
is full professor at the institute for geoinformatics of
the university of Muenster. He is one of the authors of
the book [Applied Spatial Data Analysis with R, second
edition](http://www.asdar-book.org/), and is author and
maintainer of a handful of packages found on his [github
page](https://github.com/edzer).

The material for this tutorial will also be developed [on
github](https://github.com/edzer/UseR2017/).

