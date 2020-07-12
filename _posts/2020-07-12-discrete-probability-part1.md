---
title: 📑 [WIP] Discrete Probability Distributions (Part 1) - MathPhy with VBalki! 
author: Rohith Krishna
date: 12 July 2020
layout: post
permalink: /2020-07-12-discrete-probability-part1
tags: [stochastic processes, mathematical physics, probability]
---

### Some basic ideas in probability 

Consider a pair of fair dice and toss them once. We ask the question - *What kind of distribution do we obtain from tossing a pair of dice?* Consider $$s$$, denoting the sum of the score on the dice to be a random variable. The sample space of this score: $$s = \{2,3,4,…,12\}$$. *What is the probability of getting a particular score?* From the conservation of total probability, $$ \Sigma_{s=2}^{12} P_s = 1$$; where each $$P_s\in [0,1]$$.

*What is the most probable score?* 7. Because there are six outcomes favorable to this event, which is the  maximum for any event pertaining to the maximum score. 

*What is the probability of getting any score? Say, 3 in die1 and 4 in die2 ?* It is $$1/36$$, for it's $$1/6$$ for each die. *How many such distinct possibilities exist when you toss both the dice?*  The two die are independent distinguishable objects. So there are 36 microstates. (in the language of statistical physics.) This gives the detailed configuration of this system. 

**Note:** There are 36 microstates given by the sample space $$ \{\{1,1\}, \{1,2\},…\{6,6\}\}$$. The macrostates are labelled by the score $$s$$ and are 11 in number. The most probable macrostate is 7. Why? Because it is the most number of accessible microstates, given each microstate is equally probable. This reminds one of microcannonical ensembles in statistical mechanics. When you have a set of equally probable microstates, then the most probable macrostate is going to be the one that gets contributions from the largest number of microstates. 

Therefore $$P_7 = 1/6$$, contributed by the microstates $$\{(1,6), (2,5), (3,4), (4,3), (5,2), (6,1) \}$$. The extreme values for the macrostate are 2 and 12 with $$P_2 = P_{12} = 1/36$$. The probability distribution is given by the function:
$$
P_s = \begin{cases} a \\b \end{cases}
$$


