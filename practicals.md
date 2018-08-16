---
title: Practical exercises
layout: index

---

# Practical exercises

Here you can find the exercises for the practical sessions during the course. All content will remain here on the Distance website for future consultation.

## Practicals

Practicals are provided in [RMarkdown](http://rmarkdown.rstudio.com/index.html) (`.Rmd`) format. RMarkdown can be opened in [RStudio](https://www.rstudio.com/) and the file "knitted" into HTML or PDF.

Note that the practicals are designed to be run sequentially, files generated from previous analyses are loaded and used in subsequent analyses.

Number | Practical Description                            | Practical                                                                                 | Solution                                                                                                      |
-------|--------------------------------------------------|-------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------|
1      | R tutorial (see [this page](../R_tutorial.html)  |                                                                                           |                                                                                                               |
2      | Processing sperm whale data                      | [Rmd](practicals/02-process-geodata.Rmd)     [PDF](practicals/02-process-geodata.pdf)     |                                                                                                               |
3      | Fitting detection functions                      | [Rmd](practicals/03-detection-functions.Rmd) [PDF](practicals/03-detection-functions.pdf) | [Rmd](practicals/03-detection-functions-solutions.Rmd) [PDF](practicals/03-detection-functions-solutions.pdf) |
4      | Fitting DSMs                                     | [Rmd](practicals/04-simple-dsms.Rmd)         [PDF](practicals/04-simple-dsms.pdf)         | [Rmd](practicals/04-simple-dsms-solutions.Rmd)         [PDF](practicals/04-simple-dsms-solutions.pdf)         |
5      | Multiple term DSMs, model checking and selection | [Rmd](practicals/05-advanced-dsms.Rmd)       [PDF](practicals/05-advanced-dsms.pdf)       | [Rmd](practicals/05-advanced-dsms-solutions.Rmd)       [PDF](practicals/05-advanced-dsms-solutions.pdf)       |
6      | DSM Prediction                                   | [Rmd](practicals/06-prediction.Rmd)          [PDF](practicals/06-prediction.pdf)          | [Rmd](practicals/06-prediction-solutions.Rmd)          [PDF](practicals/06-prediction-solutions.pdf)          |
7      | DSM Variance                                     | [Rmd](practicals/07-variance.Rmd)            [PDF](practicals/07-variance.pdf)            | [Rmd](practicals/07-variance-solutions.Rmd)            [PDF](practicals/07-variance-solutions.pdf)            |
8      | Mark-recapture distance sampling                 | [Rmd](practicals/08-mrds-in-R.Rmd) [R PDF](practicals/08-mrds-in-R.pdf) [Distance PDF](08-mrds_in_Distance.pdf) | [PDF](practicals/08-mrds_solution.pdf) |
9      | Simulation of distance sampling data             | [Rmd](practicals/04-dssim.Rmd)                     |  |

## Data sets 

Data for the practicals come in a variety of forms for analysis both in R and in Distance 7.



### Data for density surface modelling (Practicals 5-10)

To run the sperm whale analysis you'll need to download the following files, unzip them and store the unzipped folders in the same directory as the `Rmd` files for practicals 5-10 above:

- [Analysis.gdb](practicals/Analysis.gdb.zip)
- [Covariates_for_Study_Area.zip](practicals/Covariates_for_Study_Area.zip)

The Distance 7 project containing these data can be downloaded [from this location](practicals/spermwhale-Dist7.zip)

We'd like to thank Jason Roberts of Duke University for preparing these files in ArcGIS with the [MGET Toolbox](http://mgel2011-kvm.env.duke.edu/mget/).

### Data for simulation (Practical 4)

Download [this zip archive](practicals/prac4-DSsim.zip).  You will find a folder *(Distance simulation exercise)* filled with material useful for the R version of Practical 4, and two archives containing Distance 7 projects *(DSsimExercise and DSsimExerciseSolutions)*.

### Data for double platform analysis (Practical 11)

For R users you just need the `csv` file: [Crabeater seals MRDS](practicals/crabbieMRDS.csv). For Distance users, the project file [can be downloaded here](practicals/CrabbieMRDSExercise.zip).

## Problems

If you run into a problem running any of these examples, please report [an issue on this GitHub repository](https://github.com/distanceworkshops/stand-intermed-2018/issues). Or contact the workshop instructors.


