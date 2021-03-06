# Combinatorics and Algebra of Events



## Prerequisites {-}


```r
library(ggplot2)
library(dplyr)
library(knitr)

# Set ggplot2 theme
theme_set(theme_bw())
```

## Exercise F1

### Part A

Three doctors work in the emergency room of a hospital: N, O and P. Since the division of weekend services (Saturday and Sunday) is very difficult, the three doctors decide to conduct a random experiment to determine the division. Three slips of paper with the first letters of their names (N, O and P) are placed in an urn. Two pieces of paper are then drawn at random from the urn to make the division.

Specify the possible outputs (2-tuples) of this random experiment, if

#### with the allocation you want to determine on which day a doctor is on duty (first element of the 2-tuple stands for Saturday), and it should be possible for a doctor to be on duty (i.e. double duty) on both days.

#### double duty is possible, but it should not be determined on which day a doctor is on duty.

#### double duty is not possible, but it should be determined on which day a doctor is on duty.

#### double duty is not possible and it should not be determined on which day a doctor is on duty.

## Exercise F2

### Part A

At the beginning of the semester, a group of students would like to offer a 5-day orientation tour of the university for first-year students. There are 5 volunteer members available.

#### How many different ways are there to give each member a weekday (Monday to Friday)?

Since Klaus has fallen ill, Karl will lead a tour twice.

#### How many different options are there for scheduling the tours by name?

Karl suddenly insists that he does not want to lead a tour on two consecutive days.

#### How many different options are there for scheduling the tours by name now?

### Part B

In two urns there are 6 different colored balls in each of the two urns, whereby the color composition of the balls in both urns is the same. Two balls are drawn at random from each urn without putting them back.

How many possibilities are there,

#### to draw a total of 2 balls from both urns?

#### to get two pairs of balls of the same color?

#### to get four different colored balls?

#### to get exactly one pair of balls of the same color?

## Multiple Choice

### Part A

Are the following statements right or wrong?

#### Be $A$, $B$, $C$ $\subset \omega$ events. The event: "At least two of these events occur" can be represented graphically as follows:

#### From $n$ objects $r$ elements shall be selected. Then the number of choices for a variation with repetition can not be smaller than for a variation without repetition.

#### The certain event has the probability one. But an event with a probability of one is only "almost certain".

#### Two events, which have no common elements, are disjoint.

#### Using the objective concept of probability, the individual case is considered, but not the series ("long run").

#### For two events $A$ and $B$ applies: $P(A \cap B) \le P(A) \le P(A \cup B) \le P(A) + P(B)$.

#### If three events $A$, $B$ and $C$ are stochastically independent in pairs, then there is valid: $P(A \cap B \cap C) = P(A) \cdot P(B) \cdot P(C)$.

#### If three events $A$, $B$ and $C$ are completely disjoint [i.e. $(A \cap B \cap C) = \emptyset$], then they are also disjoint in pairs [i.e. $(A \cap B) = \emptyset$, $(B \cap C) = \emptyset$ and $(C \cap A) = \emptyset$].

#### Let $A$ and $B$ be events (with: $0 < P(A) < 1$ and $0 < P(B) < 1$). If $P(A \cap B) = 0$, then $A$ and $B$ are stochastically independent.

#### The probability of throwing a non-ideal die twice with a maximum of a "6" is equal to the probability of not throwing a "6" at least once.

## Exercise F4

### Part A

Three different special prizes are raffled off in a game show. Three urns are available for the raffle, each containing six tickets with the names of the six players. One ticket is drawn from each urn.

#### How many possibilities are there to draw a ticket from each of the three urns?

#### How many possibilities are there to draw a ticket from each of the three urns, whereby no name is drawn several times?

### Part B

After the game show, the six candidates (who are all looking for comfort) are taken to their hotel in two cars of different comfort. One car can accommodate up to four candidates. 

#### How many possibilities are there to accommodate the six candidates in the two cars?

### Part C

The publishing house "Schöne Kinderwelt" would like to publish a fairy tale book. The publishing house owns the rights to 6 fairy tales by the Brothers Grimm and 4 fairy tales by Hans Christian Andersen as well as the rights to 2 fairy tales by other authors. For reasons of cost, only 7 fairy tales should be selected.

#### How many possibilities are there to select the 7 fairy tales?

#### How many possibilities remain if 3 fairy tales by the Grimm brothers, 3 by Hans Christian Andersen and 1 fairy tale by other authors are to be selected?

#### How many possibilities are there to arrange the 7 selected fairy tales in a book?

## Exercise F5

### Part A

In a lottery there are 10 winners. The following cars are available as main prizes:
5 cars from "Idua" | 3 cars from "WMB" | 2 cars from "WV".

#### How many ways are there to distribute the cars to the winners?

In another lottery, six companies each provide one car, but the cars differ considerably in price and quality. Only three winners have declared their claim to the prize.

#### How many possibilities are there to distribute the cars among the three winners, if everyone should only get one car at a time?

## Exercise F6

### Part A

Of three events $A$, $B$, $C$ occur:

