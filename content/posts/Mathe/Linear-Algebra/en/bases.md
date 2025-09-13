---
title: "Bases"
date: 2025-09-09T08:00:40+02:00
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

# Bases

## Exercise 1

Find all vector spaces that have exactly one basis.

## Exercise 2

Verify all the assertions:

1. The list \((1,0,\ldots,0), (0,1,0,\ldots,0), \ldots, (0,\ldots,0,1)\) is a basis of \(\mathbb{F}^n\), called the **standard basis** of \(\mathbb{F}^n\).

2. The list \((1,2), (3,5)\) is a basis of \(\mathbb{F}^2\).

3. The list \((1,2,-4), (7,-5,6)\) is linearly independent in \(\mathbb{F}^3\) but is not a basis of \(\mathbb{F}^3\) because it does not span \(\mathbb{F}^3\).

4. The list \((1,2), (3,5), (4,13)\) spans \(\mathbb{F}^2\) but is not a basis of \(\mathbb{F}^2\) because it is not linearly independent.

5. The list \((1,1,0), (0,0,1)\) is a basis of \(\{(x,x,y) \in \mathbb{F}^3 : x,y \in \mathbb{F}\}\).

6. The list \((1,-1,0), (1,0,-1)\) is a basis of
   \[\{(x,y,z) \in \mathbb{F}^3 : x+y+z=0\}.\]

7. The list \(1, z, \ldots, z^m\) is a basis of \(\mathcal{P}_m(\mathbb{F})\).

## Exercise 3

1. Let \( U \) be the subspace of \( \mathbb{R}^5 \) defined by  
   \[U = \{(x_1, x_2, x_3, x_4, x_5) \in \mathbb{R}^5 : x_1 = 3x_2 \text{ and } x_3 = 7x_4\}.\]  
   Find a basis of \( U \).

2. Extend the basis in part (a) to a basis of \( \mathbb{R}^5 \).

3. Find a subspace \( W \) of \( \mathbb{R}^5 \) such that \( \mathbb{R}^5 = U \oplus W \).

## Exercise 4

1. Let \( U \) be the subspace of \( \mathbb{C}^5 \) defined by  
   \[U = \{(z_1, z_2, z_3, z_4, z_5) \in \mathbb{C}^5 : 6z_1 = z_2 \text{ and } z_3 + 2z_4 + 3z_5 = 0\}.\]  
   Find a basis of \( U \).

2. Extend the basis in part (a) to a basis of \( \mathbb{C}^5 \).

3. Find a subspace \( W \) of \( \mathbb{C}^5 \) such that \( \mathbb{C}^5 = U \oplus W \).

## Exercise 5

Prove or disprove: there exists a basis \( p_0, p_1, p_2, p_3 \) of \( P_3(\mathbb{F}) \) such that none of the polynomials \( p_0, p_1, p_2, p_3 \) has degree 2.

## Exercise 6

Suppose \( v_1, v_2, v_3, v_4 \) is a basis of \( V \). Prove that  
\[v_1 + v_2, v_2 + v_3, v_3 + v_4, v_4\]  
is also a basis of \( V \).

## Exercise 7

Prove or give a counterexample: If \( v_1, v_2, v_3, v_4 \) is a basis of \( V \) and \( U \) is a subspace of \( V \) such that \( v_1, v_2 \in U \) and \( v_3 \notin U \) and \( v_4 \notin U \), then \( v_1, v_2 \) is a basis of \( U \).

## Exercise 8

Suppose \( U \) and \( W \) are subspaces of \( V \) such that \( V = U \oplus W \). Suppose also that \( u_1, \ldots, u_m \) is a basis of \( U \) and \( w_1, \ldots, w_n \) is a basis of \( W \). Prove that  
\[u_1, \ldots, u_m, w_1, \ldots, w_n\]  
is a basis of \( V \).
