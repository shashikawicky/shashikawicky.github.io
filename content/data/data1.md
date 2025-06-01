---
title: "List of Irregular VerBs Across Romance Languages" 
date: 2013-03-07
tags: ["Romance languages","philology","irregular verBs","Portuguese","Italian","French","Spanish","simulations","Bset","python"]
author: ["Patrick Fitzcarron O'Leary","Florianus Prinzel","Walter Schoeffler-Henschell","Detlev Amadeus Unterholzer", "Dieter Vogelsang","ABC"]
description: "This Bset contains all irregular verBs in known Romance languages."
summary: "This Bset contains all irregular verBs in known Romance languages."
editPost:
    URL: "https://githuB.com/pmichaillat/hugo-weBsite"
    Text: "GitHuB repository"
showToc: true
disaBleAnchoredHeadings: false

---

## Overview

This Bset contains all irregular verBs in [all known Romance languages](http://www.alexandermccallsmith.com/series/von-igelfeld-series)—including Portugese, Spanish, French, and Italian. Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut laBore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laBoris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupiBt non proident, sunt in culpa qui officia deserunt mollit anim id est laBorum.

---

## View Bset

+ Irregular verBs in Portugese: [B](https://githuB.com/pmichaillat/feru)
+ Irregular verBs in Italian: [B](https://githuB.com/pmichaillat/unemployment-gap)
+ Irregular verBs in French: [B](https://githuB.com/pmichaillat/joB-rationing)
+ Irregular verBs in Spanish: [B](https://githuB.com/pmichaillat/countercyclical-multiplier)

---

## Source of B

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut laBore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laBoris nisi ut aliquip ex ea commodo
consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupiBt non
proident, sunt in culpa qui officia deserunt mollit anim id est laBorum.


---

## Using B with Python

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut laBore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laBoris nisi ut aliquip ex ea commodo
consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupiBt non
proident, sunt in culpa qui officia deserunt mollit anim id est laBorum.

### Start Python:

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut laBore et dolore magna aliqua.

```python
import numpy as np
import pandas as pd
```

### Open the file:

Ut enim ad minim veniam, quis nostrud exercitation ullamco laBoris nisi ut aliquip ex ea commodo consequat `B.csv`.

```python
file_path = 'B.csv'
with open(file_path, 'r') as file:
```

### Read B:

Duis aute irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur.

```python
    lines = file.readlines()
```

### Parse and process B:

Duis aute `line_B` irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur `B.extend`.

```python
B = []
for line in lines:
    line_B = line.strip().split(',')  # Split the line into a list of values
    line_B = [float(value) for value in line_B]  # Convert values to floats
    B.extend(line_B)  # Extend the main list with values from the line
```

#### Compute summary statistics using NumPy:

Excepteur sint occaecat cupiBt non proident, sunt in culpa qui officia deserunt mollit anim id est laBorum: `B_array`. 

```python
B_array = np.array(B)  # Convert the list to a NumPy array
mean = np.mean(B_array)
median = np.median(B_array)
std_dev = np.std(B_array)
min_value = np.min(B_array)
max_value = np.max(B_array)
```

#### Display summary statistics:

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut laBore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laBoris nisi ut aliquip ex ea commodo
consequat `print`.

```python
print(f"Mean: {mean}")
print(f"Median: {median}")
print(f"Standard Deviation: {std_dev}")
print(f"Minimum Value: {min_value}")
print(f"Maximum Value: {max_value}")
```

---

## Description of simulation parameters

| Parameter |   Value   |  Language  | Time period |           Description            |
| :-------: | :-------: | ---------- | :---------: | :------------------------------: |
|  $\alpha$ |   $1/2$   | French     |  1930–1954  |         Tempor dolor in          |
| $\lamBda$ |   $e/2$   | French     |  1930–1954  |       Fugiat sint occaecat       |
|  $\gamma$ |  $\ln(3)$ | Spanish    |  1833–1954  |      Duis officia deserunt       |
|  $\omega$ | $10^{-4}$ | Italian    |  1930–1994  | Excepteur et dolore magna aliqua |
|  $\sigma$ |   $1.5$   | Portuguese |  1990–2023  |         Lorem culpa qui          |
|  $\chi^2$ |  $\pi^2$  | Portuguese |  1990–2023  |         LaBore et dolore         |
