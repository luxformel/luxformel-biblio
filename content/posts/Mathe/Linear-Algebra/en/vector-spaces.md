---
title: "Vector Spaces"
date: 2025-09-08T03:11:30+02:00
# weight: 1
# aliases: ["/first"]
tags: ["Linear Algebra", "Vector Spaces"]
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

# Vector Spaces

## Exercise 1

For each of the following subsets of $\mathbb{F}^3$, determine whether it is a subspace of $\mathbb{F}^3$:

1. $\{(x_1, x_2, x_3) \in \mathbb{F}^3 : x_1 + 2x_2 + 3x_3 = 0\}$

2. $\{(x_1, x_2, x_3) \in \mathbb{F}^3 : x_1 + 2x_2 + 3x_3 = 4\}$

3. $\{(x_1, x_2, x_3) \in \mathbb{F}^3 : x_1 x_2 x_3 = 0\}$

4. $\{(x_1, x_2, x_3) \in \mathbb{F}^3 : x_1 = 5x_3\}$

## Exercise 2

Show that the set of differentiable real-valued functions $f$ on the interval $(-4, 4)$ such that $f'( -1) = 3f(2)$ is a subspace of $\mathbb{R}^{(-4, 4)}$.

## Exercise 3

Suppose $b \in \mathbb{R}$. Show that the set of continuous real-valued functions $f$ on the interval $[0, 1]$ such that $\int_0^1 f = b$ is a subspace of $\mathbb{R}^{[0, 1]}$ if and only if $b = 0$.

## Exercise 4

Verify all the assertions:

1. If $b \in \mathbb{F}$, then

   $$\{(x_1, x_2, x_3, x_4) \in \mathbb{F}^4 : x_3 = 5x_4 + b\}$$

   is a subspace of $\mathbb{F}^4$ if and only if $b = 0$.

2. The set of continuous real-valued functions on the interval $[0, 1]$ is a subspace of $\mathbb{R}^{[0, 1]}$.

3. The set of differentiable real-valued functions on $\mathbb{R}$ is a subspace of $\mathbb{R}^{\mathbb{R}}$.

4. The set of differentiable real-valued functions $f$ on the interval $(0, 3)$ such that $f'(2) = b$ is a subspace of $\mathbb{R}^{(0, 3)}$ if and only if $b = 0$.

5. The set of all sequences of complex numbers with limit 0 is a subspace of $\mathbb{C}^\infty$.

## Exercise 5

Is $\mathbb{R}^2$ a subspace of the complex vector space $\mathbb{C}^2$?

## Exercise 6

1. Is $\{(a, b, c) \in \mathbb{R}^3 : a^3 = b^3\}$ a subspace of $\mathbb{R}^3$?

2. Is $\{(a, b, c) \in \mathbb{C}^3 : a^3 = b^3\}$ a subspace of $\mathbb{C}^3$?

## Exercise 7

Give an example of a nonempty subset $U$ of $\mathbb{R}^2$ such that $U$ is closed under addition and under taking additive inverses (meaning $-u \in U$ whenever $u \in U$), but $U$ is not a subspace of $\mathbb{R}^2$.

## Exercise 8

Give an example of a nonempty subset $U$ of $\mathbb{R}^2$ such that $U$ is closed under scalar multiplication, but $U$ is not a subspace of $\mathbb{R}^2$.

## Exercise 9

A function $f : \mathbb{R} \to \mathbb{R}$ is called periodic if there exists a positive number $p$ such that $f(x) = f(x + p)$ for all $x \in \mathbb{R}$. Is the set of periodic functions from $\mathbb{R}$ to $\mathbb{R}$ a subspace of $\mathbb{R}^{\mathbb{R}}$? Explain.

## Exercise 10

Suppose $U_1$ and $U_2$ are subspaces of $V$. Prove that the intersection $U_1 \cap U_2$ is a subspace of $V$.

## Exercise 11

Prove that the intersection of every collection of subspaces of $V$ is a subspace of $V$.

## Exercise 12

Prove that the union of two subspaces of $V$ is a subspace of $V$ if and only if one of the subspaces is contained in the other.

## Exercise 13

Prove that the union of three subspaces of $V$ is a subspace of $V$ if and only if one of the subspaces contains the other two.

## Exercise 14

Verify the assertion:

Suppose that $U = \{(x, x, y, y) \in \mathbb{F}^4 : x, y \in \mathbb{F}\}$ and $W = \{(x, x, x, y) \in \mathbb{F}^4 : x, y \in \mathbb{F}\}$. Then

$$U + W = \{(x, x, y, z) \in \mathbb{F}^4 : x, y, z \in \mathbb{F}\}.$$


## Exercise 15

Suppose $U$ is a subspace of $V$. What is $U + U$?

## Exercise 16

Is the operation of addition on the subspaces of $V$ commutative? In other words, if $U$ and $W$ are subspaces of $V$, is $U + W = W + U$?

## Exercise 17

Is the operation of addition on the subspaces of $V$ associative? In other words, if $U_1, U_2, U_3$ are subspaces of $V$, is
$$(U_1 + U_2) + U_3 = U_1 + (U_2 + U_3)?$$

## Exercise 18

Does the operation of addition on the subspaces of $V$ have an additive identity? Which subspaces have additive inverses?

## Exercise 19

Prove or give a counterexample: if $U_1, U_2, W$ are subspaces of $V$ such that
$$U_1 + W = U_2 + W,$$
then $U_1 = U_2$.

## Exercise 20

Suppose
$$U = \{(x, x, y, y) \in \mathbb{F}^4 : x, y \in \mathbb{F}\}.$$
Find a subspace $W$ of $\mathbb{F}^4$ such that $\mathbb{F}^4 = U \oplus W$.

## Exercise 21

Suppose
$$U = \{(x, y, x + y, x - y, 2x) \in F^5 : x, y \in F\}.$$
Find a subspace $W$ of $F^5$ such that $F^5 = U \oplus W$.

## Exercise 22

Suppose
$$U = \{(x, y, x + y, x - y, 2x) \in F^5 : x, y \in F\}.$$
Find three subspaces $W_1, W_2, W_3$ of $F^5$, none of which equals $\{0\}$, such that $F^5 = U \oplus W_1 \oplus W_2 \oplus W_3$.

## Exercise 23

Prove or give a counterexample: if $U_1, U_2, W$ are subspaces of $V$ such that
$$V = U_1 \oplus W \quad \text{and} \quad V = U_2 \oplus W,$$
then $U_1 = U_2$.

## Exercise 24

A function $f : R \to R$ is called even if
$$f(-x) = f(x)$$
for all $x \in R$. A function $f : R \to R$ is called odd if
$$f(-x) = -f(x)$$
for all $x \in R$. Let $U_e$ denote the set of real-valued even functions on $R$ and let $U_o$ denote the set of real-valued odd functions on $R$. Show that
$$R^R = U_e \oplus U_o.$$

