---
title: "Probability Distributions"
date: 2026-01-08T09:15:23+01:00
# weight: 1
# aliases: ["/first"]
tags: ["Probability", "Applied Mathematics"]
categories: ["Mathé"]
author: "Luxformel"
# author: ["Me", "You"] # multiple authors
showToc: true
TocOpen: false
draft: false
hidemeta: false
comments: false
canonicalURL: "https://canonical.url/to/page"
disableHLJS: true # to disable highlightjs
disableShare: false
disableHLJS: false
hideSummary: false
searchHidden: false
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: true
ShowRssButtonInSectionTermList: true
UseHugoToc: true

math: true
---

# Probability Distributions

## Exercise 1 : Random Variable

Two dice are thrown. Calculate the mean value of the random variable 'sum of the number of spots'.

## Exercise 2 : Linear Continuous Distribution

A random variable has the probability distribution:

$$
  f(x) = 
  \begin{cases}
  \frac{x}{2}, & 0 \leq x \leq 2 \\
  0, & \text{otherwise}
  \end{cases}
$$
Compute the mean value of the random variable.

## Exercise 3 : Binomial Probability

60% of the students who start to study for an engineering degree complete their studies and obtain a degree. What is the probability that in a group of 10 arbitrarily chosen students in the first term of study 8 will obtain a degree?

## Exercise 4 : Normal Distributions — Means

Evaluate the mean values of the random variable $x$ which have the following normal distributions:

1. $f(x) = \frac{1}{3\sqrt{2\pi}} e^{-(x-2)^2/18}$
2. $f(x) = \frac{1}{\sqrt{2\pi}} e^{-(x+4)^2/2}$

## Exercise 5 : Binomial Mean and Variance

Let $X\sim\mathrm{Bin}(n=20,p=0.3)$. Compute the mean $E[X]$ and variance $\mathrm{Var}(X)$. What is $P(X\ge 8)$? Use an exact sum and approximate using a normal approximation with continuity correction.

## Exercise 6 : Poisson Approximation

For rare events with probability $p$ and large $n$, the binomial can be approximated by a Poisson distribution. Suppose on average 2 events occur per hour. What is the probability of observing 5 events in an hour? Show how this approximates a binomial with $n=1000$ and $p=0.002$.

## Exercise 7 : Exponential Distribution and Memoryless Property

Let $T$ be exponentially distributed with rate $\lambda=0.5\ \mathrm{hr}^{-1}$. Compute $E[T]$, $\mathrm{Var}(T)$ and $P(1<T\le 3)$. Show the memoryless property by computing $P(T>5\mid T>2)$.

## Exercise 8 : Continuous Uniform Distribution

Let $X\sim U(a=1,b=4)$. Compute the mean, variance and the distribution of $Y=2X+3$. Find $P(2<X<3.5)$.

## Exercise 9 : Chi-square and Student's

Let $Z_1,\dots,Z_n\stackrel{\text{iid}}{\sim}N(0,1)$. Define $Q=\sum_{i=1}^n Z_i^2$ and $T=Z_1/\sqrt{(Q-Z_1^2)/(n-1)}$. Show that $Q\sim\chi^2_n$ and $T$ has Student's $t$ distribution with $n-1$ degrees of freedom. Compute numeric examples for $n=10$.

## Exercise 10 : Sampling Distribution and Central Limit Theorem

Suppose $X_1,\dots,X_{36}$ are iid with mean $\mu=10$ and variance $\sigma^2=9$. Let $\bar X$ be the sample mean. Use the CLT to approximate $P(9.2<\bar X<10.8)$. Compare with exact result if $X_i$ are normal.

## Exercise 11 : Confidence Interval for a Mean

A sample of size $n=25$ from a normal population yields sample mean $\bar x=50$ and sample standard deviation $s=4$. Construct a 95% confidence interval for the population mean.

## Exercise 12 : Hypothesis Test for a Proportion

A poll of 200 voters finds 118 in favor of proposition A. Test at the 5% level whether the true proportion exceeds 0.5. State null and alternative hypotheses, test statistic and conclusion.

## Exercise 13 : Joint Distribution, Marginals and Independence

Let the joint pdf of $(X,Y)$ be

$$
f_{X,Y}(x,y)=\begin{cases}c(x+y),&0\le x\le1,\ 0\le y\le1,\\0,&\text{otherwise.}\end{cases}
$$

1. Determine $c$. 
2. Find marginal densities $f_X,f_Y$. 
3. Are $X$ and $Y$ independent? 
4. Compute $E[XY]$.

## Exercise 14 : Covariance and Correlation

Given two random variables with $E[X]=2,E[Y]=3,\mathrm{Var}(X)=4,\mathrm{Var}(Y)=9$ and $\mathrm{Cov}(X,Y)=3$, compute the correlation coefficient and interpret its value. If $Z=4X-2Y$, compute $E[Z]$ and $\mathrm{Var}(Z)$.

## Exercise 15 : Moment Generating Functions

Find the moment generating function $M_X(t)$ for an exponential random variable with rate $\lambda$. Use $M_X$ to compute $E[X]$ and $\mathrm{Var}(X)$.

## Exercise 16 : Transformation of Variables

Let $X\sim N(0,1)$ and let $Y=X^2$. Find the pdf of $Y$ and identify its distribution. Compute $E[Y]$.

## Exercise 17 : Law of Large Numbers

State and illustrate the (weak) law of large numbers: for iid $X_i$ with $E[X_i]=\mu$, show numerically how $\bar X_n$ concentrates near $\mu$ as $n$ increases for a chosen non-normal distribution (e.g., exponential).

## Exercise 18 : Bayesian Update with Beta Prior

Suppose prior for a probability $p$ is $\mathrm{Beta}(\alpha=2,\beta=2)$. After observing 7 successes and 3 failures, find the posterior distribution and its mean. Compute a 90% credible interval for $p$.

## Exercise 19 : Multivariate Normal — Marginal and Conditional

Let $(X,Y)$ be jointly normal with mean vector $(\mu_X,\mu_Y)$ and covariance matrix $\Sigma$. Write formulas for the marginal distribution of $X$ and the conditional distribution $X\mid Y=y$. Provide a simple numeric example and compute the conditional mean and variance.

## Exercise 20 : Goodness-of-Fit (Chi-square Test)

Given categorical data with observed counts in 4 categories: [25, 30, 20, 25] and expected equal proportions, perform a chi-square goodness-of-fit test at the 5% level.
