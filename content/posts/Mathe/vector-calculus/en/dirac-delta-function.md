---
title: "Dirac Delta Function"
date: 2025-12-18T14:58:07+01:00
# weight: 1
# aliases: ["/first"]
tags: ["Vector Calculus", "Dirac", "Functions"]
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

# Dirac Delta Function

## Exercise 1 : Basic Delta Integrals

Evaluate the following integrals:

1. $\displaystyle \int_{2}^{6} (3x^2 - 2x - 1) \, \delta(x - 3) \, dx$
2. $\displaystyle \int_{0}^{5} \cos x \; \delta(x - \pi) \, dx$
3. $\displaystyle \int_{-1}^{3} x^3 \, \delta(x + 1) \, dx$
4. $\displaystyle \int_{-\infty}^{\infty} \ln(x + 3) \, \delta(x + 2) \, dx$
5. $\displaystyle \int_{0}^{\infty} e^{-x} \, \delta(x - 2) \, dx$

## Exercise 2 : Delta with Scaled & Shifted Arguments

Use $\delta(ax) = \frac{1}{|a|}\delta(x)$ and similar properties to evaluate:

1. $\displaystyle \int_{-2}^{2} (2x + 3) \, \delta(3x) \, dx$
2. $\displaystyle \int_{0}^{2} (x^3 + 3x + 2) \, \delta(1 - x) \, dx$
3. $\displaystyle \int_{-1}^{1} 9x^2 \, \delta(3x + 1) \, dx$
4. $\displaystyle \int_{-\infty}^{\infty} f(x) \, \delta(ax - b) \, dx$ for $a \ne 0$ (general formula)
5. $\displaystyle \int_{0}^{4} \sin(\pi x) \, \delta\!\left(x - \frac{1}{2}\right) dx$

## Exercise 3 : Fundamental Properties

Let $\delta(x - b)$ be a Dirac delta centered at $x = b$.

1. $\displaystyle \int_{-\infty}^{\infty} \delta(x - b) \, dx = \;?$
2. If $f(x)$ is continuous at $x = b$, justify the sampling property:
   $\displaystyle \int f(x) \delta(x-b)\,dx = f(b)$ in one sentence.
3. Prove: $\displaystyle x \frac{d\delta(x)}{dx} = -\delta(x)$  
   *Hint: Use integration by parts with test functions.*

## Exercise 4 : Heaviside Step Function Relation

The Heaviside step function is:

$$
\theta(x) = 
\begin{cases} 
1, & x > 0, \\
0, & x \leq 0.
\end{cases}
$$

Show that $\displaystyle \frac{d\theta}{dx} = \delta(x)$, arguing from the fundamental theorem of calculus and the sampling property.

## Exercise 5 : General Composition Rule

Let $f(x)$ be smooth with a simple zero at $x_0$, so $f(x_0) = 0$ but $f'(x_0) \neq 0$. Show:

