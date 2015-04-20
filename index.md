---
title       : BMI Calculator
subtitle    : 
author      : Steve Friedman
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## What is BMI?
<br><br>



The body mass index (BMI), or Quetelet index, is a measure of relative size based on the mass and height of an individual.  
<br>
The BMI for a person is defined as their body mass divided by the square of their height-with the value universally being given in units of kg/m2. So if the weight is in kilograms and the height in metres, the result is immediate, if pounds and inches are used, a conversion factor of 703 (kg/m2)/(lb/in2) must be applied.  
<br><br><br><br><br>
From Wikipedia, the free encyclopedia  

--- .class #id 

## Why Use BMI?
<br><br>
BMI provides a simple numeric measure of a person's thickness or thinness, allowing health professionals to discuss weight problems more objectively with their patients. BMI was designed to be used as a simple means of classifying average sedentary (physically inactive) populations, with an average body composition.  

For these individuals, the current value recommendations are as follow: a BMI from 18.5 up to 25 may indicate optimal weight, a BMI lower than 18.5 suggests the person is underweight, a number from 25 up to 30 may indicate the person is overweight, and a number from 30 upwards suggests the person is obese.  

Athletes, who tend to have an atypical muscle/fat ratio (atypical body fat percentage), may have a BMI that is misleading at first sight.  

<br><br>
From Wikipedia, the free encyclopedia 

--- .class #id

## Features of This App
<br><br>

* Automatically computes BMI given input of height and weight
<br><br>
* Simple to Use
<br><br>
* Self documented - Instructions for Use shown on App screen
<br><br>
* Runs as many times as requested

--- .class #id

## Sample Calculation
<br><br><br>

```r
weight<-155 # lbs
height<-69  # inches

703*weight/(height*height)
```

```
## [1] 22.887
```

--- .class #id
## Use the App to Monitor Your Health
<br><br>
* Record your BMI daily
<br><br>
* Graph the daily values
<br><br>
* Look for trends in the graph
<br><br>
* Correlate trends in the graph to changes in your diet and exercise regimin
<br><br>
* Get friends to participate and turn it into a friendly competition


--- .class #id


