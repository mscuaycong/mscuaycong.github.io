---
title       : Analyze and Plot 2 Years of Monthly Numeric Data
subtitle    : Developing Data Products Assignment
author      : M. Cuaycong
job         : 
framework   : io2012     # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft,selfcontained }
knit        : slidify::knit2slides
--- 

## Overview

### This application will automate the usual comparative analysis we often find ourselves doing.

* Takes 2 years of monthly data
* User can select a file to upload
* User selects a month to summarize
* Compares year over year change for the same year-to-date period
* Compares year 2 month versus year month 1


---

##  The App

<div style='text-align: center;'>
     <img height='560' src='http://mscuaycong.github.io/figure/App.PNG' />
          </div>


--- .class #id1 

## The Data

The file will be read into a data frame and will have 3 columns and 12 monthly observations.  The first column will need to have month abbreviated values.



|month | year1| year2|
|:-----|-----:|-----:|
|jan   |    10|    12|
|feb   |    20|    24|
|mar   |    30|    36|
|apr   |    40|    48|
|may   |    50|    60|
|jun   |    60|    72|
|jul   |    70|    84|
|aug   |    80|    96|
|sep   |    90|   108|
|oct   |   100|   120|
|nov   |   110|   132|
|dec   |   120|   144|



---

## Plot the Data
#### User has 2 standard plots, one of which is a 2-line plot.


![plot of chunk unnamed-chunk-2](assets/fig/unnamed-chunk-2-1.png)


---

## Summarize the Data

The monthly data is summarized, using the month selected by the user.


|Period |Year1 |Year2 |%Chg-YoY |
|:------|:-----|:-----|:--------|
|dec    |120   |144   |20       |
|YTD    |780   |936   |20       |


---.class1 #id1 bg:lightblue

## That's It

> Try the app...[Click Here](https://mscuaycong.shinyapps.io/DDPAssign/)



<div style='text-align: center;'>

<font size="10">THANKS for your time.</font>

  </div>



