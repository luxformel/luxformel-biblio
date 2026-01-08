---
title: "Differential Equations"
date: 2026-01-08T10:09:01+01:00
# weight: 1
# aliases: ["/first"]
tags: ["Calculus", "Differential Equations", "Applied Mathematics"]
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

# Differential Equations

## Exercise 1 : Classification — Linear vs Nonlinear

Which of the following are linear first- and second-order DEs with constant coefficients?

1. $y' + x^2 y = 2x$
2. $5y'' - 2y' - 4x = 3y$
3. $y^4 + 2y'' + 3y' = 0$
4. $\sin x\, y'' - y = 0$
5. $y'' - x^5 = 2$
6. $2y'' - y' + \frac{3}{2}y = 0$

## Exercise 2 : Homogeneity and Order

Which of the following are homogeneous and non-homogeneous DEs and what is the order in each case?

1. $y'' + ax = 0$
2. $\frac{5}{4}y'' + \frac{2}{3}y' = \frac{1}{2}y$
3. $2y' = 3y$
4. $\frac{3}{10}y'' + \frac{2}{5}y' + \frac{1}{6}y - \sin x = 0$
5. $3y'' + y' = 2y$

## Exercise 10.3 : Characteristic Equations — Homogeneous Linear ODEs

Solve the following DEs. In the case of complex roots give the real solution.

1. $2y'' - 12y' + 10y = 0$
2. $4y'' - 12y' + 9y = 0$
3. $y'' + 2y' + 5y = 0$
4. $y'' - \frac{1}{2}y' + \frac{5}{8}y = 0$
5. $\frac{1}{4}y'' + \frac{1}{2}y' - 2y = 0$
6. $5y'' - 2y' + y = 0$

## Exercise 4 : First-Order Linear — Separable and Exponential Solutions

Solve the following DEs:

1. $2y' + 8y = 0$
2. $\frac{1}{5}y' = 6y$
3. $3y' = 6y$

## Exercise 5 : Simple Second-Order Integrations

Obtain the general solution of the following second-order DEs:

1. $S''(t) = 2t$
2. $x''(t) = -\omega^2 \cos \omega t$

## Exercise 6 : Non-homogeneous Second-Order — Method of Undetermined Coefficients

1. $y'' + y' + y = 2x + 3$
2. $y'' + 4y' + 2y = 2x + 3$

## Exercise 7 : Non-homogeneous Examples — Polynomial and Trigonometric Forcing

1. $7y'' - 4y' - 3y = 6$
2. $y'' - 10y' + 9y = 9x$
3. $3y'' - y' - 4y = x^2$
4. $y'' + 2y' + 5y = \cos 2x$

## Exercise 8 : Verify Particular Integral and General Solution

A particular integral $y_p(x)$ of the following non-homogeneous DE is known. Check that it is a solution and obtain the general solution of the DE.

$$
\frac{1}{2}y'' - 3y' + \frac{5}{2}y = \frac{3}{4}x^2 - 1, \,\quad y_p(x) = \frac{3}{10}x^2 + \frac{18}{25}x + \frac{43}{125}
$$

## Exercise 9 : Initial Value Problems — First-Order Linear

1. $\frac{1}{2}y' + 2y = 0$ (given that $y(0) = 3$)
2. $\frac{4}{7}y' - \frac{6}{5}y = 0$ (given that $y(10) = 1$)

## Exercise 10 : Parameter Determination — Using Initial/Boundary Values

The DE $\frac{1}{3}y' - \frac{2}{3}y = 0$ has for its general solution $y(x) = Ce^{2x}$. Calculate the value of the constant if

1. $y(0) = 0$
2. $y(0) = -2$
3. $y(-1) = 1$
4. $y'(-1) = 2e^{-2}$

## Exercise 11 : Boundary Value Problems — Simple Harmonic Solutions

Solve $y'' + 4y = 0$ for the following boundary conditions:

1. $y(0) = 0$, $y\left(\frac{\pi}{4}\right) = 1$
2. $y\left(\frac{\pi}{2}\right) = -1$, $y'\left(\frac{\pi}{2}\right) = 1$
3. $y(0) = 0$, $y'(0) = 1$
4. $y\left(\frac{\pi}{4}\right) = a$, $y''(0) = b$

## Exercise 12 : Constant-Coefficient IVP — Reduction to Standard Form

Solve $y'' + y = 2y'$, given that $y(0) = 1$ and $y(1) = 0$.

