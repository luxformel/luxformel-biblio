---
title: "Span and Linear Independence"
date: 2025-09-08T04:12:27+02:00
# weight: 1
# aliases: ["/first"]
tags: ["Linear Algebra", "Span", "Linear Independence"]
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

# Span and Linear Independence

## Exercise 1

Suppose $v_1, v_2, v_3, v_4$ spans $V$. Prove that the list  
$$v_1 - v_2, v_2 - v_3, v_3 - v_4, v_4$$  
also spans $V$.

## Exercise 2

Verify the assertions:

1. A list $v$ of one vector $v \in V$ is linearly independent if and only if $v \neq 0$.

2. A list of two vectors in $V$ is linearly independent if and only if neither vector is a scalar multiple of the other.

3. $(1, 0, 0, 0), (0, 1, 0, 0), (0, 0, 1, 0)$ is linearly independent in $F^4$.

4. The list $1, z, \ldots, z^m$ is linearly independent in $\mathcal{P}(F)$ for each nonnegative integer $m$.

## Exercise 3

Find a number $t$ such that  
$$ (3, 1, 4), (2, -3, 5), (5, 9, t) $$  
is not linearly independent in $\mathbb{R}^3$.

## Exercise 4

Verify the assertion:

The list $(2, 3, 1), (1, -1, 2), (7, 3, c)$ is linearly dependent in $\mathbb{F}^3$ if and only if $c = 8$.

## Exercise 5

1. Show that if we think of $C$ as a vector space over $\mathbb{R}$, then the list  
$$ (1 + i, 1 - i) $$  
is linearly independent.  

2. Show that if we think of $C$ as a vector space over $C$, then the list  
$$ (1 + i, 1 - i) $$  
is linearly dependent.

## Exercise 6

Suppose $v_1, v_2, v_3, v_4$ is linearly independent in $V$. Prove that the list  
$$v_1 - v_2, v_2 - v_3, v_3 - v_4, v_4$$  
is also linearly independent.

## Exercise 7

Prove or give a counterexample: If $v_1, v_2, \ldots, v_m$ is a linearly independent list of vectors in $V$, then  
$$5v_1 - 4v_2, v_2, v_3, \ldots, v_m$$  
is linearly independent.

## Exercise 8

Prove or give a counterexample: If $v_1, v_2, \ldots, v_m$ is a linearly independent list of vectors in $V$ and $\lambda \in \mathbb{F}$ with $\lambda \neq 0$, then $\lambda v_1, \lambda v_2, \ldots, \lambda v_m$ is linearly independent.

## Exercise 9

Prove or give a counterexample: If $v_1, \ldots, v_m$ and $w_1, \ldots, w_m$ are linearly independent lists of vectors in $V$, then $v_1 + w_1, \ldots, v_m + w_m$ is linearly independent.

## Exercise 10

Suppose $v_1, \ldots, v_m$ is linearly independent in $V$ and $w \in V$. Prove that if $v_1 + w, \ldots, v_m + w$ is linearly dependent, then $w \in \text{span}(v_1, \ldots, v_m)$.

## Exercise 11

Suppose $v_1, \ldots, v_m$ is linearly independent in $V$ and $w \in V$. Show that $v_1, \ldots, v_m, w$ is linearly independent if and only if  
$$w \notin \text{span}(v_1, \ldots, v_m).$$

## Exercise 12

Explain why there does not exist a list of six polynomials that is linearly independent in $P_4(\mathbb{F})$.

## Exercise 13

Explain why no list of four polynomials spans $P_4(\mathbb{F})$.

## Exercise 14

Prove that $V$ is infinite-dimensional if and only if there is a sequence $v_1, v_2, \ldots$ of vectors in $V$ such that $v_1, \ldots, v_m$ is linearly independent for every positive integer $m$.

## Exercise 15

Prove that $\mathbb{F}^{\infty}$ is infinite-dimensional.

## Exercise 16

Prove that the real vector space of all continuous real-valued functions on the interval $[0, 1]$ is infinite-dimensional.

## Exercise 17

Suppose $p_0, p_1, \ldots, p_m$ are polynomials in $P_m(\mathbb{F})$ such that $p_j(2) = 0$ for each $j$. Prove that $p_0, p_1, \ldots, p_m$ is not linearly independent in $P_m(\mathbb{F})$.