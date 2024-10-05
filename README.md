This package constitutes an interactive R problem set based on the RTutor package (https://github.com/skranz/RTutor). 

Here you will use R code and interactive tasks to examine the effects on tastes and mortality of an anti-alcohol campaign in the Soviet Union and another import shock, specifically related to beer, after the fall of the Soviet Union. Together we will read in data, transform it, and then output and interpret it. There will be quizzes and lines of code to fill in.

This problem set is based on the paper "The Long-Run Effects of a Public Policy on Alcohol Tastes and Mortality" by Kueng, L., & Yakovlev, E. (2021).

The paper, online appendix, and data are available at the following websites:

- **Paper**: https://www.aeaweb.org/articles?id=10.1257/pol.20180439

- **Online-Appendix**: https://lorenzkueng.droppages.com/LongRunEffects_KY_OnlineAppendix.pdf

- **Data**: https://doi.org/10.3886/E117443V1

## 1. Installation

RTutor and this package is hosted on Github. To install everything, run the following code in your R console.
```s
install.packages("RTutor",repos = c("https://skranz-repo.github.io/drat/",getOption("repos")))

if (!require(devtools))
  install.packages("devtools")

devtools::install_github("MichaelKireev/RTutorAlcoholTastesMortality")
```

## 2. Show and work on the problem set
To start the problem set first create a working directory in which files like the data sets and your solution will be stored. Then adapt and run the following code.
```s
library(RTutorAlcoholTastesMortality)

# Adapt your working directory to an existing folder
setwd("C:/problemsets/RTutorAlcoholTastesMortality")
# Adapt your user name
run.ps(user.name="Jon Doe", package="RTutorAlcoholTastesMortality",
       auto.save.code=TRUE, clear.user=FALSE)
```
If everything works fine, a browser window should open, in which you can start exploring the problem set.
