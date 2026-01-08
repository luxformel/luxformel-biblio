---
title: "Taylor Series and Power Series"
date: 2026-01-08T11:27:35+01:00
# weight: 1
# aliases: ["/first"]
tags: ["Calculus", "Taylor Series", "Power Series", "Applied Mathematics"]
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

# Taylor Series and Power Series

## Exercise 1 : Expansion of a Function in a Power Series

Expand the following functions at $x_0 = 0$ in a series up to the first four terms:

1. $f(x) = \sqrt{1 - x}$
2. $f(t) = \sin(\omega t + \pi)$
3. $f(x) = \ln[(1 + x)^5]$
4. $f(x) = \cos x$
5. $f(x) = \cosh x$

## Exercise 2 : Interval of Convergence of a Power Series

Obtain the radius of convergence of the following series:

1. $f(x) = \sin x = \sum_{n=0}^{\infty} \frac{(-1)^n}{(2n+1)!} x^{2n+1}$
2. $f(x) = \frac{1}{1 - 3x} = \sum_{n=0}^{\infty} 3^n x^n$

## Exercise 3 : Approximate Value of Functions

Sketch in the neighbourhood of $x_0 = 0$ the function $f(x)$ and the graphs of the approximate polynomials $P_1(x)$, $P_2(x)$ and $P_3(x)$.

1. $y = \tan x$
2. $y = \frac{x}{4 - x}$

## Exercise 4 : Taylor Expansion Around $\pi$

Expand the following functions at $x_0 = \pi$:

1. $y = \sin x$
2. $y = \cos x$

## Exercise 5 : Logarithm Expansion at 1

Expand the function $f(x) = \ln x$ at $x_0 = 1$.

## Exercise 6 : Rational Function Expansion at 2

Expand the function $f(x) = \frac{4}{x}$ at $x_0 = 2$. Obtain the first four terms.

## Exercise 7 : Intersection and Cubic Approximations

1. Determine the intersection – which lies in the first quadrant – of the functions $e^x - 1$ and $2 \sin x$. Approximate both functions by a polynomial of the third degree, $P_3(x)$.

## Exercise 8 : Numerical Square-root Approximation

Calculate $\sqrt{42} = \sqrt{36 + 6}$ to 4 decimal places.

## Exercise 9 : Approximation with 1% Error

Replace the function $f(x)$ by an approximate polynomial in the interval $(0, 0.3)$. The error should not exceed $1\%$.

1. $f(x) = \ln(1 + x)$
2. $f(x) = \frac{1}{\sqrt{1 + x}}$

## Exercise 10 : Quarter-point Approximations

Given the functions $f(x)$, compute approximately (see Table 8.1) the value of $f(1/4)$. The value obtained should have an accuracy of $10\%$.

1. $f(x) = e^x$
2. $f(x) = \ln(1 + x)$
3. $f(x) = \sqrt{1 + x}$

## Exercise 11 : Integrating Power Series

Let the series for the function $f(x) = \sum_{n=0}^{\infty} a_n x^n$ be given. Obtain a series expansion for the integral $\int f(x) \, dx$ by integrating the series term by term for the following functions:

1. $f(x) = \frac{1}{1 + x} = \sum_{n=0}^{\infty} (-1)^n x^n = 1 - x + x^2 - x^3 + x^4 - \cdots \quad (|x| < 1)$
2. $f(x) = \cos x = \sum_{n=0}^{\infty} (-1)^n \frac{x^{2n}}{(2n)!} = 1 - \frac{x^2}{2!} + \frac{x^4}{4!} - \frac{x^6}{6!} + \cdots$

## Exercise 12 : Integrals via Series

Solve the following integrals using a series expansion:

1. $\int_0^{0.58} \sqrt{1 + x^2} \, dx$
2. $\int_0^x \frac{\sin t}{t} \, dt$ (Integral (b) cannot be evaluated by any other method.)

## Exercise 13 : Inverse Sine and $\pi$ Series

1. Obtain a power series for $\sin^{-1} x$ by first expanding $1/\sqrt{1 - x^2}$, which is the derivative of $\sin^{-1} x$, and second, integrating term by term.
2. Since $\sin^{-1}(1) = \pi/2$, by inserting $x = 1$ into the series one obtains a series for $\pi/2$. Compute the value of this series up to the fifth term and compare it with the correct numerical value.

## Exercise 14 : Binomial Series for Fractional Powers

Expand the following using the generalized binomial theorem up to the first four nonzero terms and state the interval of validity:

1. $(1 + x)^{1/2}$ about $x_0 = 0$
2. $(1 + x)^{-3/2}$ about $x_0 = 0$

## Exercise 15 : Laurent-Type Expansion and Singularities

Find a series expansion (Taylor or Laurent as appropriate) for the following about the indicated point and identify the singularity type if any:

1. $f(x)=\dfrac{1}{x(1-x)}$ about $x_0=0$ (write as power series valid for $|x|<1$)
2. $g(x)=\dfrac{1}{(x-1)^2}$ about $x_0=1$ (express principal part up to order $(x-1)^{-2}$)

## Exercise 16 : Fourier Series — Basic Computation

Compute the Fourier series (half-range or full as appropriate) for the 2$\pi$-periodic extension of the function:

1. $f(x)=x$ on $(-\pi,\pi)$ write the first three nonzero terms

## Exercise 17 : Series Solution of an ODE

Find a power-series solution about $x_0=0$ up to order $x^3$ for the ODE:

1. $y'(x)-y(x)=x$, with $y(0)=1$

## Exercise 18 : Multivariable Taylor Polynomial

Find the second-order Taylor polynomial about $(0,0)$ for:

1. $f(x,y)=e^{x}\cos y$

## Exercise 19 : Radius of Convergence Practice

Determine the radius of convergence for the following series and justify your answer:

1. $\sum_{n=0}^{\infty} n!\,x^n$
2. $\sum_{n=0}^{\infty} \dfrac{x^n}{n!}$

## Exercise 20 : Error Bounds for Taylor Approximation

Use the Lagrange remainder to bound the error when approximating $e^x$ on $[0,1]$ by its Taylor polynomial of degree 3 about $0$. Provide a numerical upper bound.

## Exercise 21 : Generating Functions — Fibonacci

Show that the generating function for the Fibonacci sequence $F_n$ is $G(x)=\dfrac{x}{1-x-x^2}$, expand $G(x)$ to obtain the first six terms of the sequence, and comment on radius of convergence.
