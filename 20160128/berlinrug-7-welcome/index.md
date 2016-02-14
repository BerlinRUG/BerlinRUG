---
title       : 7. Meetup of Berlin R Users Group - "RMarkdown & Packages"
subtitle    : 2016-01-28 @ Hypoport (Berlin, DE)
author      : Konstantin Greger
job         : 
logo        : Rlogo.png
biglogo     : Rlogo.png
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Schedule for today

Time|What's happening
-------|-------
19:00|doors open
19:15|Konstantin Greger ([@kogreger](https://twitter.com/kogreger)): "Welcome and Brief Introduction"
19:20|Jens Hanack ([@hypoport](https://twitter.com/hypoport)): "Welcome to Hypoport"
19:25|Open Mic!
19:30|Dr. Andreas Busjahn (HealthTwiSt GmbH; [@TwinGuyBerlin](https://twitter.com/TwinGuyBerlin)): "RMarkdown and Word"
20:00|Steven Pollack: "R Packages: What, Why and How?"
from ~21:25|socializing & networking
22:00|doors close



--- .class #id 

## Number of group members

![plot of chunk groupStats](assets/fig/groupStats-1.png)

--- .class #id 

## Call for Presenters

time series analysis, own packages, modelling count variables, binary logistic modelling with R, data manipulation with dplyr (with magrittr), data visualization with ggvis, making maps with R, introduction to survival analysis with R, logistic regression modelling with R - beyond binary (multinomial and ordinal logistic regression), shiny dashboard, propensity score matching studies, dplyr, ggvis, possibly some of the work I've done with web scraping, network analysis, information visualization, maps and spatial analysis in R, R in the social sciences, basic introduction to dplyr, data mining in R, ODE based models of phytoplankton growth, overview of glmnet, applications of using R in my job environment, R introductionary course, writing functions in R is actually fairly easy, R + knitr + LaTeX: much stronger than Office Word (claim and proof), *apply is the best thing since sliced bread, why you should write a package - and how, modelling election outcomes, discrete choice modeling, bayesian statistics, quantitative marketing/economics, reproducibility in environmental modelling

Just contact me: [kogreger@gmail.com](mailto:kogreger@gmail.com)

--- .class #id 

## Important Links

Participate in our group survey here: [http://bit.ly/BerlinRUG_Member_Survey](http://bit.ly/BerlinRUG_Member_Survey)

Have a look at our group repository here: [http://kogreger.github.io/BerlinRUG](http://kogreger.github.io/BerlinRUG)

Get the latest news via Twitter: [@BerlinRUG](https://twitter.com/BerlinRUG)

User Group hashtag: [#BerlinRUG](https://twitter.com/hashtag/BerlinRUG?src=hash)

--- .class #id &twocol

## Our group sponsors

*** =left

![plot of chunk leftSponsor](assets/fig/leftSponsor-1.png)

*** =right

![plot of chunk rightSponsor](assets/fig/rightSponsor-1.png)

--- #custbg

##  

<style>
#custbg {
  background-image:url(./assets/img/bilbo.jpg); 
  background-repeat: no-repeat;
  background-position: center center;
  background-size: cover;
}
</style>

<div style="font-size:50%; position:fixed; bottom:10px; left:10px; ">"Bilbo, The Fellowship of the Ring, no. 168" © New Line Productions, Inc.<br>http://www.framecaplib.com/lotrlib/images/fotr/fotr0168.jpg</div>

--- .class #id bg:url(./assets/img/openmic.jpg)

## Open Mic!

<div style="font-size:50%; position:fixed; bottom:10px; left:10px; ">"SennMicrophone" by ChrisEngelsma - Own work. Licensed under CC BY-SA 3.0 via Commons<br>https://commons.wikimedia.org/wiki/File:SennMicrophone.jpg#/media/File:SennMicrophone.jpg</div>

--- .class #id 

## Schedule for today

Time|What's happening
-------|-------
19:00|doors open
19:15|Konstantin Greger ([@kogreger](https://twitter.com/kogreger)): "Welcome and Brief Introduction"
19:20|Jens Hanack ([@hypoport](https://twitter.com/hypoport)): "Welcome to Hypoport"
19:25|Open Mic!
19:30|Dr. Andreas Busjahn (HealthTwiSt GmbH; [@TwinGuyBerlin](https://twitter.com/TwinGuyBerlin)): "RMarkdown and Word"
20:00|Steven Pollack: "R Packages: What, Why and How?"
from ~21:25|socializing & networking
22:00|doors close
