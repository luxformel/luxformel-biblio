---
title: "Continuous Functions"
date: 2025-09-07T06:48:04+02:00
# weight: 1
# aliases: ["/first"]
tags: ["Continuity", "Calculus"]
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

# Continuous Functions

## Exercise 1

For which functions $ f $ does there exist a continuous function $ F: \mathbb{R} \to \mathbb{R} $ such that $ F(x) = f(x) $ for all $ x $ in the domain of $ f $?

1. $ f(x) = \frac{x^2 - 4}{x - 2} $

2. $ f(x) = \frac{|x|}{x} $

3. $ f(x) = 0 $ for irrational $ x $

4. $ f(x) = \frac{1}{q} $ for $ x = \frac{p}{q} $ in lowest terms

## Exercise 2

At which points are the following functions continuous?

1. $ f(x) = \begin{cases} 0 & \text{if } x \text{ is irrational} \\ \frac{1}{q} & \text{if } x = \frac{p}{q} \text{ in lowest terms} \end{cases} $

2. $ f(x) = \begin{cases} x & \text{if } x \text{ is rational} \\ 0 & \text{if } x \text{ is irrational} \end{cases} $

## Exercise 3

1. Show that if $ |f(x)| \leq |x| $ for all $ x $, then $ f $ is continuous at 0.

2. Give an example of such a function that is not continuous at any $ a \neq 0 $.

3. Suppose $ g $ is continuous at 0 with $ g(0) = 0 $, and $ |f(x)| \leq |g(x)| $. Prove that $ f $ is continuous at 0.

## Exercise 4

Give an example of a function $ f $ that is continuous nowhere, but $ |f| $ is continuous everywhere.

## Exercise 5

For each real number $ a $, construct a function that is continuous at $ a $ but discontinuous everywhere else.

## Exercise 6

1. Construct a function discontinuous at $ \frac{1}{n} $ for $ n \in \mathbb{N} $, but continuous elsewhere.

2. Construct a function discontinuous at $ 0 $ and $ \frac{1}{n} $ for $ n \in \mathbb{N} $, but continuous elsewhere.

## Exercise 7

Suppose $ f(x + y) = f(x) + f(y) $ for all $ x, y $, and $ f $ is continuous at 0. Prove that $ f $ is continuous everywhere.

## Exercise 8

Suppose $ f $ is continuous at $ a $ with $ f(a) = 0 $, and $ \alpha \neq 0 $. Prove that $ f + \alpha $ is nonzero in some neighborhood of $ a $.

## Exercise 9

1. Suppose $ f $ is defined at $ a $ but not continuous there. Prove there exists $ \varepsilon > 0 $ such that for every $ \delta > 0 $, there is some $ x $ with $ |x - a| < \delta $ and $ |f(x) - f(a)| > \varepsilon $.

2. Conclude that either there exist points arbitrarily close to $ a $ where $ f(x) < f(a) - \varepsilon $, or points where $ f(x) > f(a) + \varepsilon $.

## Exercise 10

1. Prove that if $ f $ is continuous at $ a $, then $ |f| $ is continuous at $ a $.

2. Prove that every continuous function can be written as the sum of an even continuous function and an odd continuous function.

3. Prove that if $ f $ and $ g $ are continuous, then $ \max(f, g) $ and $ \min(f, g) $ are continuous.

4. Prove that every continuous function can be written as the difference of two nonnegative continuous functions.

## Exercise 11

Using the continuity of $ f(x) = \frac{1}{x} $, prove that if $ \lim_{x \to a} g(x) = l \neq 0 $, then $ \lim_{x \to a} \frac{1}{g(x)} = \frac{1}{l} $.

## Exercise 12

1. Prove: if $ \lim_{x \to a} g(x) = l $ and $ f $ is continuous at $ l $, then $ \lim_{x \to a} f(g(x)) = f(l) $.

2. Show by counterexample that this may fail if $ f $ is not continuous at $ l $.

## Exercise 13

1. Prove that if $ f $ is continuous on $[a, b]$, then there exists a continuous function $ g: \mathbb{R} \to \mathbb{R} $ such that $ g(x) = f(x) $ for all $ x \in [a, b] $.

2. Show by counterexample that this fails for $ (a, b) $.

## Exercise 14

1. Suppose $ g $ and $ h $ are continuous at $ a $ with $ g(a) = h(a) $. Define $ f(x) = \begin{cases} g(x) & \text{if } x \geq a \\ h(x) & \text{if } x \leq a \end{cases} $. Prove $ f $ is continuous at $ a $.

2. Suppose $ g $ is continuous on $[a, b]$, $ h $ is continuous on $[b, c]$, and $ g(b) = h(b) $. Define $ f(x) = \begin{cases} g(x) & \text{if } x \in [a, b] \\ h(x) & \text{if } x \in [b, c] \end{cases} $. Prove $ f $ is continuous on $[a, c]$.

## Exercise 15

Prove: if $ f $ is continuous at $ a $, then for every $ \varepsilon > 0 $ there exists $ \delta > 0 $ such that $ |x - a| < \delta $ and $ |y - a| < \delta $ imply $ |f(x) - f(y)| < \varepsilon $.

## Exercise 16

1. Prove: if $ \lim_{x \to a^+} f(x) = f(a) > 0 $, then there exists $ \delta > 0 $ such that $ f(x) > 0 $ for all $ x \in (a, a + \delta) $.

2. State and prove the analogous result for left-hand limits.

## Exercise 17

A function $ f $ has a **removable discontinuity** at $ a $ if $ \lim_{x \to a} f(x) $ exists but is not equal to $ f(a) $.

1. Determine whether the following have removable discontinuities at 0:
   - $ f(x) = \begin{cases} \sin(1/x) & x \neq 0 \\ 1 & x = 0 \end{cases} $
   - $ f(x) = \begin{cases} x\sin(1/x) & x \neq 0 \\ 1 & x = 0 \end{cases} $

2. Suppose $ f $ has a removable discontinuity at $ a $. Define $ g(x) = \begin{cases} f(x) & x \neq a \\ \lim_{x \to a} f(x) & x = a \end{cases} $. Prove $ g $ is continuous at $ a $.

3. Let $ f(x) = \begin{cases} 0 & x \text{ irrational} \\ \frac{1}{q} & x = \frac{p}{q} \text{ in lowest terms} \end{cases} $. Find $ g(x) = \lim_{y \to x} f(y) $.

4. Suppose every discontinuity of $ f $ is removable. Define $ g(x) = \lim_{y \to x} f(y) $. Prove $ g $ is continuous.

5. Does there exist a function that is discontinuous everywhere but has only removable discontinuities?