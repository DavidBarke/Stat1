# Multivariate Analysis



## Prerequisites {-}


```r
library(ggplot2)
library(dplyr)
library(knitr)

# Set ggplot2 theme
theme_set(theme_bw())
```

## Exercise D1

In a survey, 200 father-son pairs were asked about their voting behavior in the last election. Create a contingency table using the following information:

1. The sons chose parties $A$, $B$ and $C$ in the ratio $2:1:2$.
2. Half of the fathers who voted for Party $B$ must face the fact that their sons prefer Party $A$.
3. 5% of the sons interviewed - like their fathers - chose party A.
4. Party B won 40% of all votes.
5. 15% of all fathers gave their vote to Party C.
6. 20 sons whose fathers voted for Party A chose Party B.
7. Only 30 fathers voted for the same party as their sons.

## Exercise D2

In the context of developing a marketing strategy for their latest product, the marketing department of a company conducted a survey in the hope of obtaining information about the most promising packaging color. For this purpose, a total of 600 units of the product were offered on three different test markets. Several employees have so far collected the following information about the pieces sold in the test markets:

1. The number of units sold on test market I was in line with the packaging color (black, red, white) in the ratio 1:3:1.
2. 30% of the pieces sold on the Test Market II were packed in black.
3. 25% of all offered pieces were not sold.
4. As many black-packaged pieces were sold as white-packaged pieces.
5. 175 pieces were sold on Test Market III.
6. The number of pieces sold on Test Market II represented 75% of the total number of red wrapped pieces sold on all Test Markets.
7. On Test Market I, 50 fewer pieces were sold than on Test Market III.
8. 35% of the red wrapped pieces sold were sold on Test Market III.

### Present the data obtained from the examination in tabular form in a contingency table.

### Determine the sales shares of the individual packaging colors in the various test markets.

### Based on the results obtained in 2), which packaging color is the marketing department likely to choose?

## Exercise D3

A survey was carried out in which the interviewed persons were asked to give information about their love for animals (yes/no). The respondents were divided into three categories (children, teenagers, adults).

The survey produced the following results:
1. Of the 400 children questioned, 80% are fond of animals.
2. 200 adults were interviewed.
3. The number of animal-loving adults was 140 less than the number of animal-loving children.
4. Altogether 80% (=800 persons) were animal-loving.

### What is the number of non-animal-loving adults?

### What percentage of respondents are not adults?

### How large is the proportion of animal-loving teenagers among those surveyed?

### How large is the proportion of teenagers among animal lovers?

### Do children love animals more than adults?

## Exercise D4

An investigation by the public health department in X-City revealed the following findings about infections with the virus Z in risk groups A, B and C:


|group | infected| not infected|
|:-----|--------:|------------:|
|A     |       18|           42|
|B     |        5|           31|
|C     |       17|           37|

The realizations of the feature _Group_ are denoted by $a_i, i \in \{A, B, C\}$, whereas the realizations of the feature _Infected_ are denoted by $b_j \, , j \in \{1, 2\}$.

###  Is the frequency f(a_i|b_j) more interesting for any member of one of these risk groups than the frequency f(b_j|a_i)? Explain.

### Is the infection level for group B the lowest in this investigation?

### Is the statement correct that in group B the fewest non-infected people were found?

### Is it correct to say that the proportion of non-infected people is smallest in group C?

## Exercise D5

### Part A

After intensive research work, the Birnwiese Fruit Growers' Association would like to bring two new apple varieties Grüner Bitterer (G) and Kleiner Saurer (K) to the market. To test their market chances, the association will supply the new varieties together with the two already established varieties Edler Gelber (E) and Rotbaeckchen (R) to three canteen kitchens (a school kitchen S, a mensa M and a company canteen C) in a total quantity of all apple varieties of 200 kg.

