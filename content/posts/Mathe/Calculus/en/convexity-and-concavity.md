---
title: "Convexity and Concavity"
date: 2025-09-07T06:52:52+02:00
# weight: 1
# aliases: ["/first"]
tags: ["Convexity", "Concavity", "Calculus"]
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

# Convexity and Concavity 

## Exercise 1

Show that a function $ f $ is convex on an interval if and only if for all $ x, y $ in the interval and $ 0 < t < 1 $, we have:
$$ f(tx + (1 - t)y) \leq tf(x) + (1 - t)f(y). $$

## Exercise 2

Let $ f $ and $ g $ be convex functions with $ f $ increasing.

1. Prove $ f \circ g $ is convex.

2. Provide an example where $ g \circ f $ is not convex.

3. Give an alternative proof of 1. using second derivatives (assume twice differentiability).

## Exercise 3

1. Show that if $ f $ is differentiable and convex on an interval, then either:

   - $ f $ is increasing, or

   - $ f $ is decreasing, or 

   - $ \exists c $ such that $ f $ decreases on $ (-\infty, c] $ and increases on $ [c, \infty) $.

2. Prove 1. without differentiability. Show:
   - If $ a < b $ and $ f(a) < f(b) $, then $ f $ increases on $ [b, \infty) $
   - If $ f(a) > f(b) $, then $ f $ decreases on $ (-\infty, a] $

## Exercise 4

Let $ f $ be twice-differentiable with:

- $ f(x) > 0 $ for $ x \geq 0 $

- $ f $ is decreasing

- $ f'(0) = 0 $

Prove $ f''(x) = 0 $ for some $ x > 0 $. Show all hypotheses are necessary using counterexamples:

- $ f(x) = 1 - x^2 $ (not positive)

- $ f(x) = x^2 $ (not decreasing)  

- $ f(x) = 1/(x + 1) $ ($ f'(0) \neq 0 $)

*Hint: Choose $ x_0 > 0 $ with $ f'(x_0) < 0 $. Show $ f'(y) \not\leq f'(x_0) $ for all $ y > x_0 $, so $ \exists x_1 > x_0 $ with $ f'(x_1) > f'(x_0) $. Apply MVT on $[0, x_1]$.*

## Exercise 5

1. Prove that if $ f $ is convex, then $ f\left(\frac{x + y}{2}\right) \leq \frac{f(x) + f(y)}{2} $.

2. Suppose $ f $ satisfies the midpoint convexity condition in 1. Show it holds for all dyadic rationals $ k = m/2^n \in (0,1) $ (use induction).

3. Prove that if $ f $ is continuous and midpoint convex, then $ f $ is convex.

## Exercise 6

Let $ p_1, \ldots, p_n > 0 $ with $ \sum p_i = 1 $.

1. Show $ \sum p_i x_i $ lies between $ \min x_i $ and $ \max x_i $.

2. Show the same for $ \frac{1}{t} \sum_{i=1}^{n-1} p_i x_i $ where $ t = \sum_{i=1}^{n-1} p_i $.

3. Prove Jensen's inequality: If $ f $ is convex, then
   $$ f\left(\sum p_i x_i\right) \leq \sum p_i f(x_i). $$

## Exercise 7

1. For convex $ f $, define the right and left derivatives:
   $$ f_+'(a) = \lim_{h \to 0^+} \frac{f(a+h) - f(a)}{h}, \quad f_-'(a) = \lim_{h \to 0^-} \frac{f(a+h) - f(a)}{h} $$
   Show both exist, are increasing, and $ f_-'(a) \leq f_+'(a) $.

2. Let $ f $ be convex on $[a,b]$, $ g $ convex on $[b,c]$, with $ f(b) = g(b) $ and $ f_-'(b) \leq g_+'(b) $. Define:
   $$ h(x) = \begin{cases} f(x) & x \in [a,b] \\ g(x) & x \in [b,c] \end{cases} $$
   Show $ h $ is convex on $[a,c]$.

3. Show $ f_+'(a) = f_-'(a) $ if and only if $ f_+' $ is continuous at $ a $.

## Exercise 8

1. Prove every convex function on an open interval is continuous.

2. Construct a convex function on a closed interval that is not continuous, and characterize the possible discontinuities.

## Exercise 9

A function $ f $ is _weakly convex_ if for $ a < x < b $:
$$ \frac{f(x) - f(a)}{x - a} \leq \frac{f(b) - f(a)}{b - a}. $$

1. Show $ f $ is convex if and only if it's weakly convex with no straight-line segments in its graph.

2. Reformulate the previous exercises for weakly convex functions.

## Exercise 10

Find convex functions $ f $ and $ g $ such that $ f(x) = g(x) $ if and only if $ x \in \mathbb{Z} $.

## Exercise 11

For a function $ f $, define the epigraph:
$$ A_f = \{(x, y) : y \geq f(x)\}. $$
Show $ A_f $ is convex if and only if $ f $ is weakly convex.