# Python Basics {#pythonbasics}



The python engine is based on the reticulate package (Ushey, Allaire, and Tang 2020), which makes it possible to execute all Python code chunks in the same Python session. If you actually want to execute a certain code chunk in a new Python session, you may use the chunk option python.reticulate = FALSE. If you are using a knitr version lower than 1.18, you should update your R packages.

Below is a relatively simple example that shows how you can create/modify variables, and draw graphics in Python code chunks. Values can be passed to or retrieved from the Python session. To pass a value to Python, assign to `py$name`, where `name` is the variable name you want to use in the Python session; to retrieve a value from Python, also use `py$name`.

---
title: "Python code chunks in R Markdown"
date: 2018-02-22
---

## A normal R code chunk


```r
library(reticulate)
x = 42
print(x)
```

```
## [1] 42
```

## Modify an R variable

In the following chunk, the value of `x` on the right hand side
is 42, which was defined in the previous chunk.


```r
x = x + 12
print(x)
```

```
## [1] 54
```

## A Python chunk

This works fine and as expected. 


```python
x = 42 * 2
print(x) 
```

```
## 84
```

The value of `x` in the Python session is 84.
It is not the same `x` as the one in R.

## Modify a Python variable


```python
x = x + 18 
print(x)
```

```
## 102
```

Retrieve the value of `x` from the Python session again:


```r
py$x
```

```
## [1] 102
```

Assign to a variable in the Python session from R:


```r
py$y = 1:5
```

See the value of `y` in the Python session:


```python
print(y)
```

```
## [1, 2, 3, 4, 5]
```

## Python graphics

You can draw plots using the **matplotlib** package in Python.


```python
import matplotlib.pyplot as plt
plt.plot([0, 2, 1, 4])
plt.show()
```

![](pythonbasics_files/figure-latex/unnamed-chunk-9-1.pdf)<!-- --> 

````
```{r}
# a literal code chunk
```
````


```python
x = 'Hello, Python World!'
print(x.split(' '))
```

```
## ['Hello,', 'Python', 'World!']
```

