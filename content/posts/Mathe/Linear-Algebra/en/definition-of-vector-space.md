---
title: "Definition of Vector Space"
date: 2025-09-07T07:07:06+02:00
# weight: 1
# aliases: ["/first"]
tags: ["Linear Algebra", "Vector Spaces" , "Solved"]
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

Léisung zu dësen Exercicer sinn am Archiv op [luxformel](https://luxformel.info/Archiv/Mathe/pdf/) ze fannen. 

# Definition of Vector Space

## Exercise 1: Double Additive Inverse
Prove that $ -(-v) = v $ for every $ v \in V $, where $ V $ is a vector space.

## Exercise 2: Zero Product Property
Suppose $ a \in \mathbb{F} $ (a field), $ v \in V $, and $ av = 0 $. Prove that $ a = 0 $ or $ v = 0 $.

## Exercise 3: Unique Solution to Vector Equation
Suppose $ v, w \in V $. Explain why there exists a unique $ x \in V $ such that $ v + 3x = w $.

## Exercise 4: Alternative Axiom for Additive Inverses
Show that in the definition of a vector space, the additive inverse condition can be replaced with:
$$ 0v = 0 \text{ for all } v \in V $$
(where left 0 $ \in \mathbb{F}$, right 0 $ \in V $).

## Exercise 5: Extended Real Numbers as a Vector Space?

Define **addition** and **scalar multiplication** on $ \mathbb{R}^* = \mathbb{R} \cup \{\infty, -\infty\} $ as follows:

For $ t \in \mathbb{R} $:
$$
t \cdot \infty = 
\begin{cases} 
-\infty & \text{if } t < 0, \\ 
0 & \text{if } t = 0, \\ 
\infty & \text{if } t > 0,
\end{cases}
\quad \quad
t \cdot (-\infty) = \text{(analogous)}
$$

For $ t \in \mathbb{R} $:
$$
t + \infty = \infty + t = \infty, \quad
\infty + \infty = \infty, \quad
\infty + (-\infty) = 0.
$$

Is $ \mathbb{R}^* $ a vector space over $ \mathbb{R} $? Justify.