## Exercise 13 : First-Order Linear — Integrating Factor and Nonhomogeneous Terms

Solve the following first-order linear DEs:

1. $xy' = 2y - x\frac{y}{x}$
2. $y' = \frac{y}{x} + x$
3. $y' + y\tan x = \sin 2x$
4. $xy' + (1+x)y = xe^{-x}$

## Exercise 14 : Bernoulli-Type Equations

Verify that the following DEs can be brought into the form of Bernoulli-type equations and solve them.

1. $y' + xy = xy^3$
2. $y' - \frac{2}{x^2 - 1}y = -y^2$
3. $x^2y' + xy^3 = 1$
4. $yy' + \frac{y^2}{x} + x = 0$

## Exercise 15 : Separable Equations

In the following DEs, the variables can be separated. Solve

1. $y' = e^{x-2y}$
2. $y' + xy' + \frac{x}{y} = 0$
3. $xy' + (\ln x)y^2 = 0$
4. $(y')^2 + xe^x y' + xe^x = 1$

## Exercise 16 : Exact Equations — Potential Functions

Verify that the following are exact DEs. Find $F$ and solve.

1. $2y' + (4 - y^2) = 0$
2. $(1 - xe^{-y})y' + e^{-y} = 0$
3. $2y - x^2 \sin 2y$ $y' + 2x \cos^2 y = 0$
4. $(2x - 3)y' + 3x^2 + 2y = 0$

## Exercise 17 : Integrating Factors — Make Equations Exact

You will remember that the integrating factor $\mu(x, y)$ for a DE $p(x, y)y' + q(x, y) = 0$ is easy to find in special cases. Solve the following equations by finding an integrating factor, $\mu$, and then solving the exact equation.

1. $\sin y \cdot y' - \cos y = -e^{2x}$
2. $(e^y - x)y' + 1 = 0$

## Exercise 18 : Systems of Linear ODEs — Eigenvalue Methods

Solve the following simultaneous DEs:

1. $x' - 7x + y = 0$
  $y' - 2x - 5y = 0$
2. $x' + y' + 2x + y = 0$
  $y' + 5x + 3y = 0$

## Exercise 19 : Variation of Parameters

Use variation of parameters to find a particular solution for each of the following non-homogeneous ODEs and hence write the general solution.

1. $y'' + y = \tan x$ on an interval where $\tan x$ is defined.
2. $y'' - y = e^x/x$ for $x>0$.

## Exercise 20 : Reduction of Order

Given one solution, reduce the order to find a second linearly independent solution.

1. If $y_1(x)=e^{2x}$ solves $y'' - 4y' + 4y=0$, find $y_2(x)$.
2. If $y_1(x)=x$ solves $x^2y''-x(x+2)y'+(x+2)y=0$, find $y_2(x)$ for $x>0$.

## Exercise 21 : Power Series Solutions

Find the power-series solution about $x=0$ (up to the first four nonzero terms) for:

1. $y'' - xy = 0$.
2. $y'' + xy' + y = 0$.

## Exercise 22 : Laplace Transform Techniques

Solve the following initial-value problems using Laplace transforms.

1. $y'' + 3y' + 2y = u(t-1)$, $y(0)=0$, $y'(0)=0$, where $u$ is the unit step.
2. $y'' + 4y = \delta(t-\pi)$, $y(0)=0$, $y'(0)=0$, where $\delta$ is the Dirac delta.

## Exercise 23 : Sturm–Liouville / Eigenvalue Problems

Find eigenvalues and eigenfunctions for the following boundary-value problems.

1. $y'' + \lambda y = 0$, $y(0)=0$, $y(\pi)=0$.
2. $y'' + \lambda y = 0$, $y'(0)=0$, $y'(L)=0$.

## Exercise 24 : Numerical Methods — Euler and Stability

Implement (by hand or pseudocode) the explicit Euler method for $y'=f(t,y)$ and analyze local truncation error for $y'=\lambda y$.

1. Apply one Euler step to $y'= -5y$ with $y(0)=1$ and step $h=0.1$.
2. Discuss stability condition for the explicit Euler method applied to $y'=\lambda y$.

## Exercise 25 : Green's Functions and Forcing

Construct the Green's function for the BVP $y''=f(x)$ with $y(0)=0$, $y(1)=0$, and use it to write the solution operator. Provide explicit formula for $f(x)=x$.
