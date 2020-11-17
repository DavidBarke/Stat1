# Discrete Random Variables and Distributions



## Prerequisites {-}


```r
library(ggplot2)
library(dplyr)
library(knitr)

# Set ggplot2 theme
theme_set(theme_bw())
```

## Exercise G1

### The pigsty

A farmer owns a pigsty with 10 compartments, in each of which 2 pigs stand. There is a suspicion that some pigs are infected with a certain, but not communicable disease, which can be detected by a blood test.
The veterinarian suggests that a blood test be performed on each pig for a fee of 10 EUR per pig. However, the total fee of 200 EUR resulting from this proposal seems far too high for the farmer. Therefore, the farmer in turn suggests that the doctor mixes the blood taken from the animals in one compartment and analyzes this mixture for 10 EUR. Only if the results are positive should the doctor perform a single test on each pig in the compartment concerned. Whether the farmer's method is advantageous (i.e. costs less than 200 EUR) depends on the probability $\pi$ of a pig being infected with the disease.

#### First of all, think intuitively for which values of $\pi$ (rather small or rather large) the method proposed by the farmer is more cost-effective.

#### Now decide mathematically for which values of $\pi$ the method suggested by the farmer is cheaper than the method suggested by the doctor by comparing the expected value of the doctor's fee (if suggested by the farmer) with the fixed amount of the doctor's fee (if suggested by the doctor).

Suppose you were not an economist or business economist, but a farmer and had this problem to solve. Surely you would then have made a proposal to the veterinarian that was a bit more favourable and also more advantageous to you for a higher probability of illness $\pi$ than the method suggested by the veterinarian. Modify the farmer's method described above accordingly.

#### For what values of $\pi$ is your modified method now cheaper than the method suggested by the veterinarian? Justify your proposal with the help of a formal calculation.

## Exercise G2

### Lottery

A lottery ticket seller sells ( infinitely many ) lots with the equally distributed numbers 0 to 9. 

The following payment plan applies:

* If the digits 0, 6 or 9 appear, nothing is paid out.
* If an even number (except 0 or 6) appears, 4.50 EUR is paid out.
* If an odd number appears (except 9), 3 EUR will be paid.

#### Calculate the expected value of the payout amount per draw.

#### With what probability does a lot buyer receive a payout of exactly 3 EUR when buying 3 lots?

#### With what probability does a lot buyer receive a payout of at least 4 EUR when buying 3 lots?

The lot seller has set the lot price so that his daily profit has an expected value of 450 EUR for 1,000 lots sold.

#### How high is this lot price?

## Exercise G3

### Aircraft engine

Each aircraft engine fails during a flight independently from the other engines with a probability of $\pi$. 

Be
* $X$ : "Number of functioning engines of a twin-engined aircraft.
* $Y$ : "Number of functioning engines of a three-engined aircraft.
* $Z$ : "Number of functioning engines of a four-engined aircraft."

#### Determine the probability function of X in a table.

#### Determine the probability function of Y in a table.

#### Determine the probability function of Z in a table.

### Part A

An aircraft can stay in the air (and land safely) if at least **two-thirds** of the engines are working. Are aircraft with two, three or four engines more reliable, i.e. for which type of aircraft, the probability of a crash is lowest if for the probability of failure of an engine applies:

#### $\pi = 0.7$

#### $\pi = 0.2$

#### $\pi = 0.01$

### Part B

An aircraft can stay in the air (and land safely) if at least **half** of the engines are working. Are aircraft with two, three or four engines more reliable, i.e. for which type of aircraft, the probability of a crash is lowest if for the probability of failure of an engine applies:

#### $\pi = 0.7$

#### $\pi = 0.2$

#### $\pi = 0.01$

## Exercise G4

### Mini-Roulette

Mini roulette is played in a casino in a small spa town. This roulette is divided into four equal sectors. The ball can only fall into one of these sectors during one pass. In each sector one of the numbers "-2", "-1", "+1" and "+2" is printed. The following rules apply:

