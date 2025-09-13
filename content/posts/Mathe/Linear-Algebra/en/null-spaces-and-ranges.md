---
title: "Null Spaces and Ranges"
date: 2025-09-09T08:35:31+02:00
# weight: 1
# aliases: ["/first"]
tags: ["Linear Algebra", "Linear Maps"]
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

# Null Spaces and Ranges

## Exercise 1

Give an example of a linear map \( T \) such that \(\dim \text{null} \, T = 3\) and \(\dim \text{range} \, T = 2\).

## Exercise 2

Suppose \( V \) is a vector space and \( S, T \in \mathcal{L}(V, V) \) are such that  
\[\text{range} \, S \subset \text{null} \, T.\]  
Prove that \((ST)^2 = 0\).

## Exercise 3

Suppose \( v_1, \ldots, v_m \) is a list of vectors in \( V \). Define \( T \in \mathcal{L}(\mathbb{F}^m, V) \) by  
\[T(z_1, \ldots, z_m) = z_1 v_1 + \cdots + z_m v_m.\]  
1. What property of \( T \) corresponds to \( v_1, \ldots, v_m \) spanning \( V \)?  
2. What property of \( T \) corresponds to \( v_1, \ldots, v_m \) being linearly independent?

## Exercise 4

Show that  
\[\{T \in \mathcal{L}(\mathbb{R}^5, \mathbb{R}^4): \dim \text{null} \, T > 2\}\]  
is not a subspace of \(\mathcal{L}(\mathbb{R}^5, \mathbb{R}^4)\).

## Exercise 5

Give an example of a linear map \( T : \mathbb{R}^4 \to \mathbb{R}^4 \) such that  
\[\text{range} \, T = \text{null} \, T.\]

## Exercise 6

Prove that there does not exist a linear map \( T : \mathbb{R}^5 \to \mathbb{R}^5 \) such that  
\[\text{range} \, T = \text{null} \, T.\]

## Exercise 7

Suppose \( V \) and \( W \) are finite-dimensional with \( 2 \leq \dim V \leq \dim W \). Show that \(\{T \in \mathcal{L}(V, W) : T \text{ is not injective}\}\) is not a subspace of \(\mathcal{L}(V, W)\).

## Exercise 8

Suppose \( V \) and \( W \) are finite-dimensional with \(\dim V \geq \dim W \geq 2\). Show that \(\{T \in \mathcal{L}(V, W) : T \text{ is not surjective}\}\) is not a subspace of \(\mathcal{L}(V, W)\).

## Exercise 9

Suppose \( T \in \mathcal{L}(V, W) \) is injective and \( v_1, \ldots, v_n \) is linearly independent in \( V \). Prove that \( T v_1, \ldots, T v_n \) is linearly independent in \( W \).

## Exercise 10

Suppose \( v_1, \ldots, v_n \) spans \( V \) and \( T \in \mathcal{L}(V, W) \). Prove that the list \( Tv_1, \ldots, Tv_n \) spans range \( T \).

## Exercise 11

Suppose \( S_1, \ldots, S_n \) are injective linear maps such that \( S_1S_2 \cdots S_n \) makes sense. Prove that \( S_1S_2 \cdots S_n \) is injective.

## Exercise 12

Suppose that \( V \) is finite-dimensional and that \( T \in \mathcal{L}(V, W) \). Prove that there exists a subspace \( U \) of \( V \) such that \( U \cap \text{null} \, T = \{0\} \) and range \( T = \{Tu : u \in U\} \).

## Exercise 13

Suppose \( T \) is a linear map from \( F^4 \) to \( F^2 \) such that
\[
\text{null} \, T = \{(x_1, x_2, x_3, x_4) \in F^4 : x_1 = 5x_2 \text{ and } x_3 = 7x_4\}.
\]
Prove that \( T \) is surjective.

## Exercise 14

Suppose \( U \) is a 3-dimensional subspace of \( R^8 \) and that \( T \) is a linear map from \( R^8 \) to \( R^5 \) such that \( \text{null} \, T = U \). Prove that \( T \) is surjective.

## Exercise 15

Prove that there does not exist a linear map from \( F^5 \) to \( F^2 \) whose null space equals
\[
\{(x_1, x_2, x_3, x_4, x_5) \in F^5 : x_1 = 3x_2 \text{ and } x_3 = x_4 = x_5\}.
\]

## Exercise 16

