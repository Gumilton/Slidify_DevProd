---
title       : Introduction to Shiny App for Linear Regression
subtitle    : Linear Regression and Prediction
author      : XG
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [bootstrap, quiz, shiny, interactive]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Introduction

1. Linear Regression has been an important tool for data statistical summary.
2. Simple softwares are needed for simple regression and prediction purpose.
3. We design an app to take in 5 pairs of data and predict on new data.

--- .class #id 

## Principle

The linear regression works on the two dimensional data with the assumption that a predictor x and responder y follow y= a + b*x + e where e is the error.
For example, we have the following data set:


```
##   X Y
## 1 1 2
## 2 2 3
## 3 3 4
## 4 4 5
## 5 5 6
```

A linear regression will generate that:
Y = ``1`` + ``1`` * X

to predict a new Y based on a new X with the assumption that Y and X follows the rule above.

---

## Analysis on Result

1. Input five pairs of training data.
2. Input the new X data value.
3. The software will calculate the corresponding Y value based on the X value.
4. (Optional) The performace date can be modified by entering current date.


Linear regression figure will be retained in the result for reference. In the figure, black dots and blue lines represent the five pairs of training data and the linear regression fitted. The red dot indicates the location of new predicted data.

---

## Summary and Contact

We appreciate feedback and debug suggestion.
Please contact xg@xg.com

