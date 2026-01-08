---
title: "Differential Calculus"
date: 2026-01-08T09:57:06+01:00
# weight: 1
# aliases: ["/first"]
tags: ["Calculus", "Differentiation", "Applied Mathematics"]
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

# Differential Calculus

## Exercise 1 : Sequences and Limits of Sequences

Calculate the limiting value of the following sequences for $n \to \infty$.

1. $a_n = \frac{\sqrt{n}}{n}$
2. $a_n = \frac{5 + n}{2n}$
3. $a_n = \left(-\frac{1}{4}\right)^n - 1$
4. $a_n = \frac{2}{n} + 1$
5. $a_n = \frac{n^3 + 1}{2n^3 + n^2 + n}$
6. $a_n = 2 + 2^{-n}$
7. $a_n = \frac{n^2 - 1}{(n + 1)^2} + 5$

## Exercise 2 : Limits of Functions

Calculate the following limits:

1. $\lim_{x \to 0} \frac{x^2 + 1}{x - 1}$
2. $\lim_{x \to 2} \frac{1}{x}$
3. $\lim_{x \to 0} \frac{x^2 + 10x}{2x}$
4. $\lim_{x \to \infty} e^{-x}$
5. $\lim_{x \to 0} \frac{\sqrt{1 + x} - \sqrt{1 - x}}{x}$
6. $\lim_{x \to 0} \frac{1 - \cos x}{x}$

## Exercise 3 : Continuity

1. Is the function $y = 1 + |x|$ continuous at the point $x = 0$?
2. Determine the points for which the following function is discontinuous:
   $$
   f(x) = \begin{cases}
   1 & \text{for } 2k \leq x \leq 2k+1 \\
   -1 & \text{for } 2k+1 < x < 2(k+1)
   \end{cases}, \quad k = 0, 1, 2, \ldots
   $$


## Exercise 4 : Series and Finite Sums

Obtain the values of the following sums:

1. $S_5 = \sum_{v=1}^{5} \left(1 + \frac{1}{v}\right)$
2. $S_{10} = \sum_{n=0}^{9} 3 \left(\frac{1}{2}\right)^n$
3. What is the value of the sum $S = \sum_{n=0}^{\infty} \left(\frac{1}{2}\right)^n$?

## Exercise 5 : Secants, Tangents and Differentials

1. Given the curve $y = x^3 - 2x$, calculate the slope of the secant to the curve between the points $x_1 = 1$ and $x_2 = 3/2$. Compare the slope of the secant with that of the tangent at the point $x_1 = 1$.
2. The distance-time law for a particular motion is given by $s(t) = 3t^2 - 8t$ m. Evaluate the velocity at $t = 3$ s.

3. Determine the differential $dy$ of the following functions:

    - $f(x) = x^2 + 7x$
    - $f(x) = x^5 - 2x^4 + 3$
    - $f(x) = 2(x^2 + 3)$

## Exercise 6 : Basic Differentiation Practice

Differentiate with respect to $x$ the following expressions:

1. $3x^5$
2. $8x - 3$
3. $x^{7/3}$
4. $7x^3 - 4x^{3/2}$
5. $\frac{x^3 - 2x}{5x^2}$

## Exercise 7 : Differentiation Rules and Quotients

Obtain the derivatives of the following:

1. $y = 2x^3$
2. $y = \sqrt[3]{x^2}$
3. $y = \frac{1}{x^2}$
4. $y = \frac{2x}{4 + x}$
5. $y = (x^2 + 2)^3$
6. $y = x^4 + \frac{1}{x}$
7. $y = \sqrt{1 + x^2}$
8. $y = \left(a - \frac{b}{x}\right)^3$

## Exercise 8 : Chain Rule and Trigonometric Derivatives

Differentiate:

1. $y = 3\cos(6x)$
2. $y = 4\sin(2\pi x)$
3. $y = Ae^{-x}\sin(2\pi x)$
4. $y = \ln(x + 1)$
5. $y = \sin x \cos x$
6. $y = \sin x^2$
7. $y = (3x^2 + 2)^2$
8. $y = a\sin(bx + c)$