1. S receives 10 kg from variety (R).
2. From (E) a total of 70 kg is delivered.
3. A total of 30 kg is delivered by (G).
4. The delivered quantities of S and M together make up the delivered quantity of C.
5. The quantity delivered from (R) to M makes up 10% of the total quantity delivered to C.
6. From (E) twice as much is delivered to S as from (E) to M.
7. C receives four times as much from (E) as M receives from (E).
8. In total, twice as much is delivered to M as from (E) to S.
9. From (G) four times as much is delivered to S as is delivered from (G) to M and C respectively.
10. From (G) half as much is delivered to S as from (R) to C.

#### What are the names of the statistical features examined here and how are they scaled?

#### Display the common frequency distribution of these two characteristics in tabular form.

#### Are the two characteristics independent of each other in terms of the data available? Justify your answer by means of a formal calculation. 

#### Which of the three canteen kitchens gets the smallest share of new apple varieties in relation to the total quantity of apples delivered to them? Justify your answer with the help of a formal calculation.

### Part B

According to the fruit growers' association, hardly any maggots should be present in the two new apple varieties. The canteen chef distrusts these promises and examines half of the apples of the new varieties delivered to him for maggots ($6$ apples $\approx$ 1 kg). He receives the following result:


```r
maggots <- 0:3
rel_frequency <- c(0.2, 0.4, 0.3, 0.1)
tbl <- tibble(maggots = maggots, rel_frequency = rel_frequency)
names(tbl) <- c("Number of maggots per apple", "Relative frequency")

kable(tbl)
```



| Number of maggots per apple| Relative frequency|
|---------------------------:|------------------:|
|                           0|                0.2|
|                           1|                0.4|
|                           2|                0.3|
|                           3|                0.1|

#### What is the name of the statistical feature examined here and how is it scaled?

#### Determine the absolute frequencies as well as the absolute and relative cumulative frequencies of the statistical feature in a table.

#### Display the relative distribution function.

#### Determine **graphically** the values of a so-called _5 number summary_ and draw the corresponding box-plot.

## Exercise D6

### Part A

The standard of cleanliness in youth hostels often leaves a lot to be desired. A group of statistics students would therefore like to conduct a study in four different regions (A, B, C and D) of the country to get an idea of the standard of cleanliness (good, moderate, poor) of some of the youth hostels located there. A total of 40 youth hostels were inspected with the following results:

1. In region D there are 2 hostels of moderate standard.
2. A total of 14 hostels in Region C and 6 hostels in Region A were checked.
3. In 12 hostels checked, the standard is moderate.
4. In Region C, 8 hostels have a good standard.
5. In Region C, there are twice as many hostels with a moderate standard as those with a poor standard.
6. The hostels in Region C with a poor standard make up 10% of the hostels with a good standard of all regions.
7. In Region A, there are four times as many hostels of moderate standard as there are hostels of good or bad standard in each region.
8. The number of moderate-standard hostels in Region A is half the number of good-standard hostels in Region D.
9. There are four times as many hostels of moderate standard in all regions together as there are hostels of poor standard in Region B.

#### What are the names of the statistical features examined here and how are they scaled?

#### Display the common frequency distribution of these two characteristics in tabular form.

#### Are the two characteristics independent of each other in terms of the data available? Justify your answer by means of a formal calculation.

#### In which region is the cleanliness (of hostels with at least moderate standard) greatest? Justify your answer by means of a formal calculation.

### Part B

After the results of this study were announced, all the managers of those hostels that were certified as having poor standards of cleanliness unanimously assured that a thorough remedy of the deficiencies complained about would be provided as soon as possible. After some time, 20 rooms in each of the affected hostels were checked again for their standard of cleanliness:



#### What is the name of the statistical feature under investigation here and how is it scaled?

#### Determine the absolute frequencies as well as the absolute and relative cumulated frequencies of the statistical feature in a table.

#### Display the (relative) distribution function graphically.

#### Calculate and graphically determine the values of a so-called 5-number summary and draw the corresponding box plot.

## Exercise D7

### Part A

### Part B
