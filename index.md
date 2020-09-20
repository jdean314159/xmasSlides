--- 
title       : "Days 'til Christmas"
subtitle    : "Yes, we need a little Christmas, right this very moment..."
author      : "Jeff Dean"
job         : 
framework   : revealjs        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : default      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
--- 

## How Many Days Until Christmas?

#### The year of 2020 has been a _little_ hard on most of us.

#### As we get closer to the end of the year, we **need** to be reminded that better days are coming.

#### Are you ready for _Christmas_?


---  .class #id0 bg:red

## Let Me Count the Days

#### With our tool, we can automatically determine the number of days from a given date to the next Christmas

#### This can be used to figure out how much time you have to get presents

###### This is especially important because Amazon has a backlog on a number of products!

--- .class #id1 bg:green

## The Magic Behind The Algorithm

#### No magic involved (although this is about Christmas)

#### All you have to do is enter a date, say, today's date!

###### R code



```r
thisDate <- today()
Year <- year(thisDate)
```
##### Today is 2020-09-20 

#### Then we figure out the year, and add it to a year-month-day string for Christmas

##### i.e. 2020-12-25.
#### We subtract the date entered from Christmas day for that year, and voila!

--- .class #id2 bg:green

## Why?

#### As we said, 2020 has been a rough year.

##### Politics, COVID-19, wildfires, the economy, ...

#### We just thought you needed a reminder of the coming holiday season

---- .class #id3

## Don't forget the holiday wine!

![wreath](./assets/img/center.jpg)

