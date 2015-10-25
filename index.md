---
title       : Diamonds in Singapore
subtitle    : Pricing the C's of Diamond stones
author      : Satya Sreenivasan
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---



## Purpose of this Presentation
This is a Pitch Presentation for the 'Developing Data Products' Coursera class. The purpose of the project is to demonstrate ability to create an interactive app using the 'shiny' package and then use either 'slidify' or 'RStudio Presenter' to create a slidedeck for the pitch presentation. I have chosen to create my slidedeck using 'slidify'.

---

## About the Application
After looking around several days for meaningful datasets to be used for this project, I decided to use the 'Diamond' dataset that is found in the Ecdat package. Since the dataset is from Singapore where I live, and diamonds are a girl's best friend, I decided to proceed with this data.

The source for the dataset is:  Chu, Singfat (2001), Pricing the C's of Diamond Stones, Journal of Statistics Education Volume 9, Number 2 (2001), http://www.amstat.org/publications/jse/v9n2/datasets.chu.html.

---

## About the data
The price of diamond jewelry depends on the four C's: caratage, cut, colour, and clarity of the diamond stone. A good cut gives a diamond more sparkle. Colourless diamonds are the most prized. A flawless diamond has maximum clarity because the passage of light is unimpeded through the stone.

This dataset contains information on {308} diamond stones - their price and 4 other attributes namely: 

```
## 'data.frame':	308 obs. of  5 variables:
##  $ carat        : num  0.3 0.3 0.3 0.3 0.31 0.31 0.31 0.31 0.31 0.31 ...
##  $ colour       : Factor w/ 6 levels "D","E","F","G",..: 1 2 4 4 1 2 3 4 5 6 ...
##  $ clarity      : Factor w/ 5 levels "IF","VS1","VS2",..: 3 2 4 2 2 2 2 5 3 2 ...
##  $ certification: Factor w/ 3 levels "GIA","HRD","IGI": 1 1 1 1 1 1 1 1 1 1 ...
##  $ price        : int  1302 1510 1510 1260 1641 1555 1427 1427 1126 1126 ...
```

---

## Utility of the Application
By playing around with the attributes for X and Y axes and the color, one can infer the relative worth of the different grades of colour and clarity and whether differences in prices can be attributed to the 3 different certification bodies. Hopefully, this is of interest to students of Statistics/Data Science who are looking to buy a diamond :)