## Exercise 9 : Inverse Trigonometric Derivatives

Differentiate inverse trigonometric functions:

1. $y = \cos^{-1}(cx)$
2. $y = A\tan^{-1}(x + 2)$
3. $y = \sin^{-1}(x^2)$
4. $y = \coth^{-1}(\sqrt{x})$

## Exercise 10 : Hyperbolic Functions

Differentiate hyperbolic trigonometric functions:

1. $y = C\sinh(0.1x)$
2. $u = \pi\tanh(v + 1)$
3. $\eta = \ln(\cosh \xi)$
4. $s = \ln(\cosh t)$
5. $y = \sinh^2 x - \cosh^2 x$
6. $y = 2x\coth x - x^2$

## Exercise 11 : Inverse Hyperbolic Derivatives

Differentiate inverse hyperbolic trigonometric functions:

1. $y = A\sinh^{-1}(10x)$
2. $u = C\coth^{-1}(v + 1)$
3. $\eta = \tanh^{-1}(\sin \xi)$
4. $y = \sinh^{-1}\left(\frac{x - 1}{x}\right)$

## Exercise 12 : Higher Derivatives and Orders

1. $g(\phi) = a\sin\phi + \tan\phi$, required $g'(\phi)$, 1st derivative
2. $v(u) = u e^u$, required $v''(u)$, 2nd derivative
3. $f(x) = \ln x$, required $f''(x)$, 2nd derivative
4. $h(x) = x^5 + 2x^2$, required $h^{(iv)}(x)$, 4th derivative

## Exercise 13 : Zeros and Extrema

Find the zeros and the extreme values for the following functions:

1. $y = 2x^4 - 8x^2$
2. $y = 3 \sin \phi$
3. $y = \sin(0.5x)$
4. $y = 2 + \frac{1}{2}x^3$
5. $y = 2 \cos(\phi + 2)$
6. $y = \frac{2}{3}x^3 - 2x^2 - 6x$

## Exercise 14 : Points of Inflexion

Show that the following functions have a point of inflexion. Calculate the value of the function at such a point.

1. $y = x^3 - 9x^2 + 24x - 7$
2. $y = x^4 - 8x^2$

## Exercise 15 : Curve Sketching

Sketch the following functions:

1. $y = x^2 + \frac{1}{x^3}$
2. $y = \frac{4x + 1}{2x + 3}$
3. $y = \frac{x^2 - 6x + 8}{x^2 - 6x + 5}$

## Exercise 16 : Applications of Differential Calculus

1. A tray in the form of a cube is to be manufactured out of sheet metal. It is to have a cubic capacity of $0.05 \text{ m}^3$. If the tolerance on the linear dimensions is not to exceed $3 \text{ mm}$, calculate the change in the volume and in the area of metal as a percentage.
2. The height of a tower is calculated from its angles of elevation of $35^\circ$ and $28^\circ$, observed at two points $100 \text{ m}$ apart in a horizontal straight line through its base. If the measurement of the larger angle is found to have an error of $0.5^\circ$, what will be the error in the calculated height?

## Exercise 17 : Curvature

Calculate the radius of curvature for the following functions:

1. $y = x^3$ at $x = 1$
2. $y^2 = 10x$ at $x = 2.5$

## Exercise 18 : L'Hôpital's Rule

1. $\lim_{x \to 0} \frac{\sin x}{x}$
2. $\lim_{x \to 0^+} \frac{\ln(1 + 1/x)}{1/x}$
3. $\lim_{x \to +0} x \sin x$
4. $\lim_{x \to 0} \frac{1}{x} \left( \frac{1}{\sinh x} - \frac{1}{\tanh x} \right)$
5. $\lim_{x \to 1} x^{\tan(\pi/2)x}$
6. $\lim_{x \to \infty} \frac{\ln x^3}{\sqrt[3]{x}}$
7. $\lim_{\theta \to 0} \frac{\cos a\theta - \cos b\theta}{\theta^2}$

