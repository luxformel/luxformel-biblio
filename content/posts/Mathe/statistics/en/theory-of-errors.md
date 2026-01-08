---
title: "Theory of Errors"
date: 2026-01-08T09:35:29+01:00
# weight: 1
# aliases: ["/first"]
tags: ["Statistics", "Applied Mathematics"]
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

# Theory of Errors

## Exercise 1 : Types of Errors

In the following examples, state whether the error is systematic (constant $S$) or random $R$.

1. A 100-metre race is held in a school during a sports day. The judges start their stopwatches when the sound of the starting pistol reaches them. What type of error arises in this case?
2. The timing of the start and end of the 100-metre race is subject to individual fluctuations, e.g. reaction time. What kind of error is it?
3. The zero point of a voltmeter has been wrongly set. The measurements are therefore subject to an error. What kind of error is it?
4. The resistance of a copper coil is obtained by measuring the current flowing through when a voltage is applied to it. As the coil warms up the resistance increases. What kind of error will ensue?

## Exercise 2 : Sample Statistics

1. Nine different rock samples are taken from a crater on the moon whose densities are determined with the following results: $3.6, 3.3, 3.2, 3.0, 3.2, 3.1, 3.0, 3.1, 3.3 \frac{g}{cm^3}$. Calculate the mean value and standard deviation of the parent population.
2. The velocity of a body travelling along a straight line is measured 10 times. The results are $1.30, 1.27, 1.25, 1.26, 1.29, 1.31, 1.23, 1.33, 1.24 \frac{m}{s}$. Calculate the mean value and the standard deviation.

## Exercise 3 : Uniform Distribution Moments

A continuous random variable has the following density function:
$$
f(x) = 
\begin{cases} 
1, & 0 \leq x \leq 1 \\
0, & \text{otherwise}
\end{cases}
$$
Calculate the mean value and the variance.

## Exercise 4 : Normal Probability

A measured variable is normally distributed with a mean value $\mu = 8$ and a standard deviation $\sigma = 1$. What percentage of all test data are smaller than 7?

## Exercise 5 : Error Propagation — Area and Density

1. The sides of a rectangle are $x = 120 \pm 0.2  cm$ and $y = 90 \pm 0.1 cm$. Calculate the area and the standard deviation.
2. Calculate the density and the standard deviation of a sphere of diameter $6.2 \pm 0.1 mm$ and mass $1000 \pm 0.1  g$.

## Exercise 6 : Linear Fit (Spring Balance)

The sensitivity of a spring balance is to be determined. To achieve this we place different masses $m$ on the balance and record the deflection $S$. The results are:

| mass (mg): | 2000 | 3000 | 4000 | 5000 | 6000 |
|------------|------|------|------|------|------|
| deflection (mm): | 16 | 27 | 32 | 35 | 40 |

If a straight line is to be fitted through these data points, i.e. $S = am + b$, calculate the values of $a$ and $b$.

## Exercise 7 : Linear Regression with Uncertainties

In the spring-balance experiment you may instead have measured additional points with small known uncertainties. Suppose the measured deflections (mm) and their standard uncertainties are: $(16\pm0.5),(27\pm0.5),(32\pm0.5),(35\pm0.5),(40\pm0.5)$. Perform a weighted least-squares fit to $S=am+b$ and compute $a,b$ and their standard uncertainties.

## Exercise 8 : Weighted Angle Average

An angle has been measured several times with two theodolites and the following values were obtained: $73^\circ 2'7'' \pm 10'$ and $73^\circ 2'12'' \pm 20''$. Calculate the weighted average.

## Exercise 9 : Chi-square Test for Calibration

A calibration experiment yields counts in 5 bins: [102, 98, 95, 105, 100]. The expected (ideal) distribution is uniform. Perform a chi-square goodness-of-fit test at the 5% level and state whether the instrument agrees with the expected uniform response.

## Exercise 10 : Monte Carlo Error Propagation

Let $z=\dfrac{xy}{x+y}$ where $x=1.23\pm0.02$ and $y=2.34\pm0.03$ (independent). Estimate the value and standard uncertainty of $z$ using (a) first-order error propagation and (b) a Monte Carlo simulation (draw 10,000 samples from Gaussian distributions and compute the empirical mean and standard deviation).

## Exercise 11 : Significant Figures and Rounding Effects

Discuss how rounding to different numbers of significant figures influences propagated results. As a concrete example, compute the area of a rectangle with sides $x=12.34\,cm$ and $y=5.678\,cm$, (a) using full precision then rounding only the final result to 3 s.f., and (b) rounding each side to 3 s.f. before computing the area. Compare differences.

## Exercise 12 : Maximum Likelihood Estimation for Normal Errors

You measure a quantity several times: $8.1,8.0,8.3,7.9,8.2$. Assuming independent Gaussian measurement errors with unknown mean $\mu$ and known standard deviation $\sigma=0.1$, derive the maximum likelihood estimator for $\mu$ and compute its value and standard error.
