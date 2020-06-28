---
title: Difference Equations in Time-series Econometrics
author: Rohith Krishna
date: 28 June 2020
layout: post
permalink: /2020-06-28-difference-equations
---

The statistical modeling of macroeconomics involves varaibles with time-series data. Time series econometrics is concerned with the estimation of difference equations that contain stochastic components. The dynamic economic models use stochastic difference equations in order to forecast variables.

It is usually possible to decompose time-series data into *trend, cyclical (or seasonal)* and *irregular* components.

- The trend component refers to the long term behaviour of the series.
- The cyclical component is the periodic regular movements in the series.
- The stochastic component is the irregular component and our goal is usually to predict this component.

![Time Series](images/2020-06-28-difference-equations-img01.jpg)

The irregular component (herein called the *stochastic term*) is of particular importance to us. Although there exists no patterns in this components, positive and negative values often occur in runs. A large value is any period is followed by another large value. Also, over the entire span, the irregular component tends to revert to zero.

The objective of time-series econometrics is to find the equation of motion driving the stochastic process, and to use this equation to predict future outcomes. [^1] For example, consider a time-series of a variable $$y_t$$, where the subscript $$t$$ denotes the time. The three components could be decomposed as:

- Trend: $$ T_t = 1 +0.1 t$$,
- Cyclical: $$ S_t = 1.6 \sin \frac{t\pi}{6} $$, and,
- Irregular: $$ I_t = 0.7 I_{t-1} + \epsilon_t$$.

### Difference Equations

Difference equations are those where variables are expressed as a fuction of time, its own lagged values and other variables.  The trend and cyclical components depend on time, while the irregular component depends on lagged values and the stochastic disturbance term $$ \epsilon_t$$. As stated earlier objective is to estimate these difference equations containing stochastic components. In this accord, four difference equation models are presented here that finds application in macroeconomics and finance.

## Random Walk Hypothesis

Consider the day-to-day changes in the price of a stock. It is posited that the changes should have a mean value of 0. Effiecient speculation in the market drives up the stock price and no one would hold the stock if the price depreciates (rational investor). If $$ y_t$$ is the log of price of a share of this stock, then

$$y_{t+1} = y_t + \epsilon_t$$

$$ \Delta y_{t+1} = \epsilon_t $$

where, $$ \epsilon_{t+1} $$ is the random disturbance and has an expected value of 0.

Zero.
















[^1]: Herein lies its similarity with physics.
