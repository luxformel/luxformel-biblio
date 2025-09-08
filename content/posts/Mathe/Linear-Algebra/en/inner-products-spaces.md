---
title: "Inner Product Spaces"
date: 2025-09-07T07:28:08+02:00
# weight: 1
# aliases: ["/first"]
tags: ["Linear Algebra", "Inner Products"]
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

# Inner Product Spaces

## Exercise 1
In each part, determine whether the set of vectors is orthogonal and whether it is orthonormal with respect to the Euclidean inner product on ℝ².

1. $ (0, 1), (2, 0) $ 
2. $(- \frac{1}{\sqrt{2}}, \frac{1}{\sqrt{2}}), (\frac{1}{\sqrt{2}}, \frac{1}{\sqrt{2}})$  
3. $(- \frac{1}{\sqrt{2}}, \frac{1}{\sqrt{2}}), (\frac{1}{\sqrt{2}}, \frac{1}{\sqrt{2}})$  
4. $ (0, 0), (0, 1) $

## Exercise 2
In each part, determine whether the set of vectors is orthogonal and whether it is orthonormal with respect to the Euclidean inner product on $\mathbb{R}^2$.

1. $(\frac{1}{2}, 0, \frac{1}{2}), (\frac{1}{3}, \frac{1}{3}, -\frac{1}{3}), (-\frac{1}{2}, 0, \frac{1}{2})$  
2. $(\frac{2}{3}, \frac{1}{3}, \frac{1}{3}), (\frac{1}{3}, \frac{2}{3}, \frac{1}{3}), (\frac{1}{3}, \frac{1}{3}, \frac{2}{3})$  
3. $ (1, 0, 0), (0, \frac{1}{2}, \frac{1}{2}), (0, 0, 1)  $
4. $(\frac{1}{\sqrt{6}}, \frac{1}{\sqrt{6}}, -\frac{2}{\sqrt{6}}), (\frac{1}{\sqrt{2}}, -\frac{1}{\sqrt{2}}, 0) $

## Exercise 3
In each part, determine whether the set of vectors is orthogonal with respect to the standard inner product on $P_2$.

1. $p_1(x) = \frac{1}{3}x + \frac{1}{3}x^2$,  $p_2(x) = \frac{2}{3} + \frac{1}{3}x - \frac{2}{3}x^2$,  $p_3(x) = \frac{1}{3} + \frac{2}{3}x + \frac{1}{3}x^2 $ 
2. $p_1(x) = 1$, $p_2(x) = \frac{1}{\sqrt{2}}x + \frac{1}{\sqrt{2}}x^2$, $p_3(x) = x^2$

## Exercise 4
In each part, determine whether the set of vectors is orthogonal with respect to the standard inner product on $M_{22}$.

1.
$$
\left[\begin{array}{ll}0 & 0 \\ 1 & 0\end{array}\right], \left[\begin{array}{ll}0 & 0 \\ 0 & 1\end{array}\right], \left[\begin{array}{ll}0 & 1 \\ 0 & 0\end{array}\right], \left[\begin{array}{ll}1 & 0 \\ 0 & 0\end{array}\right]
$$  
2.
$$
\left[\begin{array}{cc}1 & 0 \\ 0 & 0\end{array}\right], \left[\begin{array}{cc}0 & 1 \\ 1 & 0\end{array}\right], \left[\begin{array}{cc}0 & 0 \\ 0 & 1\end{array}\right], \left[\begin{array}{cc}1 & 0 \\ 0 & -1\end{array}\right]
$$

## Exercise 5
Show that the column vectors of $A$ form an orthogonal basis for the column space of $A$ with respect to the Euclidean inner product, and then find an orthonormal basis for that column space.  
$$
A = \left[\begin{array}{ccc}1 & 2 & 0 \\ 0 & 0 & 5 \\ -1 & 2 & 0\end{array}\right]
$$

## Exercise 6
Show that the column vectors of $A$ form an orthogonal basis for the column space of $A$ with respect to the Euclidean inner product, and then find an orthonormal basis for that column space. 
$$
A = \left[\begin{array}{ccc}1 & 1 & 2 \\ 2 & 1 & 1 \\ 3 & 2 & 3\end{array}\right]
$$

## Exercise 7
Verify that the vectors  
$$
\mathbf{v}_1 = \left(-\frac{2}{3}, \frac{4}{3}, 0\right), \mathbf{v}_2 = \left(\frac{4}{3}, \frac{5}{3}, 0\right), \mathbf{v}_3 = (0, 0, 1)
$$  
form an orthonormal basis for $\mathbb{R}^2$ with respect to the Euclidean inner product. Express $\mathbf{u} = (-1, -2, 2)$ as a linear combination of $\mathbf{v}_1, \mathbf{v}_2, \mathbf{v}_3$.

## Exercise 8
Express $\mathbf{u} = (3, -7, 4)$ as a linear combination of the vectors from Exercise 7.

