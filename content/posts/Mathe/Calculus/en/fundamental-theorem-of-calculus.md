---
title: "Fundamental Theorem of Calculus"
date: 2025-09-07T07:02:44+02:00
# weight: 1
# aliases: ["/first"]
tags: ["Calculus"]
categories: ["Mathé"]
author: "Damon"
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
searchHidden: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: true
ShowRssButtonInSectionTermList: true
UseHugoToc: true
---

# Fundamental Theorem of Calculus

## Exercise 1 : Derivatives of Integral Functions

Find $F'(x)$ for each function:

1. $F(x) = \int_a^{x^3} \sin^3 t  dt$

2. $F(x) = \int_3^x \frac{1}{1 + \sin^6 t + t^2} \int_1^t \sin^3 u  du  dt$

3. $F(x) = \int_{15}^x \int_8^y \frac{1}{1 + t^2 + \sin^2 t}  dt  dy$

4. $F(x) = \int_x^b \frac{1}{1 + t^2 + \sin^2 t}  dt$

5. $F(x) = \int_a^b \frac{x}{1 + t^2 + \sin^2 t}  dt$

6. $F(x) = \sin \left( \int_0^x \sin \left( \int_0^y \sin^3 t  dt \right)  dy \right)$

7. $(F^{-1})'(x)$ where $F(x) = \int_1^x \frac{1}{t}  dt$

8. $(F^{-1})'(x)$ where $F(x) = \int_0^x \frac{1}{\sqrt{1 - t^2}}  dt$ (express in terms of $F^{-1}(x)$)

## Exercise 2 : When is $F'(x) = f(x)$?

For each $f$ below, with $F(x) = \int_0^x f$, determine where $F'(x) = f(x)$:

1. $f(x) = \begin{cases} 0 & x \leq 1 \\ 1 & x > 1 \end{cases}$

2. $f(x) = \begin{cases} 0 & x < 1 \\ 1 & x \geq 1 \end{cases}$

3. $f(x) = \begin{cases} 0 & x \neq 1 \\ 1 & x = 1 \end{cases}$

4. $f(x) = \begin{cases} 0 & x \notin \mathbb{Q} \\ 1/q & x = p/q \text{ in lowest terms} \end{cases}$

5. $f(x) = \begin{cases} 0 & x \leq 0 \\ x & x \geq 0 \end{cases}$

6. $f(x) = \begin{cases} 0 & x \leq 0 \text{ or } x > 1 \\ 1/[1/x] & 0 < x \leq 1 \end{cases}$

7. $f(x) = \begin{cases} 1 & x = 1/n, n \in \mathbb{N} \\ 0 & \text{otherwise} \end{cases}$

## Exercise 3 : Constant Expressions

Show these expressions are independent of $x$:

1. $\int_0^x \frac{1}{1 + t^2}  dt + \int_0^{1/x} \frac{1}{1 + t^2}  dt$

2. $\int_{-\cos x}^{\sin x} \frac{1}{\sqrt{1 - t^2}}  dt$ for $x \in (0, \pi/2)$

## Exercise 4 : Inverse Function Derivatives

Find $(f^{-1})'(0)$ for:

1. $f(x) = \int_{0}^{x} (1 + \sin(\sin t))  dt$

2. $f(x) = \int_{1}^{x} \cos(\cos t)  dt$

## Exercise 5 : Finding Functions from Integral Equations

Find $g$ such that:

1. $\int_{0}^{x} tg(t)  dt = x + x^2$

2. $\int_{0}^{x^2} tg(t)  dt = x + x^2$

## Exercise 6 : Functional Equations

1. Find all continuous $f$ satisfying $\int_{0}^{x} f = (f(x))^2 + C$ for $C \neq 0$, assuming $f$ has at most one zero.

2. Find a solution zero on $(-\infty, b]$ ($b > 0$) but non-zero for $x > b$.

3. For $C = 0$, find a solution zero on $[a, b]$ ($a < 0 < b$) but non-zero elsewhere.

## Exercise 7 : Integral Bounds

Prove the following inequalities:

1. $\frac{1}{7\sqrt{2}} \leq \int_{0}^{1} \frac{x^6}{\sqrt{1+x^2}}  dx \leq \frac{1}{7}$  
   (Hint: Bound the integrand appropriately on $[0,1]$)

