---
title: "Functions"
date: 2025-09-07T06:44:19+02:00
# weight: 1
# aliases: ["/first"]
tags: ["Functions", "Calculus"]
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
searchHidden: false
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: true
ShowRssButtonInSectionTermList: true
UseHugoToc: true
---

# Functions

## Exercise 1

Let $f(x) = \frac{1}{1 + x}$. Find:

1. $f(f(x))$ and determine its domain

2. $f\left(\frac{1}{x}\right)$

3. $f(cx)$

4. $f(x + y)$

5. $f(x) + f(y)$

6. For which numbers $c$ does there exist $x$ such that $f(cx) = f(x)$?

7. For which numbers $c$ does $f(cx) = f(x)$ hold for two different values of $x$?

## Exercise 2

Let $g(x) = x^2$ and $h(x) = \begin{cases} 0 & \text{if } x \text{ rational} \\ 1 & \text{if } x \text{ irrational} \end{cases}$. Find:

1. All $y$ such that $h(y) \leq y$

2. All $y$ such that $h(y) \leq g(y)$

3. $g(h(z)) - h(z)$

4. All $w$ such that $g(w) \leq w$

5. All $e$ such that $g(g(e)) = g(e)$

## Exercise 3

Find the domain of:

1. $f(x) = \sqrt{1 - x^2}$

2. $f(x) = \sqrt{1 - \sqrt{1 - x^2}}$

3. $f(x) = \frac{1}{x - 1} + \frac{1}{x - 2}$

4. $f(x) = \sqrt{1 - x^2 + \sqrt{x^2 - 1}}$

5. $f(x) = \sqrt{1 - x + \sqrt{x - 2}}$

## Exercise 4

Let $S(x) = x^2$, $P(x) = 2^x$, $s(x) = \sin x$. Evaluate:

1. $(S \circ P)(y)$

2. $(S \circ s)(y)$

3. $(S \circ P \circ s)(t) + (s \circ P)(t)$

4. $s(t^3)$

## Exercise 5

Express using $S$, $P$, $s$, $+$, $\cdot$, and $\circ$:

1. $f(x) = 2^{\sin x}$

2. $f(x) = \sin 2^x$

3. $f(x) = \sin x^2$

4. $f(x) = \sin^2 x$

5. $f(t) = 2^t$

6. $f(u) = \sin(2^u + 2^{u^2})$

7. $f(y) = \sin(\sin(\sin(2^{2^{\sin y}})))$

8. $f(a) = 2^{\sin^2 a} + \sin(a^2) + 2^{\sin(a^2 + \sin a)}$

## Exercise 6

1. Given distinct numbers $x_1, \ldots, x_n$, find a degree $n-1$ polynomial $f_i$ with $f_i(x_i) = 1$ and $f_i(x_j) = 0$ for $j \neq i$

2. Find a degree $n-1$ polynomial $f$ such that $f(x_i) = a_i$ for given numbers $a_1, \ldots, a_n$

## Exercise 7

1. Prove: For any polynomial $f$ and number $a$, there exist polynomial $g$ and number $b$ such that $f(x) = (x - a)g(x) + b$

2. Prove: If $f(a) = 0$, then $f(x) = (x - a)g(x)$ for some polynomial $g$

3. Prove: A degree $n$ polynomial has at most $n$ roots

4. Construct degree $n$ polynomials with: $n$ roots, no roots (if $n$ even), and one root (if $n$ odd)

## Exercise 8

Find conditions on $a, b, c, d$ such that $f(x) = \frac{ax + b}{cx + d}$ satisfies $f(f(x)) = x$ for all valid $x$

## Exercise 9

Let $C_A(x) = \begin{cases} 1 & \text{if } x \in A \\ 0 & \text{if } x \notin A \end{cases}$

1. Express $C_{A \cap B}$, $C_{A \cup B}$, $C_{R-A}$ in terms of $C_A$ and $C_B$

2. Prove: If $f(x) \in \{0,1\}$ for all $x$, then $f = C_A$ for some set $A$

3. Prove: $f = f^2$ if and only if $f = C_A$ for some set $A$

## Exercise 10

1. Characterize functions $f$ for which there exists $g$ with $f = g^2$

2. Characterize functions $f$ for which there exists $g$ with $f = 1/g$

3. Characterize functions $b, c$ for which there exists $x$ satisfying $(x(t))^2 + b(t)x(t) + c(t) = 0$ for all $t$

4. Characterize functions $a, b$ for which there exists $x$ satisfying $a(t)x(t) + b(t) = 0$ for all $t$, and determine how many such $x$ exist

## Exercise 11

1. If $H(H(y)) = y$, find $\underbrace{H(H(\cdots(H(y)\cdots)))}_{80 \text{ times}}$

