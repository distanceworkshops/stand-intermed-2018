---
title: Intermediate-level Distance Sampling Workshop
layout: index

---

# Intermediate-level Distance Sampling Workshop

This is the site for the Intermediate-level Distance Sampling Workshop given in St Andrews, 26th to 31st August 2018.

## Course materials

- [Slides](slides.html) in PDF, HTML and R formats
- [Practical session exercises and data](practicals.html)
- [Materials for the R tutorial](R_tutorial.html)
- [Bibliography](bibliography.html) listing additional useful publications

## Course description

The first day of the workshop will review fundamental principles of distance sampling, analyses involving conventional distance sampling and survey design. Subsequently, attention will turn to simulation of distance sampling surveys for design purposes, and to survey and analysis methods for dealing with imperfect detection on the trackline (double-observer methods). Slightly more than two days will be devoted to spatial modelling of distance sampling data. A blend of the latest version Distance 7 and the R computing language will be employed. Throughout the workshop, there will be unstructured time, with instructors working with participants on their specific problems.

## Schedule

| Day       | Purpose                                                 | 0900-1030                                               | 1045-1215                                                          | 1345-1515                                                          | 1530-1700                          |
|-----------|---------------------------------------------------------|---------------------------------------------------------|--------------------------------------------------------------------|--------------------------------------------------------------------|------------------------------------|
| Sunday    | (Optional) R refresher/tutorial                          |                                                         |                                                                    | Start 1400                                                         | *Practical 1*         |
| Monday    | Detection functions, distance sampling simulation       | Welcome and review of assumptions                       | *Practicals 2 & 3:* Analyse simple simulated and awkward data sets | Distance sampling simulation: automated survey design              | *Practical 4:* Simulation            |
| Tuesday   | Sperm whale data analysis                               | What is a Density Surface Model (DSM)?                                          | Intro to generalized additive models (GAMs)                        | *Practicals 5, 6 & 7:* Process data, fit detection function, fit DSMs | DSM: Model checking            |
| Wednesday | Add covariates, produce predictions                     | DSM: Multiple smooths and model selection                    | *Practical 8:* Multiple term DSMs, model checking and selection |  DSM: Prediction & variance estimation     |  *Practicals 9 & 10:* DSM: Prediction and variance |
| Thursday  | Double platform detection functions and advanced topics |  DSM: Modelling advice and advanced topics                | DSM wrapup | Mark-recapture distance sampling                                   | *Practical 11:* `mrds`                                                 |
| Friday    | Research talks and unstructured time | Research talks: acoustics, spatial capture-recapture, HMMs, other spatial approaches, movement | Special topics                                                     | Open                                                               | Open                               |

## Refresher of distance sampling concepts

To remind you about fundamentals of distance sampling, we have [posted the lecture notes and practicals](Introductory distance sampling workshop.pdf) (without data to complete them) from former introductory distance sampling workshops.  Thumb through these to remind yourself about distance sampling concepts.  Some of these lectures are also [available in video format](http://distancesampling.org/videos.html).

## Software

Participants are encouraged to bring their own laptops to use during the workshop practicals. R and Distance for Windows will be used.

To ensure your computer is setup correctly prior to the workshop please check the instructions below.

### Distance for Windows

Distance can be downloaded from [the distance sampling website](http://distancesampling.org/Distance/). Distance 7.2 was released 29th June 2018, if you already have Distance on your computer please ensure you have the latest version.

### R

The course will use R, RStudio and various R packages to be installed from CRAN. The following steps should setup your computer for the workshop:

1. Install R from [the R website](https://cran.rstudio.com/)
2. Install RStudio from [the RStudio website](http://www.rstudio.com/products/rstudio/download/)
3. Open RStudio and install R packages using the following command (cut and paste into the Editor window and submit):

```{r}
install.packages(c("mrds", "Distance", "dsm", "DSsim", "ggplot2", "rgdal", "knitr",
                   "plyr", "raster", "reshape2", "viridis", "htmltools",
                   "caTools", "bitops", "rmarkdown", "tweedie", "shapefiles"))
```

There may be quite a lot of packages downloaded in this process, including many not listed here because the packages listed depend upon many other packages.

Several participants have noted they are unfamiliar with R and RStudio.  There are three things that can be done to increase your familiarity.

*  For practice with the R language
    - DataCamp's [free R tutorial](https://www.datacamp.com/courses/free-introduction-to-r)
*  Experience using the RStudio interface with R
    - DataCamp's [tutorial working with RStudio](https://www.datacamp.com/courses/working-with-the-rstudio-ide-part-1)
*  Tutorial prior to the distance sampling workshop
    - we will spend Sunday (26th August) working through a tutorial that will be available as part of the workshop practical exercises


### Reporting bugs, suggesting improvements

If during the course you encounter bugs in Distance or the distance sampling R packages, or if you have suggestions for improvements in our software, you can report these using the following Google Form. Please try to include as much information as possible.

**[Bug reports and suggestions](https://docs.google.com/forms/d/14ipIeUiiLegvFWq8nnzkOONdN9j_n4Q4ZeJ1dzWZEfc/)**


### ArcGIS

Participants may be interested in the [MGET toolbox for ArcGIS](http://mgel2011-kvm.env.duke.edu/mget/) for use in data formatting, importing etc. Information on [installing the software can be found here](http://mgel.env.duke.edu/mget/download/), if you already have ArcGIS installed. A [brief tutorial is also available](http://mgel2011-kvm.env.duke.edu/mget/documentation/arcgis-tutorial/) on the MGET website.