2. $\frac{3}{8} \leq \int_{0}^{1/2} \sqrt{\frac{1-x}{1+x}}  dx \leq \frac{\sqrt{3}}{4}$  
   (Hint: Find suitable bounds for $\sqrt{\frac{1-x}{1+x}}$ on $[0,1/2]$)

## Exercise 8 : Differentiating Parameterized Integrals

Find $F'(x)$ if $F(x) = \int_{0}^{x} xf(t)  dt$.  
(Hint: First rewrite the integral by factoring out the parameter $x$)

## Exercise 9 : Integration by Parts Identity

Prove that for continuous $f$:
$$\int_{0}^{x} f(u)(x - u)  du = \int_{0}^{x} \left( \int_{0}^{u} f(t)  dt \right)  du$$
by differentiating both sides and showing they satisfy the same differential equation with the same initial condition.

## Exercise 10 : Repeated Integration

Using the result from Exercise 9, prove:
$$\int_{0}^{x} f(u)(x - u)^2  du = 2 \int_{0}^{x} \left( \int_{0}^{u_2} \left( \int_{0}^{u_1} f(t)  dt \right)  du_1 \right)  du_2$$

## Exercise 11 : Antiderivatives

Find $f$ such that $f'''(x) = 1 / \sqrt{1 + \sin^2 x}$.

## Exercise 12 : Periodic Functions

1. If $f$ is periodic with period $a$ and integrable on $[0,a]$, show $\int_{0}^{a} f = \int_{b}^{b+a} f$ for all $b$.

2. Find a function $f$ that is not periodic but whose derivative $f'$ is periodic.

3. If $f'$ is periodic with period $a$ and $f(a) = f(0)$, then $f$ is also periodic with period $a$.

4. If $f'$ is periodic with period $a$ and $f$ is periodic (with some period), then $f(a) = f(0)$.

## Exercise 13 : Basic Integration

Find $\int_{0}^{b} \sqrt{x}  dx$ by finding an antiderivative of $\sqrt{x}$ and applying the Fundamental Theorem of Calculus.

## Exercise 14 : Area Function Properties

Using the Fundamental Theorem of Calculus and properties of continuous functions, show that if $f$ is continuous and $F(x) = \int_a^x f$, then $F$ is differentiable and $F' = f$.

## Exercise 15 : Area Bisection

1. If $C_1$ is the graph of $f(x) = x^2$ ($x \geq 0$) and $C$ is the graph of $f(x) = 2x^2$ ($x \geq 0$), find the curve $C_2$ such that for every point on $C$, the areas between $C$ and $C_1$ and between $C$ and $C_2$ are equal.

2. Generalize: For $C_1: y = x^m$ and $C: y = cx^m$ ($c > 1$), find $C_2$.

## Exercise 16 : Logarithmic Derivatives

1. Find derivatives of $F(x) = \int_{1}^{x} 1/t  dt$ and $G(x) = \int_{b}^{bx} 1/t  dt$.

2. Using these results, prove that $\int_1^a \frac{1}{t} dt + \int_1^b \frac{1}{t} dt = \int_1^{ab} \frac{1}{t} dt$.

## Exercise 17 : Intermediate Value Theorem

Using the Fundamental Theorem of Calculus and the fact that derivatives have the intermediate value property (Darboux's Theorem), prove that if $f$ is continuous on $[a,b]$, then $f$ takes every value between $f(a)$ and $f(b)$.

## Exercise 18 : General FTC Formula

Prove that if $h$ is continuous and $f,g$ differentiable, then for
$$F(x) = \int_{f(x)}^{g(x)} h(t)  dt$$
we have $F'(x) = h(g(x))g'(x) - h(f(x))f'(x)$.

## Exercise 19 : Differentiability of Integral Functions

For $f$ integrable on $[a,b]$, $c \in (a,b)$, and $F(x) = \int_{a}^{x} f$:

1. If $f$ differentiable at $c$, is $F$ differentiable at $c$?

2. If $f$ differentiable at $c$, is $F'$ continuous at $c$?

3. If $f'$ continuous at $c$, is $F'$ continuous at $c$?
Give proofs or counterexamples.

## Exercise 20 : Differentiability at Singularity

For $f(x) = \begin{cases} \cos(1/x) & x \neq 0 \\ 0 & x = 0 \end{cases}$, is $F(x) = \int_0^x f$ differentiable at $0$?

## Exercise 21 : Integral Inequality

If $f'$ is integrable on $[0,1]$ and $f(0) = 0$, prove:
$$|f(x)| \leq \sqrt{\int_0^1 |f'|^2} \quad \text{for all } x \in [0,1]$$
Show the hypothesis $f(0) = 0$ is necessary.

## Exercise 22 : Integral Comparison

If $f$ differentiable with $f(0) = 0$ and $0 < f' \leq 1$, prove for $x \geq 0$:
$$\int_0^x f^3 \leq \left( \int_0^x f \right)^2$$

## Exercise 23 : Differential Equations

1. If $G' = g$, $F' = f$, and $g(y(x))y'(x) = f(x)$, show $G(y(x)) = F(x) + c$  

2. Conversely, show this implies the differential equation  

3. Solve $y'(x) = \frac{1 + x^2}{1 + y(x)}$ 

4. Solve $y'(x) = \frac{-1}{1 + 5[y(x)]^4}$ 

5. Find all $y$ satisfying $y(x)y'(x) = -x$, and the solution with $y(0) = -1$

## Exercise 24 : Schwarzian Derivative

If $f$ has Schwarzian derivative $\frac{f'''(x)}{f'(x)} - \frac{3}{2} \left( \frac{f''(x)}{f'(x)} \right)^2 = 0$:

