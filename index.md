---
title       : USA's best hospital browser
subtitle    : Find the best hospital in 3 clicks
author      : WT
job         : Data Analyst
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Agenda  
  
1. Overview
2. How it works
3. Conclusion


--- .class #id 

## Overview

### What is this app about?
This application allow you to search for the best hospital in the USA for 3 diseases:
- Heart Attack
- Heart Failure
- Pneumonia

### Computations
The hospitals are ranked based on the 30-day mortality rate. From lowest to highest.

### Underlying data
The data come from the Hospital Compare web site (http://hospitalcompare.hhs.gov) run by the U.S. Department of Health and Human Services. The purpose of the web site is to provide data and information about the quality of care at over 4,000 Medicare-certified hospitals in the U.S. 

--- .class #id 

## How it works
### Inputs
There are 2 inputs in the left pane: Number of hospitals to be displayed & Disease for which you search the best hospital.  
There are additional search fields that are displayed in the table that allows to refine the search (by hospital name, state or rating).

### Output
Below is a sample of the output for 2 hospitals  for heart attack, run from the R function embedded in the application. (Code is not shown but actually run from the slides!)

```
##           HospitalName STATE Rate
## 1 NYU HOSPITALS CENTER    NY 10.1
## 2  DOYLESTOWN HOSPITAL    PA 10.4
```


--- .class #id 

## Conclusion

### Benefits
This application provides you with the ability to browse in a very easy way the lenthy reports of all the hospitals in the USA.  
Users have thus the ability to select the best hospital for their pathology accross the USA.  
The app require no data analytics skills thanks to its simple yet incredibly powerful interface!

### Cost
This app is provided at no cost for the user and can be accessed by anyone having internet access.


