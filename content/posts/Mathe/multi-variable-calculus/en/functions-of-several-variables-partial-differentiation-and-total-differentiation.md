---
title: "Functions of Several Variables; Partial Differentiation; and Total Differentiation"
date: 2026-01-08T10:54:10+01:00
# weight: 1
# aliases: ["/first"]
tags: ["Multi Variable Calculus", "Partial Differentiation", "Total Differentiation", "Applied Mathematics"]
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

# Functions of Several Variables; Partial Differentiation; and Total Differentiation

## Exercise 1 : Table of Variables

Construct a table of values for the function $f(x, y) = x^2 y + 6$ where $x = -2, -1, 0, 1$ and $y = -2, -1, 0, 1, 2$.

## Exercise 2 : Plane and Quadratic Surfaces

What surfaces are represented by the following functions? Sketch them!

1. $z = -x - 2y + 2$
2. $z = x^2 + y^2$
3. $z = \sqrt{1 - \frac{x^2}{4} - \frac{y^2}{9}}$

## Exercise 3 : Partial Derivatives — Practice

Obtain the partial derivatives of

1. $f(x, y) = \sin x + \cos y$
2. $f(x, y) = x^2 \sqrt{1 - y^2}$
3. $f(x, y) = e^{-(x^2 + y^2)}$
4. $f(x, y, z) = xyz + x \cos(x + y)$
5. $f(x, y) = e^x \ln y + z^4$

## Exercise 4 : Tangent Slopes to a Paraboloid

Determine the slope of the tangent in the $x$- and $y$-directions to the surface $z = x^2 + y^2$ at the point $P = (0, 1)$.

## Exercise 5 : Second Partial Derivatives (Mixed Partials)

Determine the partial derivatives $f_{xx}$, $f_{xy}$, $f_{yx}$, and $f_{yy}$ of the function $z = R^2 - x^2 - y^2$.

## Exercise 6 : Euler-Type Relation

Show that the function $z = e^{(x/y)^2}$ satisfies the relation $x f_x + y f_y = 0$.

## Exercise 7 : Total Differentials — Linear Approximations

Determine the total differential of the functions:

1. $z = \sqrt{1 - x^2 - y^2}$
2. $z = x^2 + y^2$
3. $f(x, y, z) = \frac{1}{x^2 + y^2 + z^2}$

## Exercise 8 : Error Propagation in a Conical Tank

A container in the form of an inverted right circular cone has a radius of $1.75$ m and a height of $4$ m. The radius is subject to a tolerance of $50$ mm and the height to a tolerance of $75$ mm.

1. Calculate the total percentage tolerance in the volume.
2. Calculate the total percentage tolerance in the surface area of the container.

## Exercise 9 : Contour Lines and Gradients

Find the contour lines and calculate the gradient for the following functions:

1. $f(x, y) = -x - 2y + 2$
2. $f(x, y) = \sqrt{1 - \frac{x^2}{4} - \frac{y^2}{9}}$
3. $f(x, y) = \frac{10}{\sqrt{x^2 + y^2}}$

## Exercise 10 : Level Surfaces and Gradient Vectors

Find the surfaces of constant functional values and calculate the gradient.

1. $f(x, y, z) = x + y - 3z$
2. $f(x, y, z) = x^2 + y^2$
3. $f(x, y, z) = (x^2 + y^2 + z^2)^{3/2}$

## Exercise 11 : Chain Rule — Time Derivatives

Obtain $du/dt$ when:

1. $u = x^2 - 3xy + 2y^2$ and $x = \cos t$, $y = \sin t$
2. $u = x + 4\sqrt{xy} - 3y$, $x = t^3$, $y = 1/t$

## Exercise 12 : Implicit Differentiation — Practice

Obtain $dy/dx$:

1. $x^3 - y^3 + 4xy = 0$ at $x = 2$, $y = -2$
2. $xy + \sin y = 2$ at $x = 4$, $y = \pi/2$

## Exercise 13 : Maxima and Minima — Critical Point Tests

Examine the following functions for maxima and minima:

1. $f(x, y) = x^3 - 3xy + y^3$
2. $f(x, y) = 12x + 6y - x^2 + xy - y^2$

## Exercise 14 : Traveling Wave Functions

Two cables considered as being infinitely long are excited at the left-hand end with an amplitude $A$ and a frequency $f$. Write down the wave function for

1. $A = 0.5 \text{ m}$, $f = 5 \text{ Hz}$, $\lambda = 1.2 \text{ m}$
2. $A = 0.2 \text{ m}$, $f = 0.8 \text{ Hz}$, $\lambda = 4.0 \text{ m}$

## Exercise 15 : Wave Equation Verification

Verify that the function $f(x, t) = e^{-(vt - x)^2}$ satisfies the wave equation
$$ \frac{\partial^2 f}{\partial t^2} = v^2 \frac{\partial^2 f}{\partial x^2} $$

## Exercise 16 : Directional Derivative and Unit Direction

Compute the directional derivative of $f(x,y)=x^2y+e^{xy}$ at the point $(1,0)$ in the direction of the vector $(2,1)$. First normalize the direction.

## Exercise 17 : Jacobian and Change of Variables

Let $u=x-y$, $v=x+y$. Compute the Jacobian $\frac{\partial(u,v)}{\partial(x,y)}$ and use it to transform the integral $\iint_R (x^2-y^2)\,dx\,dy$ where $R$ is the square $-1\le x,y\le1$ into $u,v$ coordinates.

## Exercise 18 : Second-Order Taylor Polynomial

Find the second-order Taylor polynomial of $f(x,y)=\ln(1+x^2+y^2)$ about the origin and estimate the remainder order.

## Exercise 19 : Constrained Extrema (Lagrange Multipliers)

Use Lagrange multipliers to find the extrema of $f(x,y)=x^2+2y^2$ subject to the constraint $x+2y=3$.

## Exercise 20 : Hessian Matrix and Classification

Compute the Hessian of $f(x,y)=x^3-3xy+y^3$ at its critical points and classify each as local min, local max, or saddle.

## Exercise 21 : Implicit Function Theorem Application

For the equation $x^2+y^2+z^2-1=0$, show locally near $(0,0,1)$ that $z$ is a function of $(x,y)$ and compute $\partial z/\partial x$ and $\partial z/\partial y$ at the origin.

## Exercise 22 : Laplacian and Harmonic Functions

Compute the Laplacian $\Delta f$ for $f(x,y)=\ln(x^2+y^2)$ (on its domain) and determine whether $f$ is harmonic where defined.

## Exercise 23 : One Step of Gradient Descent

For $f(x,y)=x^2+4y^2$, compute the gradient at $(1,1)$ and give the point after one gradient descent step with learning rate $\alpha=0.1$.

## Exercise 24 : Differentiability versus Partial Derivatives

Give an example of a function $f(x,y)$ which has partial derivatives at $(0,0)$ but is not differentiable there, and briefly explain why.

## Exercise 25 : Equality of Mixed Partials

Verify whether $f_{xy}=f_{yx}$ for $f(x,y)=\begin{cases} \dfrac{xy(x^2-y^2)}{x^2+y^2} & (x,y)\ne(0,0)\\ 0 & (x,y)=(0,0) \end{cases}$ by computing the mixed partials at the origin.
