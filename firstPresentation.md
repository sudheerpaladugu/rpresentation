First R Presentation
===
id: home
author: sdr paladugu
date:   Tue Dec 15 22:43:15 2015
autosize: true

First Slide
===
id: first
transition: linear
left: 70%

<span style="font-size:50px;font-weight:normal;font-family:Times New Roman;color: #00ff00;">
For more details on authoring R presentations please visit - </span>
<https://support.rstudio.com/hc/en-us/articles/200486468>.
- Bullet 1
- Bullet 2
- Bullet 3 

</span>
Slide With Code
===
id: second
transition: concave
incremental: true
font-family: verdana


```r
library(datasets)
summary(cars)
```

```
     speed           dist       
 Min.   : 4.0   Min.   :  2.00  
 1st Qu.:12.0   1st Qu.: 26.00  
 Median :15.0   Median : 36.00  
 Mean   :15.4   Mean   : 42.98  
 3rd Qu.:19.0   3rd Qu.: 56.00  
 Max.   :25.0   Max.   :120.00  
```
testing square $x^2$

[Go to slide 1](#/first)

Slide With Plot
===
id: third
transition: zoom

![plot of chunk unnamed-chunk-2](firstPresentation-figure/unnamed-chunk-2-1.png) 
  
First column
***
Second column


qplot Slide
===
## A Simple Plot ##

Let us create a simple scatterplot.


```r
require(ggplot2)
qplot(wt, mpg, data = mtcars)
```

<img src="firstPresentation-figure/simple-plot-1.png" title="plot of chunk simple-plot" alt="plot of chunk simple-plot" style="display: block; margin: auto;" />

