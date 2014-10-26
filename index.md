---
title       : Hello Me
subtitle    : and you
author      : lawrence
job         : coder
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides

---

## Read-And-Delete

1. Edit YAML front matter
2. Write using R Markdown
3. Use an empty line followed by three dashes to separate slides!

--- .class #id 

## Demo

This is case in Example:

```
## [1] 55
```

```
## [1] 55
```

---

## Hello

Hello, I am new in slidify.
Let's we know more in R together

---

## Graph 1


```r
x <- 1:10
plot(x)
```

![plot of chunk simpleplot](assets/fig/simpleplot-1.png) 

---

## Graph 2


```r
x <- 1:10
y <- round(rnorm(10, x, 1), 2)
boxplot(1:10~rep(1:2,5))
```

![plot of chunk multipleplots](assets/fig/multipleplots-1.png) 

```r
plot(x, y)
```

![plot of chunk multipleplots](assets/fig/multipleplots-2.png) 
---