1. only $A$.
2. exactly one.
3. at most one.
4. at least one.
5. exactly two.
6. at least two.
7. at least one not.
8. at least two not.

#### Use the event operations to formally represent the searched events and draw the corresponding Venn diagram for each.

## Exercise F7

### Part A

In a small town there are only the two daily newspapers $Z1$ and $Z2$. 60% of the inhabitants read $Z1$ and 80% of the inhabitants read $Z2$. Neither newspaper is read by 10% of the residents. A person is chosen at random. What is the probability that this person

#### reads both newspapers?

#### reads $Z1$, but not $Z2$?

#### reads $Z2$ if she is not a Z1 reader?

#### reads at most one newspaper?

#### does not read $Z1$?

## Exercise F8

### Part A

In an apartment in an old building with exterior walls and an outdated electrical system, it can happen that the electricity fails or the water supply freezes. Both circumstances occur independently, but depend on the season. Thus, of course, the water only freezes when it is winter, with a probability of 80%. However, even if it is not winter, there is a 40% probability that the electricity will fail, which is the same probability that the electricity will not fail when it is winter.
Assume that the winter season accounts for 30% of the total season.

#### Use event symbols to formalize the probability statements mentioned in the text.

#### With what probability must one expect the water supply to freeze?

#### With what probability must one expect a power failure?

#### With what probability must one expect the water supply to freeze and a power failure?

#### If the power has already been cut off, with what probability must one expect the water supply to freeze?

#### With what probability must one additionally expect a power failure if the water supply is already frozen?

#### With what probability must one expect at least one of both problems?

#### With what probability must one expect at most one of the two problems?

## Exercise F9

### Part A

At a small border crossing, two customs officers share the duty exactly halfway. When the first customs officer is on duty, he checks passports with a probability of 20% and searches cars with a probability of 10% independently of a passport check. When the second customs officer is on duty, he checks passports with a probability of 70% and searches cars with a probability of 40% independently of a passport control.

#### Define meaningful events based on the text and formalize the specified probabilities.

You drive to this border crossing with a car at any time.

#### What is the probability that your car will be searched?

#### What is the probability of a passport check?

#### What is the probability that you will be searched and your car will be checked?

#### If your passport has already been checked, how likely are you to have your car searched?

#### If your car has already been searched, how likely are you to face an additional passport check?

#### What is the probability that you will have to expect exactly one of both measures?

## Exercise F10

### Part A

A man is looking for his umbrella, which he has left in a building with a 60% probability. And if it is true, with equal probability in one of the 6 floors.

Use the following events for your solution:

* $B$: "Umbrella is in the building."
* $F$: "Umbrella is in the first 5 floors.
* $S$: "The umbrella is on the 6th floor."

#### What is the probability that the umbrella is in the building and on the 6th floor of the building?

#### What is the probability that the umbrella is on the 6th floor if you don't know if it is in the building?

#### What is the probability that the umbrella is not on the first 5 floors if you know that it is not on the 6th floor?

#### What is the probability that the umbrella is not on the first 5 floors?

#### The umbrella is not in the first 5 floors. What is the probability that the umbrella is in the building?

## Exercise F11

### Part A

The Road Traffic Office is conducting a study on the aggression behavior of drivers towards cyclists and comes to the following conclusion:

* A male motorist reacts to a hindrance by a cyclist with a 30% probability by "honking" and (independently of this) with a 20% probability by "insulting". 
* A female motorist reacts to a hindrance caused by a cyclist with a 15% probability by "honking" and (independently of this) with a 10% probability by "insulting". 
* Meeting a man behind the wheel or a woman behind the wheel can be considered equally likely.

#### Define corresponding events and assign the probability values mentioned in the text to them.

Suppose you are a cyclist who is hindering a person behind the wheel of a car.

#### Will this person honk?

#### Will this person insult you?

#### Will this person honk the horn and insult you?

#### Will this person insult you even if he or she honks already?

## Exercise F12

### Part A

In a horse race exactly seven horses start.

#### How many possibilities are there to divide the seven horses among the ten starting boxes?

#### How many possible finishes are there in places one to seven?

#### How many possibilities are there for the distribution of ranks one to three?

### Part B

Today is a big race day in Hoppewald with three scheduled races. In the individual races the following horses will be at the start:

* Race I : $A$, $B$ and $C$
* Race II : $D$, $E$, $F$, $G$ and $H$
* Race III: $A$, $B$, $C$, $D$, $E$, $F$, $G$ and $H$

The following victory probabilities apply to the individual horses, with the outcomes of the three races being independent of each other:


```r
race <- c(rep("I", times = 2), rep("II", times = 4), rep("III", times = 7))
horse <- c(LETTERS[1:2], LETTERS[4:7], LETTERS[1:7])
victory <- c(0.2, 0.4, 0.1, 0.2, 0.3, 0.4, 0.05, 0.1, 0.05, 0.05, 0.1, 0.1, 0.05)
tbl <- tibble(race = race, horse = horse, victory = victory)
names(tbl) <- c("Race", "Horse", "Probability of Victory")

kable(tbl)
```