## Exercise 9
Verify that the vectors  
$$
\mathbf{v}_1 = (2, -2, 1), \mathbf{v}_2 = (2, 1, -2), \mathbf{v}_3 = (1, 2, 2)
$$  
form an orthogonal basis for $\mathbb{R}^3$ with respect to the Euclidean inner product. Express $\mathbf{u} = (-1, 0, 2)$ as a linear combination of these vectors.

## Exercise 10
Verify that the vectors  
$$
\mathbf{v}_1 = (-1, -1, 2, -1), \mathbf{v}_2 = (-2, 2, 3, 2), \mathbf{v}_3 = (1, 2, 0, -1), \mathbf{v}_4 = (1, 0, 0, 1)
$$  
form an orthogonal basis for $\mathbb{R}^4$. Express $\mathbf{u} = (1, 1, 1, 1)$ as a linear combination of these vectors.

## Exercise 11
Find the coordinate vector $(u)_S$ for the vector and basis:  
$$
\mathbf{u} = (4, 3, 6), \mathbf{v}_1 = (1, -2, 2), \mathbf{v}_2 = (2, 1, 1), \mathbf{v}_3 = (0, 3, 3)
$$

## Exercise 12
Find the coordinate vector $(u)_S$ for:  
$$
\mathbf{u} = (1, -1, 3), \mathbf{v}_1 = (2, 0, 1), \mathbf{v}_2 = (0, 1, 0), \mathbf{v}_3 = (-1, 0, 2)
$$

## Exercise 13
Find the coordinate vector $(u)_S$ for:  
$$
\mathbf{u} = (-1, 1, 2, 1), \mathbf{v}_1 = (1, 1, 1, 1), \mathbf{v}_2 = (1, 1, -1, -1), \mathbf{v}_3 = (1, -1, 1, -1), \mathbf{v}_4 = (1, -1, -1, 1)
$$

## Exercise 14
Find the coordinate vector $(u)_S$ for:  
$$
\mathbf{u} = (1, 1, 1, 1), \mathbf{v}_1 = (-1, -1, 2, -1), \mathbf{v}_2 = (-2, 2, 3, 2), \mathbf{v}_3 = (1, 2, 0, -1), \mathbf{v}_4 = (1, 0, 0, 1)
$$


## Exercise 15

Let $\mathbb{R}^2$ have the Euclidean inner product.

1. Find the orthogonal projection of $\mathbf{u}$ onto the line spanned by $\mathbf{v}$.
2. Find the component of $\mathbf{u}$ orthogonal to that line and confirm orthogonality.

$\mathbf{u} = (-1, 6); \mathbf{v} = (3, 5)$

## Exercise 16

Let $\mathbb{R}^2$ have the Euclidean inner product.

1. Find the orthogonal projection of $\mathbf{u}$ onto the line spanned by $\mathbf{v}$.
2. Find the component of $\mathbf{u}$ orthogonal to that line and confirm orthogonality.

$\mathbf{u} = (2, 3); \mathbf{v} = (\frac{5}{13}, \frac{12}{13})$

## Exercise 17

Let $\mathbb{R}^2$ have the Euclidean inner product.

1. Find the orthogonal projection of $\mathbf{u}$ onto the line spanned by $\mathbf{v}$.
2. Find the component of $\mathbf{u}$ orthogonal to that line and confirm orthogonality.

$\mathbf{u} = (2, 3); \mathbf{v} = (1, 2)$

## Exercise 18

Let $\mathbb{R}^2$ have the Euclidean inner product.

1. Find the orthogonal projection of $\mathbf{u}$ onto the line spanned by $\mathbf{v}$.
2. Find the component of $\mathbf{u}$ orthogonal to that line and confirm orthogonality.

$\mathbf{u} = (3, -1); \mathbf{v} = (3, 4)$



## Exercise 19

Let $\mathbb{R}^3$ have the Euclidean inner product.

1. Find the orthogonal projection of $\mathbf{u}$ onto the plane spanned by $\mathbf{v}_1, \mathbf{v}_2$.
2. Find the orthogonal component and confirm orthogonality.

$$ \mathbf{u} = (4, 2, 1) $$
$$ \mathbf{v}_1 = (\frac{1}{3}, \frac{2}{3}, -\frac{1}{3}) $$
$$ \mathbf{v}_2 = (\frac{2}{3}, \frac{1}{3}, \frac{2}{3})
$$

## Exercise 20

Let $\mathbb{R}^3$ have the Euclidean inner product.

1. Find the orthogonal projection of $\mathbf{u}$ onto the plane spanned by $ \mathbf{v}_1, \mathbf{v}_2 $.
2. Find the orthogonal component and confirm orthogonality.

$$
\mathbf{u} = (3, -1, 2) $$ $$ \mathbf{v}_1 = (-\frac{1}{\sqrt{6}}, -\frac{2}{\sqrt{6}}, \frac{1}{\sqrt{6}}), $$