* If the ball falls into the sector "+1" or "+2", the result is fixed, you will be paid the corresponding amount in EUR by the bank and the game is over.
* If the ball falls in the sector "-2" or "-1", the roulette is started again. The results of both passes are added together and form the result:
  + If the result is positive, the bank will pay you this amount in EUR and the game is finished.
  + If the result is negative, you must pay this amount to the bank in EUR and the game is finished.
  + If the result is zero, you have neither profit nor loss and the game ends in a draw.

#### Determine the probability function of the random variable $X$: "Earnings per game in EUR" in table form:

#### Is this game "fair"?

#### Calculate $Var(X)$.

## Exercise G5

### Card game

A deck of 4 cards (Ace of Spades, Ace of Hearts, Queen of Clubs and Jack of Diamonds) is shuffled and dealt face down to two players, so that each player receives two cards.

#### Note the 6 card dealings that a player can receive.

Suppose one of the two players announces: "I have an ace".

#### What is the probability that this player also holds the second ace in his hand?

Suppose one of the two players announces: "I have an Ace of Spades. 

#### What is the probability that this player will also hold the second ace in his hand?

#### Determine the expected number of aces that a player will receive when the cards are dealt.

## Exercise G6

### One will win

If two candidates are equal on points in the "One will win" show, the winner is determined by throwing the dice, i.e. there is a dice round in which each candidate rolls an ideal dice once. The one of them who rolls the higher number is declared the winner. If both roll the same number, another dice round takes place until the winner is determined.

Determine the probability that until the decision is made

1. exactly 4
2. at least 4
3. at most 4

dice rounds are necessary.

## Exercise G7

### Coin toss

The two statistics students Otto and Paul came up with the following random experiment:

An ideal coin ("heads" or "tails") is tossed three times in a row.

* Game A : You win as much EUR as the number thrown in this experiment.
* Game B : Only the result of the first toss is taken into account.
  + If the 1st roll shows "heads", you win 3 EUR.
  + If the 1st roll of the dice shows "tails", you have neither a win nor a loss.

Be $X$: "Winnings of game A" and $Y$: "Winnings of game B".

#### Enter the probability function of the random variable X.

#### Enter the probability function of the random variable Y.

#### Paul chooses game A and Otto chooses game B.

#### Calculate the expected value and the variance of Paul's win.

#### Calculate the expected value and the variance of Otto's win.

#### Which game would you choose?

#### Determine the probability function of the random variable $X \cdot Y$ and calculate $E(X \cdot Y)$.

#### Calculate $Cov(X, Y)$
.
#### Determine the probability function of the random variable $Z$ : "Joint profit of Otto and Paul"

#### Calculate the expected value and the variance of the joint profit of Otto and Paul.

#### Are $X$ and $Y$ stochastically independent?

## Exercise G8

### Environmentalists

A group of environmentalists goes out to sea and collects floating barrels of poison. 

Let $X$ be : "Number of barrels found on the first day in a region" with


|  x| P(X = x)|
|--:|--------:|
|  3|     0.25|
|  4|     0.50|
|  5|     0.25|

#### What is the probability that environmentalists will find at least four barrels in a new region on the first day?

#### On average, how many barrels will be found in a new region on the first day?

#### Calculate the variance of $X$.

If the environmentalists go to the same region a second day, the chances of finding barrels change. Let $Y$ be : "Number of barrels found on the second day in the same region" with the following conditional probabilities:

$$P(Y = 0 | X = 3) = \frac{1}{2} \, , \quad P(Y = 0 | X = 4) = \frac{1}{2} \, , \quad P(Y = 0 | X = 5) = \frac{3}{4}$$
$$P(Y = 1 | X = 3) = \frac{1}{4} \, , \quad P(Y = 1 | X = 4) = \frac{1}{2} \, , \quad P(Y = 1 | X = 5) = \frac{1}{4}$$
$$P(Y = 2 | X = 3) = \frac{1}{4} \, , \quad P(Y = 2 | X = 4) = 0 \, , \quad P(Y = 2 | X = 5) = 0$$