|Race |Horse | Probability of Victory|
|:----|:-----|----------------------:|
|I    |A     |                   0.20|
|I    |B     |                   0.40|
|II   |D     |                   0.10|
|II   |E     |                   0.20|
|II   |F     |                   0.30|
|II   |G     |                   0.40|
|III  |A     |                   0.05|
|III  |B     |                   0.10|
|III  |C     |                   0.05|
|III  |D     |                   0.05|
|III  |E     |                   0.10|
|III  |F     |                   0.10|
|III  |G     |                   0.05|

What are the probabilities of the following events:

#### Horse $C$ wins exactly one of his races.

#### Horse $C$ wins both of his races.

#### Horse $C$ wins at least one of his races.

#### Horse $C$ wins at most one of his races.

#### Horse $C$ wins none of his races.

The horses C and H belong to the same racing stable.

#### What is the probability that this racing team will be able to celebrate a winner today, i.e. to be the winner in at least one race?

## Exercise F13

### Part A

In Skat, an ideal deck of cards (32 cards) is distributed among three players and the "Skat". Each player receives 10 cards, the remaining 2 cards go into the "Skat". The four existing jacks have a particularly important meaning in the Skat game. 

#### What is the probability that two jacks are in the "Skat"?

#### What is the probability that exactly one jack is in the "Skat"?

#### What is the probability that the jack of clubs is in the "Skat"?

### Part B

Two ideal dice are thrown. One cube is red, the other is white. The following events are defined:

* $A$: "The number of the white cube is even."
* $B$: "The number of the red cube is odd."
* $C$: "The sum of the eyes of both cubes is straight."
* $D$: "The sum of the eyes of both cubes is odd."

#### Determine the probabilities of the events $A$, $B$, $C$ and $D$.

#### What elements of $\Omega$ make up the following events?

1. $A \cap B$.
2. $A \cap C$.
3. $B \cap C$.

#### Use _Laplace_'s concept of probability to determine the probabilities of the events

#### Are the events $A$, $B$ and $C$ pairwise stochastically independent? Justify your respective answer with the help of a formal arithmetic operation.

#### Determine the probability of the event: $(A \cap B \cap C)$

#### Are the events $A$, $B$ and $C$ completely stochastically independent? [i.e. $P(A \cap B \cap C) = P(A) \cdot P(B) \cdot P(C)$]

One of the following statements is correct. Indicate which statement is correct:

1. "Completely stochastically independent events are always also stochastically independent in pairs."
2. "Pairwise stochastically independent events are always also completely stochastically independent."

### Part C

In a tennis match, player A wins a single set against player B with probability $p$. The winner of the whole match is the first player to win two sets.

Be $G_i$ : "Player A wins the ith set" with $i \in \{ 1, 2, 3 \}$.

### Depending on p, specify the probability that player A will win the match.

## Exercise F14

### Part A

A family was at the picnic today: Father Martin, mother Silke, the children Anja and Dirk as well as grandpa Arnold. On the way home the children suddenly notice that grandpa is no longer there. There are three possibilities:

* $A$: Grandpa is already at home and sitting comfortably in his armchair.
* $B$: Grandpa is still at the picnic area and taking his nap.
* $C$: Grandpa has gone to the nearby forest and is looking for mushrooms.

Because of the habits of grandpa, one knows the probabilities for the occurrence of events $A$, $B$ and $C$:

$$P(A) = 0.15, \, P(B) = 0.8, \, P(C) = 0.05 \, .$$

Anja is sent back to the picnic place and Dirk is sent to the edge of the forest to look for the grandfather. If grandpa is at the picnic place, Anja finds him with a probability of 90%. But if he is running around in the forest, Dirk will find him with a probability of only 50%.

#### What is the probability that Anja will find the grandpa?

#### What is the probability that Dirk will find the grandpa?

#### What is the probability that one of the children will find the grandpa?

#### What is the probability that the grandpa will be sitting in his armchair when he returns home, in case the children do not find him?

## Exercise F15

### Part A

A florist has an assortment of tulip bulbs. Of these bulbs 20% make blue tulips, the rest make red tulips. 60% of the bulbs make tulips with smooth leaves, the rest make tulips with pointed leaves. If a tulip is blue, it has smooth leaves in 10% of the cases.

It applies:

* R: "The tulip turns red."
* G: "The tulip will have smooth leaves."

#### Calculate the probability that a tulip will have red color **and** smooth leaves.

#### Calculate the probability that a tulip will turn red if you know that it will have smooth leaves.

#### Calculate the probability that a tulip will have smooth leaves if you know that it will turn red.

#### Calculate the probability that a tulip will turn red if you know that it will turn pointed.

#### Calculate the probability that a tulip will turn red **or** smooth if you know it will turn red **and** smooth.

#### Calculate the probability that a tulip will become blue **or** smooth if you know it will become red **and** pointed.

#### Calculate the probability that a tulip will turn red **or** smooth if you know it will turn red **and** pointed.

#### Calculate the probability that a tulip will turn red **and** smooth if you know it will turn red **or** smooth.
