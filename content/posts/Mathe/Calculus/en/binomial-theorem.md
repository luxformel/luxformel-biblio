---
title: "Binomial Theorem"
date: 2025-09-07T06:54:19+02:00
# weight: 1
# aliases: ["/first"]
tags: ["Binomial Theorem"]
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

# Binomial Theorem

## Exercise 1 : Expansion  

Expand using the binomial formula: 

1. $ (x + y)^4 $  
2. $ (2a - b)^5 $  
3. $ \left( \frac{1}{x} + x \right)^3 $  

## Exercise 2 : Coefficients  

Find the specified coefficient: 

1. Coefficient of $ x^3 $ in $ (1 + x)^8 $
2. Coefficient of $ a^4b^2 $ in $ (2a - 3b)^6 $
3. Coefficient of $ x^{-2} $ in $ \left( x - \frac{1}{x} \right)^{10} $  

## Exercise 3 : Identities

Prove the following identities using the binomial theorem:  

1. $ \sum_{k=0}^n \binom{n}{k} = 2^n $  
2. $ \sum_{k=0}^n (-1)^k \binom{n}{k} = 0 $ for $ n \geq 1 $ 


## Exercise 4 : General Term 

1. Find the term independent of $ x $ in $ \left( x + \frac{1}{x^2} \right)^9 $.  
2. Determine the middle term(s) in $ \left( 3x - \frac{y}{2} \right)^{10} $.  

## Exercise 5 : Approximations 

1. Approximate $ (1.01)^5 $ using the binomial theorem.  
2. Estimate $ (0.98)^6 $ to 4 decimal places.  

## Exercise 6 : Divisibility 

Prove that for all $ n \in \mathbb{N} $: 

1. $ 5^{2n+1} + 3^{n+2} \cdot 2^{n-1} $ is divisible by 19.  
2. $ 4^n + 15n - 1 $ is divisible by 9.  

## Exercise 7 : Series Manipulation  

1. Show that $ \sum_{k=1}^n k \binom{n}{k} = n \cdot 2^{n-1} $.  
2. Evaluate $ \sum_{k=0}^n \binom{n}{k} \frac{1}{k+1} $.  

## Exercise 8 : Multinomials 

1. Find the coefficient of $ x^3y^2z $ in $ (x + y + z)^6 $.  
2. Expand $ (1 + x + x^2)^3 $ using multinomial coefficients.  

## Exercise 9 : Irrational Powers  

For $ |x| < 1 $, use the generalized binomial theorem to:  

1. Expand $ \sqrt{1 + x} $ up to $ x^3 $  
2. Find the first 4 terms of $ (1 - x)^{-1/2} $  

## Exercise 10 : Combinatorial Proofs  

1. Prove **Vandermonde's Identity**:  
   $$ \sum_{k=0}^r \binom{m}{k} \binom{n}{r-k} = \binom{m+n}{r} $$  
2. Derive the identity:  
   $$ \sum_{k=0}^n \binom{n}{k}^2 = \binom{2n}{n} $$ 

## Exercise 11 : Non-Integer Exponents 

Show that for $ |x| < 1 $ and $ \alpha \in \mathbb{R} $:  
   $$ (1 + x)^\alpha = \sum_{k=0}^\infty \binom{\alpha}{k} x^k $$  
   where $ \binom{\alpha}{k} = \frac{\alpha(\alpha-1)\cdots(\alpha-k+1)}{k!} $  

## Exercise 12 : Functional Equations  

Find all functions $ f: \mathbb{R} \to \mathbb{R} $ satisfying:  
   $$ f(x+y) = \sum_{k=0}^n \binom{n}{k} f^{(k)}(x) y^k $$  
   where $ f^{(k)} $ denotes the $ k $-th derivative.  

## Exercise 13 : Asymptotics 

Using Stirling’s approximation ($ n! \approx \sqrt{2\pi n} (n/e)^n $), estimate $ \binom{2n}{n} $ for large $ n $.  

## Exercise 14 : Number Theory 

1. Prove that for a prime $ p $, $ \binom{p}{k} \equiv 0 \pmod{p} $ for $ 1 \leq k \leq p-1 $.  
2. Show that $ \binom{2p}{p} \equiv 2 \pmod{p^2} $ for prime $ p \geq 5 $.  

## Exercise 15 : Generating Functions

1. Prove that the generating function for the sequence $ \binom{n}{0}, \binom{n}{1}, \dots, \binom{n}{n} $ is $ (1 + x)^n $.  
2. Use generating functions to evaluate $ \sum_{k=0}^n \binom{n}{k}^3 $.  

## Exercise 16 : Inequalities  

1. Show that for $ n \geq 1 $, $ \binom{2n}{n} \geq \frac{4^n}{2n+1} $.  
2. Prove **Chernoff’s bound**: For $ 0 \leq p \leq 1 $ and $ X \sim \text{Binomial}(n, p) $,  
   $$ P(X \geq (1+\delta)np) \leq \left( \frac{e^\delta}{(1+\delta)^{1+\delta}} \right)^{np} $$ 

## Exercise 17 : Complex Analysis 

Using contour integration, evaluate:  
   $$ \sum_{k=0}^n \binom{n}{k} \frac{(-1)^k}{k + 1/2} $$ 

## Exercise 18 : Probability 

Let $ X \sim \text{Binomial}(n, p) $. Compute $ E\left[ \frac{1}{1 + X} \right] $ exactly.  