#### Determine the common probability function of $X$ and $Y$ in a table.

#### Calculate the covariance of $X$ and $Y$.

#### Are $X$ and $Y$ stochastically independent?

The environmentalists receive a kind of "find reward" for the barrels found. An unknown donor pays them 5 EUR for each barrel found. In addition, each trip is rewarded with 10 EUR.

#### Which proceeds in EUR can the environmentalists expect if they go to sea in a new region once on the first day and once on the second day?

## Exercise G9

### Two-dimensional random variable

The two-dimensional random variable ($X, Y$) has the following distribution (probability function):


|  x|  y| P(X = x, Y = y)|
|--:|--:|---------------:|
|  1|  1|             0.1|
|  2|  1|             0.1|
|  1|  2|             0.3|
|  2|  2|             0.1|
|  1|  3|             0.2|
|  2|  3|             0.2|

#### Determine the expected value and the variance of $X$ and $Y$ .

#### Determine the expected value and the variance and the distribution of the sum $X + Y$ .

#### Determine the expected value and the variance and the distribution of the product $X \cdot Y$ .

#### Determine $Cov(X, Y)$

#### Interpret $Cov(X, Y)$

## Exercise G10

### Candles

Candles of a certain type are offered in a store as single and double packs. The number of single packs sold per day ($X$) and the number of double packs sold per day ($Y$) are independent random variables with the following probability distributions:


|  x| P(X = x)|
|--:|--------:|
|  0|      0.1|
|  1|      0.4|
|  2|      0.3|
|  3|      0.2|



|  y| P(Y = y)|
|--:|--------:|
|  0|      0.4|
|  1|      0.3|
|  2|      0.3|

#### Determine the expected value and the variance of $X$ and $Y$.

Define $Z$: "Number of candles sold per day".

#### Determine the expected value and the variance of $Z$.

#### Determine the probability distribution of $Z$.

## Exercise G11

### Self-employment

After the unsuccessful attempt to obtain the intermediate diploma in statistics, student Emil becomes self-employed. He wants to build a secure existence as a gambler. He is offered the following two games:

* Game 1 : Two ideal dice are thrown. The product of the above numbers is paid in EUR.
* Game 2 : Two ideal dice are thrown. The eightfold sum of the above numbers is paid in EUR.

Be

* $Z_1$: "Payout at game 1"
* $Z_2$: "Payout for game 2
* $G_1$: "Win at game 1"
* $G_2$: "Win at game 2

#### What stake in EUR does Emil have to pay in Game 1 to make this game "fair"?

#### What stake in EUR does Emil have to pay in game 2 to make this game "fair"?

Emil finds out that $E(Z_1^2) = 230$ and $E(Z_2^2) = 3.509$.

#### What is the standard deviation of the win in game 1?

#### What is the standard deviation of the win in game 2?

## Exercise G12

### Free tokens

The following game of chance is considered: An ideal dice is thrown once. The player can place **free** tokens on the events:

$$A = \{1, 3, 5 \} \, , \quad B = \{5, 6\} \, , \quad C = \{ 6 \} \, .$$

The following payouts apply:



If you bet on the wrong token you will receive a payout of 0 EUR.

Let $X_A$, $X_B$ and $X_C$ be the payouts a player receives when he has bet on the corresponding marker.

#### Specify the probability functions of $X_A$, $X_B$ and $X_C$ in table form and calculate the expected value and the variance respectively.

#### Determine the common probability function of $(X_A, X_B)$, $(X_A, X_C)$ and $(X_B, X_C)$.

#### Which of these pairs of variables are stochastically independent?

#### Which of these pairs of variables are correlated?

#### Explain the signs of the respective covariance by content.

#### Player 1 sets 3 marks each on A, B and C. How large are the expected value and variance of the payout?

#### Player 2 sets 1 marker on A, 6 markers on B and 2 markers on C. What is the expected value and variance of the payout?

#### Player 3 wants to place his 9 tokens so that the expected payout is 6.50 EUR and the variance is minimal. How should he place the tokens?

## Exercise G13

### Bridge

