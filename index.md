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


---

##  The App

<div style='text-align: center;'>
    <img height='560' src='figure/App.png' />
</div>

--- .class #id1 

## The Data

> User uploads a csv data file with headers, that looks like this.  The file will be read into a data frame and will have 3 columns and 12 monthly observations.  The first column will need to have month abbreviated values.


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


|Period |Year1 |Year2 |%Chg-YoY |
|:------|:-----|:-----|:--------|
|dec    |120   |144   |20       |
|YTD    |780   |936   |20       |


---.class1 #id1 bg:lightblue

## That's It

> Try the app...[Click Here](https://mscuaycong.shinyapps.io/DDPAssign/)



# **THANKS for your time.**