Suppose there exists a linear map on \( V \) whose null space and range are both finite-dimensional. Prove that \( V \) is finite-dimensional.

## Exercise 17

Suppose \( V \) and \( W \) are both finite-dimensional. Prove that there exists an injective linear map from \( V \) to \( W \) if and only if \(\dim V \leq \dim W\).

## Exercise 18

Suppose \( V \) and \( W \) are both finite-dimensional. Prove that there exists a surjective linear map from \( V \) onto \( W \) if and only if \(\dim V \geq \dim W\).

## Exercise 19

Suppose \( V \) and \( W \) are finite-dimensional and that \( U \) is a subspace of \( V \). Prove that there exists \( T \in \mathcal{L}(V, W) \) such that \( \text{null} \, T = U \) if and only if \(\dim U \geq \dim V - \dim W\).

## Exercise 20

Suppose \( W \) is finite-dimensional and \( T \in \mathcal{L}(V, W) \). Prove that \( T \) is injective if and only if there exists \( S \in \mathcal{L}(W, V) \) such that \( ST \) is the identity map on \( V \).

## Exercise 21

Suppose \( V \) is finite-dimensional and \( T \in \mathcal{L}(V, W) \). Prove that \( T \) is surjective if and only if there exists \( S \in \mathcal{L}(W, V) \) such that \( TS \) is the identity map on \( W \).

## Exercise 22

Suppose \( U \) and \( V \) are finite-dimensional vector spaces and \( S \in \mathcal{L}(V, W) \) and \( T \in \mathcal{L}(U, V) \). Prove that \[ \dim \text{null} \, ST \leq \dim \text{null} \, S + \dim \text{null} \, T. \]

## Exercise 23

Suppose \( U \) and \( V \) are finite-dimensional vector spaces and \( S \in \mathcal{L}(V, W) \) and \( T \in \mathcal{L}(U, V) \). Prove that \[ \dim \text{range} \, ST \leq \min\{\dim \text{range} \, S, \dim \text{range} \, T\}. \]

## Exercise 24

Suppose \( W \) is finite-dimensional and \( T_1, T_2 \in \mathcal{L}(V, W) \). Prove that \( \text{null} \, T_1 \subset \text{null} \, T_2 \) if and only if there exists \( S \in \mathcal{L}(W, W) \) such that \( T_2 = ST_1 \).

## Exercise 25

Suppose \( V \) is finite-dimensional and \( T_1, T_2 \in \mathcal{L}(V, W) \). Prove that \( \text{range} \, T_1 \subset \text{range} \, T_2 \) if and only if there exists \( S \in \mathcal{L}(V, V) \) such that \( T_1 = T_2S \).

## Exercise 26

Suppose \( D \in \mathcal{L}(\mathcal{P}(\mathbb{R}), \mathcal{P}(\mathbb{R})) \) is such that \( \deg Dp = (\deg p) - 1 \) for every nonconstant polynomial \( p \in \mathcal{P}(\mathbb{R}) \). Prove that \( D \) is surjective.

## Exercise 27

Suppose \( p \in \mathcal{P}(\mathbb{R}) \). Prove that there exists a polynomial \( q \in \mathcal{P}(\mathbb{R}) \) such that \( 5q'' + 3q' = p \). [This exercise can be done without linear algebra, but it's more fun to do it using linear algebra.]

## Exercise 28

Suppose \( T \in \mathcal{L}(V, W) \), and \( w_1, \ldots, w_m \) is a basis of range \( T \). Prove that there exist \( \varphi_1, \ldots, \varphi_m \in \mathcal{L}(V, F) \) such that \[ Tv = \varphi_1(v)w_1 + \cdots + \varphi_m(v)w_m \] for every \( v \in V \).

## Exercise 29

Suppose \( \varphi \in \mathcal{L}(V, F) \). Suppose \( u \in V \) is not in null \( \varphi \). Prove that \[ V = \text{null} \, \varphi \oplus \{au : a \in F\}. \]

## Exercise 30

Suppose \( \varphi_1 \) and \( \varphi_2 \) are linear maps from \( V \) to \( F \) that have the same null space. Show that there exists a constant \( c \in F \) such that \( \varphi_1 = c\varphi_2 \).

## Exercise 31

Give an example of two linear maps \( T_1 \) and \( T_2 \) from \( \mathbb{R}^5 \) to \( \mathbb{R}^2 \) that have the same null space but are such that \( T_1 \) is not a scalar multiple of \( T_2 \).