2. Same as (1) with 81 iterations

3. Same as (1) with $H(H(y)) = H(y)$

4. Find $H$ with $H(H(x)) = H(x)$ and specific values: $H(1) = 36$, $H(2) = \pi/3$, $H(13) = 47$, $H(36) = 36$, $H(\pi/3) = \pi/3$, $H(47) = 47$

5. Find $H$ with $H(H(x)) = H(x)$ and $H(1) = 7$, $H(17) = 18$

## Exercise 12

A function is even if $f(x) = f(-x)$, odd if $f(x) = -f(-x)$

1. Determine parity of $f + g$ for all combinations of even/odd $f$ and $g$

2. Determine parity of $f \cdot g$ for all combinations of even/odd $f$ and $g$

3. Determine parity of $f \circ g$ for all combinations of even/odd $f$ and $g$

4. Prove every even function can be written as $f(x) = g(|x|)$ for infinitely many $g$

## Exercise 13

1. Prove any function $f: \mathbb{R} \to \mathbb{R}$ can be written as $f = E + O$ where $E$ is even and $O$ is odd

2. Prove this decomposition is unique

## Exercise 14

Define $|f|(x) = |f(x)|$, $\max(f, g)(x) = \max(f(x), g(x))$, $\min(f, g)(x) = \min(f(x), g(x))$

Express $\max(f, g)$ and $\min(f, g)$ in terms of $|$

## Exercise 15

1. Show $f = \max(f, 0) + \min(f, 0)$

2. Prove any function can be written as $f = g - h$ where $g, h \geq 0$, in infinitely many ways

## Exercise 16

Suppose $f(x + y) = f(x) + f(y)$ for all $x, y$

1. Prove $f(x_1 + \cdots + x_n) = f(x_1) + \cdots + f(x_n)$

2. Prove there exists $c$ such that $f(x) = cx$ for all rational $x$

## Exercise 17

Suppose $f(x + y) = f(x) + f(y)$ and $f(xy) = f(x)f(y)$ for all $x, y$, with $f$ not identically zero. Prove $f(x) = x$ for all $x$:

1. Prove $f(1) = 1$

2. Prove $f(x) = x$ for rational $x$

3. Prove $f(x) > 0$ for $x > 0$

4. Prove $f(x) > f(y)$ for $x > y$

5. Prove $f(x) = x$ for all $x$

## Exercise 18

Find necessary and sufficient conditions on $f, g, h, k$ such that $f(x)g(y) = h(x)k(y)$ for all $x, y$

## Exercise 19

1. Prove no functions $f, g$ exist satisfying:

   - $f(x) + g(y) = xy$ for all $x, y$
   - $f(x) \cdot g(y) = x + y$ for all $x, y$

2. Find functions $f, g$ such that $f(x + y) = g(xy)$ for all $x, y$

## Exercise 20

1. Find a non-constant function $f$ with $|f(y) - f(x)| \leq |y - x|$

2. Prove: If $f(y) - f(x) \leq (y - x)^2$ for all $x, y$, then $f$ is constant

## Exercise 21

Prove or give counterexample:

1. $f \circ (g + h) = f \circ g + f \circ h$

2. $(g + h) \circ f = g \circ f + h \circ f$

3. $\frac{1}{f \circ g} = \frac{1}{f} \circ g$

4. $\frac{1}{f \circ g} = f \circ \left( \frac{1}{g} \right)$

## Exercise 22

1. Prove: If $g = h \circ f$ and $f(x) = f(y)$, then $g(x) = g(y)$

2. Prove: If $g(x) = g(y)$ whenever $f(x) = f(y)$, then $g = h \circ f$ for some $h$

## Exercise 23

Suppose $f \circ g = I$ where $I(x) = x$. Prove:

1. If $x \neq y$, then $g(x) \neq g(y)$

2. For every $b$, there exists $a$ such that $b = f(a)$

## Exercise 24

1. Prove: If $g(x) \neq g(y)$ for $x \neq y$, then there exists $f$ with $f \circ g = I$

2. Prove: If for every $b$ there exists $a$ with $b = f(a)$, then there exists $g$ with $f \circ g = I$

## Exercise 25

Find $f$ such that $g \circ f = I$ for some $g$, but no $h$ exists with $f \circ h = I$

## Exercise 26

Suppose $f \circ g = I$ and $h \circ f = I$. Prove $g = h$

## Exercise 27

1. For $f(x) = x + 1$, find all $g$ such that $f \circ g = g \circ f$

2. For constant $f$, find all $g$ such that $f \circ g = g \circ f$

3. Prove: If $f \circ g = g \circ f$ for all $g$, then $f(x) = x$