1. Show $f''^2/f'^3$ is constant

2. Prove $f(x) = (ax + b)/(cx + d)$

## Exercise 25 : Improper Integrals at Infinity

1. Determine $\int_1^\infty x^r dx$ for $r < -1$

2. Show $\int_1^\infty 1/x dx$ diverges by considering $\int_1^{2^n} 1/x dx$

3. If $0 \leq g(x) \leq f(x)$ and $\int_0^\infty f$ exists, prove $\int_0^\infty g$ exists

4. Explain why $\int_0^\infty 1/(1 + x^2) dx$ exists by splitting at $x = 1$

## Exercise 26 : Convergence Tests

Determine whether these improper integrals converge:

1. $\int_0^\infty \frac{1}{\sqrt{1 + x^3}} dx$

2. $\int_0^\infty \frac{x}{1 + x^{3/2}} dx$

3. $\int_0^\infty \frac{1}{x\sqrt{1 + x}} dx$

## Exercise 27 : Two-Sided Improper Integrals

1. Explain why $\int_{-\infty}^\infty 1/(1 + x^2) dx$ exists

2. Explain why $\int_{-\infty}^\infty x dx$ does not exist (even though $\lim_{N \to \infty} \int_{-N}^N x dx$ exists)

3. If $\int_{-\infty}^\infty f$ exists, show $\lim_{N \to \infty} \int_{-N}^N f = \int_{-\infty}^\infty f$

## Exercise 28 : Unbounded Integrands

1. Find $\int_0^1 1/\sqrt{x}  dx$ as $\lim_{a \to 0^+} \int_a^1 1/\sqrt{x}  dx$

2. Find $\int_0^1 x^r  dx$ for $-1 < r < 0$

3. Show $\int_0^1 x^{-1}  dx$ diverges

4. Define $\int_a^0 |x|^r  dx$ for $a < 0$, $-1 < r < 0$ and compute it

5. Define $\int_{-1}^1 (1 - x^2)^{-1/2}  dx$ as a sum of limits and show convergence

## Exercise 29 : Limit Problems

1. If $f$ continuous on $[0,1]$, compute $\lim_{x \to 0^+} x \int_x^1 \frac{f(t)}{t}  dt$

2. If $f$ integrable on $[0,1]$ and continuous at $0$, compute $\lim_{x \to 0^+} x \int_x^1 \frac{f(t)}{t^2}  dt$

## Exercise 30 : Combined Singularities

1. For $f(x) = \begin{cases} 1/\sqrt{x} & 0 \leq x \leq 1 \\ 1/x^2 & x \geq 1 \end{cases}$, define and compute $\int_0^\infty f(x)  dx$

2. Show $\int_0^\infty x^r  dx$ never converges for any $r$