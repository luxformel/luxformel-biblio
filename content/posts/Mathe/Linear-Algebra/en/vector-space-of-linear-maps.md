---
title: "Vector Space of Linear Maps"
date: 2025-09-09T08:25:21+02:00
# weight: 1
# aliases: ["/first"]
tags: ["Linear Algebra", "Linear Maps", "Vector Spaces"]
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

# Vector Space of Linear Maps

## Exercise 1

Suppose \( b, c \in \mathbb{R} \). Define \( T: \mathbb{R}^3 \to \mathbb{R}^2 \) by  
\[T(x, y, z) = (2x - 4y + 3z + b, 6x + cxyz).\]  
Show that \( T \) is linear if and only if \( b = c = 0 \).

## Exercise 2

Suppose \( b, c \in \mathbb{R} \). Define \( T: \mathcal{P}(\mathbb{R}) \to \mathbb{R}^2 \) by  
\[Tp = \left( 3p(4) + 5p'(6) + bp(1)p(2), \int_{-1}^{2}x^3p(x)\,dx + c\sin p(0) \right).\]  
Show that \( T \) is linear if and only if \( b = c = 0 \).

## Exercise 3

Suppose \( T \in \mathcal{L}(\mathbb{F}^n, \mathbb{F}^m) \). Show that there exist scalars \( A_{j,k} \in \mathbb{F} \) for \( j = 1, \ldots, m \) and \( k = 1, \ldots, n \) such that  
\[T(x_1, \ldots, x_n) = (A_{1,1}x_1 + \cdots + A_{1,n}x_n, \ldots, A_{m,1}x_1 + \cdots + A_{m,n}x_n)\]  
for every \( (x_1, \ldots, x_n) \in \mathbb{F}^n \).  

## Exercise 4

Suppose \( T \in \mathcal{L}(V, W) \) and \( v_1, \ldots, v_m \) is a list of vectors in \( V \) such that \( Tv_1, \ldots, Tv_m \) is a linearly independent list in \( W \). Prove that \( v_1, \ldots, v_m \) is linearly independent.

## Exercise 5

Show that every linear map from a 1-dimensional vector space to itself is multiplication by some scalar. More precisely, prove that if \(\dim V=1\) and \(T\in\mathcal{L}(V,V)\), then there exists \(\lambda\in\mathbb{F}\) such that \(Tv=\lambda v\) for all \(v\in V\).

## Exercise 6

Give an example of a function \(\varphi\colon\mathbb{R}^{2}\to\mathbb{R}\) such that \[\varphi(av)=a\varphi(v)\] for all \(a\in\mathbb{R}\) and all \(v\in\mathbb{R}^{2}\) but \(\varphi\) is not linear. 

## Exercise 7

Give an example of a function \(\varphi\colon\mathbb{C}\to\mathbb{C}\) such that \[\varphi(w+z)=\varphi(w)+\varphi(z)\] for all \(w,z\in\mathbb{C}\) but \(\varphi\) is not linear. (Here \(\mathbb{C}\) is thought of as a complex vector space.) 

## Exercise 8

Suppose \(U\) is a subspace of \(V\) with \(U\neq V\). Suppose \(S\in\mathcal{L}(U,W)\) and \(S\neq 0\) (which means that \(Su\neq 0\) for some \(u\in U\)). Define \(T\colon V\to W\) by \[Tv=\begin{cases}Sv&\text{if }\;v\in U,\\ 0&\text{if }\;v\in V\text{ and }\;v\notin U.\end{cases}\] Prove that \(T\) is not a linear map on \(V\).

## Exercise 9

Suppose \(V\) is finite-dimensional. Prove that every linear map on a subspace of \(V\) can be extended to a linear map on \(V\). In other words, show that if \(U\) is a subspace of \(V\) and \(S\in\mathcal{L}(U,W)\), then there exists \(T\in\mathcal{L}(V,W)\) such that \(Tu=Su\) for all \(u\in U\).

## Exercise 10

Suppose \(V\) is finite-dimensional with \(\dim V>0\), and suppose \(W\) is infinite-dimensional. Prove that \(\mathcal{L}(V,W)\) is infinite-dimensional.

## Exercise 11

Suppose \(v_{1},\ldots,v_{m}\) is a linearly dependent list of vectors in \(V\). Suppose also that \(W\neq\{0\}\). Prove that there exist \(w_{1},\ldots,w_{m}\in W\) such that no \(T\in\mathcal{L}(V,W)\) satisfies \(Tv_{k}=w_{k}\) for each \(k=1,\ldots,m\).

## Exercise 12

Suppose \(V\) is finite-dimensional with \(\dim V\geq 2\). Prove that there exist \(S,T\in\mathcal{L}(V,V)\) such that \(ST\neq TS\).