$$
\delta\big(f(x)\big) = \frac{\delta(x - x_0)}{|f'(x_0)|}.
$$

Use this to re-derive the scaling rule $\delta(ax) = \frac{1}{|a|}\delta(x)$.

## Exercise 6 : 3D Delta Integrals

Evaluate the following 3D integrals over all space, unless specified otherwise:

1. $\displaystyle \int (r^2 + \mathbf{r}\cdot\mathbf{a} + a^2)\, \delta^3(\mathbf{r} - \mathbf{a}) \, d\tau$,  
   where $\mathbf{a}$ is a fixed vector and $a = |\mathbf{a}|$.
2. $\displaystyle \int_V |\mathbf{r} - \mathbf{b}|^2 \, \delta^3(\mathbf{r}) \, d\tau$,  
   with $V$ a cube of side 2 centered on the origin, $\mathbf{b} = 4\hat{y} + 3\hat{z}$.
3. $\displaystyle \int_V \big[r^4 + r^2 (\mathbf{r}\cdot\mathbf{c}) + c^4\big] \delta^3(\mathbf{r} - \mathbf{c}) \, d\tau$,  
   where $V$ is a sphere radius 6 centered at origin, $\mathbf{c} = 5\hat{x}+3\hat{y}+2\hat{z}$, $c = |\mathbf{c}|$.
4. $\displaystyle \int_V (\mathbf{r}\cdot\mathbf{d})\, \delta^3(\mathbf{e} - \mathbf{r}) \, d\tau$,  
   with $\mathbf{d} = (1,2,3)$, $\mathbf{e} = (3,2,1)$, $V$ a sphere radius 1.5 centered at $(2,2,2)$.

## Exercise 7 : Charge Density Expressions

Write an expression for the volume charge density $\rho(\mathbf{r})$ for:

1. A point charge $q$ at $\mathbf{r}'$.
2. An electric dipole: charge $-q$ at origin and $+q$ at $\mathbf{a}$.
3. A uniform spherical shell radius $R$, total charge $Q$, centered at origin (in spherical coordinates).
4. A uniform infinite line charge along the $z$-axis with linear density $\lambda$.

Ensure in each case that $\int \rho \, d\tau$ gives the correct total charge.

## Exercise 8 : Delta Identity from Divergence Theorem

Let $\mathbf{v} = \frac{\hat{\mathbf{r}}}{r^2}$.

1. Compute $\nabla \cdot \mathbf{v}$ for $r \neq 0$.
2. By the divergence theorem, show that $\int_{\mathcal{V}} \nabla \cdot \mathbf{v} \, d\tau = 4\pi$ if $\mathcal{V}$ contains the origin, and 0 otherwise.
3. Conclude that $\nabla \cdot \left( \frac{\hat{\mathbf{r}}}{r^2} \right) = 4\pi \delta^3(\mathbf{r})$.

## Exercise 9 : Application of Delta Divergence Identity

Evaluate:

$$
J = \int_{V} e^{-r} \left[ \nabla \cdot \left( \frac{\hat{\mathbf{r}}}{r^2} \right) \right] d\tau
$$

where $V$ is a sphere of radius $R$ centered at the origin, using:

1. The identity: $\nabla \cdot \left( \frac{\hat{\mathbf{r}}}{r^2} \right) = 4\pi \delta^3(\mathbf{r})$
2. Direct integration with the divergence theorem, treating the origin carefully.

## Exercise 10 : Delta in Different Coordinate Systems

The 3D delta in Cartesian, spherical, and cylindrical coordinates:

Show that $\delta^3(\mathbf{r} - \mathbf{r}') = \frac{\delta(r-r')\,\delta(\theta-\theta')\,\delta(\phi-\phi')}{r^2 \sin\theta}$ in spherical coordinates for $\mathbf{r}' \neq 0$, and explain the geometric origin of the factor $1/(r^2\sin\theta)$.

## Exercise 11 : Delta as Limit of Functions

Verify that

$$
\lim_{\epsilon \to 0} \frac{1}{\sqrt{2\pi\epsilon}} e^{-x^2/(2\epsilon)}
$$

acts as a 1D Dirac delta by checking:

1. Integral over $\mathbb{R}$ is 1 for any $\epsilon>0$,
2. For smooth $f(x)$, $\displaystyle \lim_{\epsilon \to 0} \int f(x) g_\epsilon(x)\,dx = f(0)$.

## Exercise 12 : Fourier Representation of Delta

In quantum mechanics, the identity $\int_{-\infty}^\infty e^{ik(x-x')} dk = 2\pi\, \delta(x-x')$ is used frequently.

1. Relate this to the Fourier representation of the delta function.
2. Use it to evaluate $\int_{-\infty}^\infty \cos(kx)\,dk$ as a distribution.

## Exercise 13 : Advanced Delta Manipulations

1. Compute $\displaystyle \int_{-\infty}^{\infty} \delta'(x) f(x) \, dx$ in terms of $f'(0)$.
2. Verify: $\displaystyle \delta(x^2 - a^2) = \frac{1}{2|a|} \bigl[ \delta(x - a) + \delta(x + a) \bigr]$.
3. Evaluate: $\displaystyle \int_{-\pi}^{\pi} \sin^2 x \; \delta'\!(x) \, dx$.
4. Show: $\displaystyle \frac{d}{dx} \theta(x^2 - 1) = \delta(x - 1) - \delta(x + 1)$.