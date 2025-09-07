---
title: "Inverse Functions"
date: 2025-09-07T07:01:15+02:00
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
searchHidden: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: true
ShowRssButtonInSectionTermList: true
UseHugoToc: true
---

# Inverse Functions

## Exercise 1

Find $ f^{-1} $ for each function $ f $

1. $ f(x) = x^3 + 1 $  
2. $ f(x) = (x - 1)^3 $  
3. $ f(x) = \begin{cases} x & \text{rational} \\ -x & \text{irrational} \end{cases} $  
4. $ f(x) = \begin{cases} -x^2 & x \geq 0 \\ 1 - x^3 & x < 0 \end{cases} $  
5. $ f(x) = \begin{cases} x & x \neq a_i \\ a_{i+1} & x = a_i \ (i < n) \\ a_1 & x = a_n \end{cases} $  
6. $ f(x) = x + \lfloor x \rfloor $  
7. $ f(0.a_1a_2a_3\ldots) = 0.a_2a_1a_3\ldots $  
8. $ f(x) = \frac{x}{1 - x^2}, \ -1 < x < 1 $

## Exercise 2

Describe $ f^{-1} $'s graph when $ f $ is:

1. Increasing and positive  
2. Increasing and negative  
3. Decreasing and positive  
4. Decreasing and negative

## Exercise 3 : Monotonicity Preservation

Prove $ f^{-1} $ is increasing when $ f $ is, and decreasing when $ f $ is.

## Exercise 4 : Operations on Increasing Functions

If $ f $ and $ g $ are increasing, are these also increasing?

1. $ f + g $  
2. $ f \cdot g $  
3. $ f \circ g $

## Exercise 5 : Composition and Translation

1. Prove $ f \circ g $ is one-one if $ f $ and $ g $ are, and find $ (f \circ g)^{-1} $
2. Find $ g^{-1} $ if $ g(x) = 1 + f(x) $

## Exercise 6 : Linear Fractional Transformations

Show $ f(x) = \frac{ax+b}{cx+d} $ is one-one iff $ ad-bc \neq 0 $, and find $ f^{-1} $.

## Exercise 7 : One-One Intervals

Find intervals $[a,b]$ where these are one-one:

1. $ f(x) = x^3 - 3x^2 $  
2. $ f(x) = x^5 + x $  
3. $ f(x) = \frac{1}{1+x^2} $  
4. $ f(x) = \frac{x+1}{x^2+1} $

## Exercise 8 : Second Derivative of Inverse

Given $ f'(x) = (1+x^3)^{-1/2} $, show $ g = f^{-1} $ satisfies $ g''(x) = \frac{3}{2}g(x)^2 $.

## Exercise 9 : Differentiability of Inverses

If $ f $ is one-one and $ f^{-1} $ has nowhere-zero derivative, prove $ f $ is differentiable.

## Exercise 10 : Differentiability Condition

What condition on $ g $ ensures $ f $ is differentiable? (Follow-up to 10-17)

## Exercise 11 : Second Derivative Formula

Find a formula for $ (f^{-1})''(x) $.

## Exercise 12 : Higher Derivatives

Prove if $ f'(f^{-1}(x)) \neq 0 $ and $ f^{(k)}(f^{-1}(x)) $ exists, then $ (f^{-1})^{(k)}(x) $ exists.

## Exercise 13 : Schwarzian Derivative

1. Show $ \mathcal{D}f^{-1} $ exists if $ \mathcal{D}f $ exists  
2. Find formula for $ \mathcal{D}f^{-1}(x) $

## Exercise 14 : Implicit Function I

1. Prove $ f $ exists satisfying $ [f(x)]^5 + f(x) + x = 0 $  
2. Find $ f' $ in terms of $ f $  
3. Find $ f' $ via implicit differentiation

## Exercise 15 : Implicit Function II

1. Find two differentiable $ f $ satisfying $ x^2 + [f(x)]^2 = 1 $ on $(-1,1)$  
2. Find $ f $ satisfying $ x^2 + [f(x)]^2 = -1 $  
3. Find differentiable $ f $ satisfying $ [f(x)]^3 - 3f(x) = x $

## Exercise 16 : Implicit Differentiation

1. Apply to $ [f(x)]^2 + x^2 = 1 $  
2. Verify for solutions from 15(a)  
3. Apply to $ [f(x)]^3 - 3f(x) = x $

## Exercise 17 : Higher Implicit Derivatives

1. Find $ f' $ and $ f'' $ for $ x^3 + y^3 = 7 $  
2. For $ f(-1) = 2 $, find $ f'(-1) $ and $ f''(-1) $

## Exercise 18 : Tangent Line

Find tangent to $ 3x^3 + 4x^2y - xy^2 + 2y^3 = 4 $ at $(-1,1)$

## Exercise 19 : Leibniz Notation

Rewrite in prime notation:
1. $ y^4 + y^3 + xy = 1 $
2. $ 4y^3y' + 3y^2y' + y + xy' = 0 $
3. $ y' = \frac{-y}{4y^3 + 3y^2 + x} $

## Exercise 20 : Inverse Function Notation

1. State Theorem 5 in $ dx/dy $ notation  
2. Explain significance of:
\[ \frac{dx^{1/n}}{dx} = \frac{1}{ny^{n-1}} \]

## Exercise 21 : Integral Relationship

For $ f = F' $ and $ G(x) = xf^{-1}(x) - F(f^{-1}(x)) $, prove $ G'(x) = f^{-1}(x) $

## Exercise 22 : Chain Rule Application

Given $ h'(x) = \sin^2(\sin(x+1)) $, $ h(0) = 3 $, find:

1. $ (h^{-1})'(3) $  
2. $ (\beta^{-1})'(3) $ where $ \beta(x) = h(x+1) $

## Exercise 23 : Function Intersections

1. Prove increasing/decreasing functions intersect at most once  
2. Find continuous increasing $ f,g $ intersecting only at integers  
3. Find continuous increasing $ f $ and decreasing $ g $ with no intersection

## Exercise 24 : Involutions

1. Prove continuous $ f = f^{-1} $ has fixed point  
2. Give examples with exactly one fixed point  
3. Prove increasing $ f = f^{-1} \Rightarrow f(x) = x $

## Exercise 25 : Symmetric Graphs

Characterize functions whose graphs remain functions when reflected across $ y = -x $

## Exercise 26 : Monotonicity

1. Prove nondecreasing but not increasing implies constant on some interval  
2. Prove differentiable nondecreasing $ \Rightarrow f' \geq 0 $  
3. Prove $ f' \geq 0 \Rightarrow f $ nondecreasing

## Exercise 27 : Dominated Decreasing Functions

1. Given $ f(x) > 0 $ decreasing, find continuous decreasing $ g $ with $ 0 < g \leq f $  
2. Show we can have $ \lim_{x\to\infty} g(x)/f(x) = 0 $