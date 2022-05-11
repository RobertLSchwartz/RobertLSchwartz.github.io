---
title:  "Mathematics of Finance"
layout: single
classes: wide
permalink: /finance_math/
author_profile: true
comments: true
---

### The Mathematics of Asset Prices
---
**Asset Prices and the Role of Probability Theory**<br>
As an application of statistics to finance theory, we can often concern ourselves with the nature of financial asset prices 
and their periodic returns through the lens of probability theory. That is, we can view them as random variables drawn from
a particular probability distribution; perhaps prices being drawn from a lognormal distribution bounded at 0 and perhaps returns
being drawn from an (approximately) normal distribution.<br>

The probability distribution itself is a function of the complex and interrelated economic phenomena which vary across geographic 
regions and time.  In fact, each of such economic phenomenon can be characterized as a random variable itself. Nevertheless, the observed 
periodic returns – perhaps daily, weekly, monthly, quarterly, or annual – are the result of economic agents 
(i.e., professional portfolio managers and traders) actively forecasting the future state of these economic phenomena and the resulting
influence they may have on the asset’s value. Such traders frequently transact in securities attempting to generate abnormal profits,
ultimately driving their prices up and down over time. Note, however, such trading is a zero sum game. For one agent to win, another must
lose. This is the transactional nature of capital markets.<br>

Returning to our statistical perspective, given the randomness associated with asset prices, we cannot be certain as to their future levels. 
We therefore say the prices and the resulting periodic returns are uncertain, or “risky”. One way to wrap our minds around the uncertainty
surrounding these asset prices and make estimations as to the range of possible outcomes for future price levels or returns, is to
observe the probability distributions which govern them. To illustrate this, I will examine key characteristics of the distributions
and provide commentary for each in the sections below.<br>

**The S&P 500 Index: A Proxy for Aggregate Stock Prices**<br>
The S&P 500 index is a bellweather index for the U.S. equity market consisting of 505 consitutent companies.<br>
Below I show summary statistics describing the nature of S&P 500 index prices and returns.<br><br>
Note that the monthly prices (a discrete time series) seem to follow a lognormal distribution, having a minimum price of $0. 
Monthly total returns, which are the first difference of the monthly price series, seem to approximate a normal distribution.
The returns do seem to have fat tails, with periods of significant negative returns. We might consider the returns to be negatively skewed.
Additionally, the returns distribution seems to be leptokurtic.<br><br><br>
![S&P500 Plots](/assets/S&P500_Plot.jpeg/){:class="img-responsive" :height="75%" width="75%" : .align-center}<br><br>
![S&P500 Summary Stats](/assets/S&P500_monthly_summary_stats.jpeg/){:class="img-responsive" :height="40%" width="40%" : .align-center}<br><br>