## Exercise 19 : Implicit Functions

Obtain the derivative $y'$ for the following expressions:

1. $2x^2 + 3y^2 = 5$
2. $3x^3y^2 + x \cos y = 0$
3. $(x + y)^2 + 2x + y = 1$ at $x = 1, y = -1$

## Exercise 20 : Logarithmic Differentiation

Obtain $y'$ for the following expressions:

1. $y = (5x + 2)(3x - 7)$
2. $y = x^{\sin x}$
3. $y = x^x$

## Exercise 21 : Parametric Equations

Obtain $dy/dx$ for the following expressions:

1. $x = ut$ and $y = vt - \frac{1}{2}gt^2$ where $u, v$ and $g$ are constants
2. $x = a(\cos t + t \sin t)$, $y = a(\sin t - t \cos t)$

## Exercise 22 : Circular Motion Parametrisation

A point rotates in the $x-y$ plane with a radius $R$ around the origin of the coordinate system with constant angular velocity. In $2 \text{ s}$ it completes $3$ revolutions. Give the parametric form of the movement.

## Exercise 23 : Parametric Curve Identification

1. The parametric form of a curve is $x(t) = t$, $y(t) = t$, $z(t) = t$. What curve is it?
2. What curve is described by the following equations? $x(t) = a \cos t$, $y(t) = b \sin t$

## Exercise 24 : Kinematics and Vector Derivatives

1. Calculate the acceleration vector if $v_x(t) = -v_0 \sin \omega t$, $v_y(t) = v_0 \cos \omega t$.
2. The position of a point in three-dimensional space is given by $r(t) = (R \cos \omega t, R \sin \omega t, t)$. Calculate the velocity for $t = \frac{2\pi}{\omega}$.
3. The acceleration of a freely falling body is $a = (0, 0, -g)$. Calculate the velocity $v(t)$ if $v(0) = (v_0, 0, 0)$.

## Exercise 25 : Line Integral on a Semicircle

Given the force $\mathbf{F} = \left(\frac{x}{\sqrt{x^2 + y^2}}, \frac{y}{\sqrt{x^2 + y^2}}\right)$, evaluate the line integral along a semicircle around the origin of the coordinate system with radius $R$. Can you give the answer without computing?

## Exercise 26 : Line Integral in 3D

Given a force $\mathbf{F} = (0, -z, y)$, calculate the line integral along the curve $\mathbf{r}(t) = (\sqrt{2}\cos t, \cos 2t, \frac{2t}{\pi})$ from $t = 0$ to $t = \frac{\pi}{2}$.

## Exercise 27 : Taylor Polynomials and Remainder

1. Find the Taylor polynomial of degree 3 about $x=0$ for $f(x)=\ln(1+x)$ and estimate the remainder for $|x|\le 0.5$. 
2. Compute the Taylor series up to order 4 for $e^{2x}$ about $x=0$.

## Exercise 28 : Mean Value Theorem and Rolle

1. State and apply Rolle's theorem to the function $f(x)=x^3-3x$ on $[-2,2]$. 
2. Use the Mean Value Theorem to show there exists $c\in(0,1)$ such that $f'(c)=f(1)-f(0)$ for $f(x)=\sqrt{x+1}$.

## Exercise 29 : Related Rates and Optimization

1. A ladder 5 m long slides down a wall. When the foot is 3 m from the wall, how fast is the top descending? 
2. Find the dimensions of a rectangle of maximum area that can be inscribed under the curve $y=4-x^2$ above the $x$-axis.

## Exercise 30 : Introduction to First-order ODEs

1. Solve the separable differential equation $\frac{dy}{dx}=xy^2$ with $y(0)=1$. 
2. Solve the linear first-order equation $\frac{dy}{dx}+2y=\sin x$.
