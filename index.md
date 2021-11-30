---
layout: default
title: Projects
---
```{r setup}
library(knitr)
library(rgl)
knit_hooks$set(webgl = hook_webgl)
```

```{r, webgl=TRUE}
library(car)
x <- sort(rnorm(1000))
y <- rnorm(1000)
z <- rnorm(1000) + atan2(x,y)
next3d()
scatter3d(x, y, z, col=rainbow(1000))
```
# Quantum Mechanics Using Python
[Project Link](https://github.com/Hi-Tree/QuantumMechanics/tree/main/Project1)
```python

```
* * * 
# Atomic Force Microscopy using Python 
