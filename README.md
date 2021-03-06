# Reproducible Research in R: Geoinformatics, Epidemiology, and Publicly Available Health and GIS Data  

**Instructors**: Cole Brokamp, Chris Wolfe, Department of Pediatrics, Cincinnati Children's Hospital Medical Center; Cincinnati, OH  
**Setting**: Workshop for American College of Epidemiology 2018 Annual Meeting  
**Location**: University of Cincinnati, Medical Sciences Building (MSB), Room E-161  
**Date**: Sunday, September 23rd, 2018

*This workshop is supported by the Geospatial Research Accelerator for Precision Population Health (GRAPPH) at Cincinnati Children's Hospital Medical Center (CCHMC).*

## Description

This workshop is designed for `R` beginners who wish to conduct reproducible research using geoinformatics and epidemiology methods with publicly available health and geospatial data. Participants will gain a general understanding of the software tools available and learn how to explore and learn them further on their own.  Additionally, participants will gain applied experience through a "hands on" session using `R`. Over the course of one day, we will cover (1) an introduction to geoinformatics for epidemiology, (2) a `tidyverse` and `R` refresher, (3) why to use `R` for reproducible research, (4) using spatial data within `R`, and (5) creating maps in `R`. The course will culminate in an applied example in which attendees will analyze the relationship between community material deprivation and pediatric hospital utilization. The entire project, including data import, exposure assessment, exploratory data analysis, mapping, statistical analysis, and reporting, will be conducted within `R`. 

## Course Requirements

- Course attendees are expected to have an introductory knowledge of `R` and the `tidyverse`. Please review [R for Data Science](http://r4ds.had.co.nz/) ahead of time if you need a refresher.
- If planning on attending the second half of the workshop (a "hands on" applied example), the first half of the workshop is mandatory; however, participants can attend the didactic first half of the workshop without attending the second half of the workshop.
- To attend and participate in the "hands on" portion, please bring a computer with R and the following packages installed:
	- `tidyverse`
	- `sf`
	- `tidycensus`
	- `tigris`
	- `tmap`
	- `mapview`
- Alternatively, the class will take place in a computer lab with the necessary software preinstalled and available for use.

Please contact the course organizer, Cole Brokamp (cole dot brokamp at cchmc dot org) with any questions.

## Course Materials

All course materials will be hosted within [this repository](https://github.com/cole-brokamp/geoinformatics_and_population_health_in_R), including slides and example code.

Recommended supplementary readings include:

- [R for Data Science](http://r4ds.had.co.nz/)
- [Geocomputation with R](https://geocompr.robinlovelace.net/)
- [R-Spatial hub](http://r-spatial.org/)

## Detailed Course Outline

1. Introduction to Geoinformatics for Epidemiology [[slides](https://github.com/cole-brokamp/geoinformatics_and_population_health_in_R/blob/master/GRAPPH_talk_ACE_2018_optimized.pdf)]
	- geomarkers
	- geocoding
	- geospatial data
	- geomarker assessment
	- examples
2. `tidyverse` Refresher [[Rmd](https://raw.githubusercontent.com/cole-brokamp/geoinformatics_and_population_health_in_R/master/tidyverse/ACE_tidy_pres.Rmd) / [slides](https://rawgit.com/cole-brokamp/geoinformatics_and_population_health_in_R/master/tidyverse/ACE_tidy_pres.html#1)]
	- tidy data structures
    - `magrittr` and the pipe operator
    - `dplyr`: `select()`, `filter()`, `mutate()`, `rename()`
    - `tidyr`: `spread()`, `gather()`
    - `tidycensus`
3. Geospatial data in `R` [[Rmd](https://raw.githubusercontent.com/cole-brokamp/geoinformatics_and_population_health_in_R/master/geospatial_data_in_R/geospatial_data_in_R.Rmd) / [slides](https://rawgit.com/cole-brokamp/geoinformatics_and_population_health_in_R/master/geospatial_data_in_R/geospatial_data_in_R.html)]
	- data formats and projections
	- simple features and `sf` package for R
    - Mapping in `R` (`ggplot2`, `tmap`, `mapview`)
    - `tigris` (and `tidycensus`)
4. Why to use `R` for reproducible research
    - what is reproducible research?
    - `knitr` and R Markdown
5. "Hands On" Example [[Rmd](https://github.com/cole-brokamp/geoinformatics_and_population_health_in_R/blob/master/hands_on/hands_on.Rmd) / [html](https://rawgit.com/cole-brokamp/geoinformatics_and_population_health_in_R/master/hands_on/hands_on.html)]
	- Ecological Association of Material Deprivation and Pediatric Hospital Utilization
6. (Time Permitting)
	- Open discussion and questions
	- `crosstalk`
	- `shiny`
	- GRAPPH, DeGAUSS







