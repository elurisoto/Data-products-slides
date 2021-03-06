---
title       : An overview on research budget
subtitle    : Developing Data Products project
author      : Eleuterio Risoto
job         : Student
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Introduction

* In these slides we will present the gba_nabste visualization tool developed for the
Coursera Developing Data Products course.

* Gba_nabste is a dataset containing the research budget assigned by different countries.

* Budget is represented as a percentage of the total budget of the country.

* The dataset covers from 1980 to 2013, but for most countries the records start in 1995.

* The countries represented are those belonging to the European Union and some other 
important ones.

* The data can be accessed and downloaded from the [Eurostat website](http://appsso.eurostat.ec.europa.eu/nui/show.do?dataset=gba_nabste).

--- .class #id 

## App utility

* The dataset comes in a strange format and its hard to see how time has affected
the research budget of each country.

* The app is interesting too see how hard the economic crisis has affected to the country.

* Sadly one of the first austerity measures is cutting the research budget, as we will see in the next slide.

* It also allows to see how countries can overspend in periods of economic bonanza.

---

## Usage example

This graph can be generated using our app. It shows Spain's budget compared to the average budget.
We can see the overspending during the real state bubble and the following budget cut. 
We can also see how elections affect budget changes. There were elections in Spain in 2004 and 2008.
These are the two years with the most sudden budget changes.
<iframe src=' assets/fig/unnamed-chunk-1-1.html ' scrolling='no' frameBorder='0' seamless class='rChart morris ' id=iframe- charta425908459 ></iframe> <style>iframe.rChart{ width: 100%; height: 400px;}</style>

---


<br><br><br><br><br><br>
<h2><center>Thank you for your attention and excuse if there was any mistake, 
english is not my first language :)</center></h2>

