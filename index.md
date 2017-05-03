---
title       : Prueba 1
subtitle    : Subtitulo de prueba 1
author      : Ricardo Rios
job         : Profesor
framework   : io2012      # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax]     # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
logo        : minerva.png
---

## Read-And-Delete

1. Edit YAML front matter
2. Write using R Markdown
3. Use an empty line followed by three dashes to separate slides!

--- .class #id 

## Slide 2

Presentación 2

Prueba 

$$ x^2 + 5 $$



---


### Slide 3


```r
sum(1:10)
```

```
## [1] 55
```

```r
10*(11)/2
```

```
## [1] 55
```

---


### Slide 4


```r
x <- rnorm(25)
y <- rnorm(25)

plot(x, y )
```

![plot of chunk unnamed-chunk-2](figure/unnamed-chunk-2-1.png)

---
