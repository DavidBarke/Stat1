# Correlation Analysis



## Prerequisites {-}


```r
library(ggplot2)
library(dplyr)
library(knitr)

# Set ggplot2 theme
theme_set(theme_bw())
```

## Exercise E1

A group of science students wrote an exam in math and an exam in physics. From 10 randomly selected students the results (in points) are summarized in the following table:


```r
student <- 1:10
maths <- c(14, 8, 10, 20, 12, 8, 12, 20, 16, 20)
physics <- c(10, 12, 12, 8, 12, 10, 10, 12, 16, 8)
tbl <- tibble(student = student, maths = maths, physics = physics)
names(tbl) <- c("Student", "Maths", "Physics")

kable(tbl)
```



| Student| Maths| Physics|
|-------:|-----:|-------:|
|       1|    14|      10|
|       2|     8|      12|
|       3|    10|      12|
|       4|    20|       8|
|       5|    12|      12|
|       6|     8|      10|
|       7|    12|      10|
|       8|    20|      12|
|       9|    16|      16|
|      10|    20|       8|

### Part A

#### Calculate the correlation coefficient according to Bravais-Pearson.

### Part B

#### Calculate the (corrected) rank correlation coefficient according to Kendall.

### Part C

Each exam is considered passed if the candidate has achieved at least 12 points.

#### To measure the correlation between the exam result in physics (passed, failed) and the exam result in mathematics (passed, failed), display the exam result of the 10 students in a contingency table.

#### Determine the $\chi^2$ value.

#### Determine the contingency coefficient $K$.

### Part D

#### Give an explanation for the different values of $r$, $\phi$ and $K$.

## Exercise E2

### Sex education

15 apprentices, who participate in a series of sex education lessons as part of their vocational school education, were asked to mark on a five-point scale (1: unimportant, 5: very important) the importance they felt sex education in general should have. In addition, the interviewed apprentices were asked to mark on a three-point scale (1: not at all, 3: a lot) the extent to which the sex education book used in class could contribute to a reasonable sex education. The result is recorded in the following frequency table (rating of important from left to right, rating of book from top to bottom):


|   |   |   |   |   |
|:--|:--|:--|:--|:--|
|-  |4  |1  |-  |-  |
|-  |-  |5  |1  |-  |
|2  |-  |1  |-  |1  |

#### To indicate the extent to which the two ratings are correlated, calculate the rank correlation coefficient according to Kendall.

## Exercise E3

### Part A

The characteristics of written and oral grades in economics were assessed in 9 exam candidates, with only whole grades from 1.0 to 5.0 being awarded. The result of the survey is shown in the following matrix:


|   |   |   |   |   |
|:--|:--|:--|:--|:--|
|1  |-  |-  |-  |-  |
|1  |1  |1  |-  |-  |
|1  |-  |-  |1  |1  |
|-  |-  |-  |1  |-  |
|-  |-  |-  |1  |-  |

#### Calculate a suitable coefficient as a measure of the strength of the relationship between the two characteristics.

### Part B

The characteristics preparation time [in weeks] and number of exams taken were recorded for 10 exam candidates. The result of the survey is shown in the following matrix:


|   |   |   |   |   |
|:--|:--|:--|:--|:--|
|-  |-  |-  |1  |1  |
|2  |1  |-  |-  |-  |
|-  |-  |-  |-  |-  |
|2  |1  |-  |-  |-  |
|-  |-  |-  |1  |1  |

#### Calculate a suitable coefficient as a measure of the strength of the relationship between the two characteristics.

## Exercise E4

At the University A, those responsible for Statistics I and II exams are interested in using a coefficient to estimate how strong the formal relationship between the two exam results (measured in points) is. For this purpose, 5 students are randomly selected from the total number of students who have written these exams. In the following table their compiled point values are listed:


| Student| Statistics 1| Statistics 2|
|-------:|------------:|------------:|
|       1|           20|           70|
|       2|           30|           40|
|       3|           50|           10|
|       4|           70|           40|
|       5|           80|           70|

### Part A

#### Draw the data into a scatterplot.

#### Calculate the appropriate coefficient for this problem.

#### Interpret the result.

#### What does this coefficient measure and what does it not measure.

### Part B

Assign ranks to the (cardinal) data.

#### Calculate the adequate coefficient.

#### Interpret the result.

## Exercise E5

### Work performance

A psychologist investigates different work groups in a company to see if there is a connection between the attractiveness of a work group (cohesion and well-being of its members) and the variance of its work performance.

Group attractiveness was measured using an ordinal scale from 1 = very high to 6 = very low. The variance in performance refers to the number of products completed by a work group on different days. The study produced the following result: 


|Work Group | Attractiveness| Variance in Performance|
|:----------|--------------:|-----------------------:|
|A          |              1|                      32|
|B          |              2|                      20|
|C          |              2|                      40|
|D          |              3|                      32|
|E          |              4|                      64|
|F          |              5|                      68|
|G          |              6|                      60|

#### What are the statistical features in this study?

#### Calculate a suitable correlation coefficient.

#### Interpret the calculated sign of this coefficient.

#### Does the calculated value of this coefficient provide information about a cause-and-effect relationship between the two characteristics examined?
