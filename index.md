---
title       : Temperature Converter
subtitle    : DS9 Slidify Project
author      : vmalino
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Application Description

The R application created to test basic features of the Shiny package.

The application allows to select one of the temparature scales (Fahrenhiet or Celsius), to enter temperature value, and to get the result of the converion to another scale.

The temperature value input is possible in two ways: slider and textbox. The slider has range (-50, 50) degree Celsius and respective values Fahreheit (-58, 122).

As the output the application provides Temperature Scale and Value.

---

## Formulas Used

Two opposite formulas used in the application for temperature conversion.

From Fahrenheit to Celsius:

$\frac{x - 32}{1.8}$

From Celsius to Fahrenheit:

$1.8 x + 32$

---

## Demo Calculations

For example, conversion from Fahrenheit to Celsius can look like this:

```r
tF <- 60
(tF - 32) / 1.8
```

```
## [1] 15.55556
```

The opposite, from Celsius to Fahrenheit:

```r
tC <- 30
tC * 1.8 + 32
```

```
## [1] 86
```

---

## Summary

* The application helps to demonstrate basic features of the Slidify package.

* The application implements simple temperature converter. 

* The slider with fixed range helps to vizualize the difference between two temperature scales.