At a round table there are four chairs for a bridge game in which four people participate. Two women wearing skirts and two men wearing tuxedos take part in the bridge game.

* Be $X$: "Number of male neighbors of a considered bridge player"
* Be $Y$ : "Number of skirts worn by a considered bridge player

#### Determine the probability function of $X$ in a table.

#### Determine the probability function of $Y$ in a table.

#### Determine the common probability function of $X$ and $Y$ in the table.

#### Calculate $Cov(X, Y)$.

## G14

### End of the soccer season

The soccer season is coming to an end. 1. FC Berlin still has two games to play, first a home game and finally an away game. In each game there are two points for a win, one point for a draw and no point for a defeat.

The coach oracles:

* In the home game we will get both points with a probability of 50% and one point with a probability of 30%.
* In the away game victory, defeat and draw are equally probable.
* It's actually impossible that we don't get any points at all in the two games or that both games end in a draw.
* If we get both points in the home game, the probability that we get at least one point in the last game is 60%.
* But if we lose the home game, there is a 40% chance that the team will pull itself together and win the away game.

Be:

* $X$ : "Number of points won in the home game"
* $Y$ : "Number of points won in the away game"

#### Determine the common probability function of $X$ and $Y$ in table form.

#### Calculate $E(X + Y)$ and interpret this value in terms of content.

## Exercise G15

### Three balls

In an urn there are three balls numbered 1 to 3. The following random experiment is performed: In the first draw, a ball is randomly selected and its number is determined. Before the second draw, all balls with a larger number are removed from the urn. Then the ball drawn in the first draw is put back into the urn, and a ball is again selected.

Be:

* $X $: "Number of the first ball drawn"
* $Y$: "Number of the second ball drawn".

#### Determine the common probability function of $X$ and $Y$ in table form.

#### Calculate $Cov(X, Y)$.

#### Are $X$ and $Y$ stochastically independent?

Assume that the random experiment described above forms the basis for a game of chance in which the sum of the numbers on the drawn balls is paid out in EUR.

#### What stake in EUR would be required for such a game to be considered "fair"?

## Exercise G16

### Statistics exam

Three students want to be examined by a professor in statistics one after the other. The passing or failing of the examination can be considered as independent for the three students. The probability of passing the exam is 80% for the first examinee and 70% for the second examinee and 60% for the third examinee. 

Be:

* $X$: "Number of successful students among the first two examinees"
* $Y$: "Number of successful students among the last two examinees"

#### Determine in table form the common probability function of the random variables $X$ and $Y$.

#### Are the random variables $X$ and $Y$ stochastically independent?

#### Determine the probability function of the random variable $Z$: "Number of total successful students among all three candidates".

## Exercise G17

The owner of a fruit store has the following problems that you should solve for him: The random variable $X$ is the amount of strawberry baskets demanded daily and has the following probability distribution:


|  x| P(X = x)|
|--:|--------:|
|  1|      0.3|
|  2|      0.4|
|  3|      0.3|

The owner of the fruit store receives the strawberry baskets from the fruit yard daily according to the following random principle:

There are 2 white and 3 green balls in an urn. He draws 3 balls at random (and without putting them back) from this urn. If 2 of the drawn balls are green, he orders 2 strawberry baskets, in all other cases he orders 3 strawberry baskets.

The quantity of strawberry baskets requested is independent of the quantity offered (=order quantity).

#### Determine the probability function for the quantity $Y$ and calculate $E(Y)$ and $Var(Y)$.

#### Determine the probability function of the random variable $Z = Y - X$ and interpret the possible realizations of $Z$

#### Calculate $E(Z)$ and interpret this value.

#### Calculate $Var(Z)$.

#### Table the common probability function of $X$ and $Y$.

#### Determine the covariance $Cov(X, Y)$.

#### Determine the conditional probability function of $X$, if $y = 3$.

If the demand cannot be satisfied, it may cost the owner 1 EUR per basket (image loss). However, if strawberry baskets cannot be sold, it may cost the owner 2 EUR per basket.

#### What are the expected costs?
