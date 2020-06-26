---
title: "Exchange Rate Volatility"
author: "Rohith Krishna"
date: "26/06/2020"
output:
  html_document:
    keep_md: yes
layout: post
permalink: /exrate
---

### Importing data


```r
library(readxl)
data <- read_excel("inrusd.xlsx")
data$inrVal <- as.numeric(data$inrVal)
```

Summary of data


```r
summary(data)
```

```
##       time                         inrVal     
##  Min.   :2015-06-25 00:00:00   Min.   :63.34  
##  1st Qu.:2016-09-23 18:00:00   1st Qu.:65.36  
##  Median :2017-12-24 12:00:00   Median :67.38  
##  Mean   :2017-12-24 12:00:00   Mean   :68.14  
##  3rd Qu.:2019-03-26 06:00:00   3rd Qu.:70.79  
##  Max.   :2020-06-25 00:00:00   Max.   :76.94
```

