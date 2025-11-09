---
title: "Vectors and Matrices"
date: 2025-11-06T20:08:06+01:00
# weight: 1
# aliases: ["/first"]
tags: ["Linear Algebra", "Vectors", "Matrices"]
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

# Vectors and Matrices


## Exercise 1

Consider the following vectors in $ \mathbb{R}^7 $:
$$
u = (0.5, 0.4, 0.4, 0.5, 0.1, 0.4, 0.1), \quad v = (-1, -2, 1, -2, 3, 1, -5)
$$

1. Check if $ u $ and $ v $ are unit vectors.  
2. Calculate the dot product of the vectors $ u $ and $ v $.  
3. Are $ u $ and $ v $ orthogonal?


## Exercise 2
Consider the following vectors in $ \mathbb{R}^9 $:
$$
u = (1, 2, 5, 2, -3, 1, 2, 6, 2), $$ $$ v = (-4, 3, -2, 2, 1, -3, 4, 1, -2) $$ $$ w = (3, 3, -3, -1, 6, -1, 2, -5, -7) $$

1. Which pairs of these vectors are orthogonal?  
2. Calculate the Euclidean norm of $ u $.  
3. Calculate the infinity norm of $ w $.


## Exercise 3

Consider the following matrices:
$$
A = \begin{pmatrix} 2 & -2 \\ 0 & 1 \end{pmatrix}, \quad B = \begin{pmatrix} 3 & 1 \\ 6 & 2 \end{pmatrix}, \quad C = \begin{pmatrix} 4 & 1 & -1 \\ 2 & 5 & -2 \\ 1 & 1 & 2 \end{pmatrix}, \quad D = \begin{pmatrix} -3 & 1 & -1 \\ -7 & 5 & -1 \\ -6 & 6 & -2 \end{pmatrix}
$$
$$
E = \begin{pmatrix} 2 \\ -1 \\ 3 \end{pmatrix}, \quad F = \begin{pmatrix} -2 & 1 & 0 \end{pmatrix}, \quad G = \begin{pmatrix} 1 & -1 & 0 & 0 \\ 1 & 4 \end{pmatrix}
$$

1. Calculate, if possible:  
   - $ A + B $  
   - $ B - A $  
   - $ B + C $  
   - $ AB $  
   - $ BA $  
   - $ BG $  
   - $ CE $  
   - $ EF $  
   - $ FE $

2. Write the transposes of $ A $ and $ B $ and calculate their product. Which property can one observe?


## Exercise 4

Consider the following matrices:
$$
A = \begin{pmatrix} 2 & -2 \\ -3 & 1 \\ 5 & -3 \end{pmatrix}, \quad B = \begin{pmatrix} 4 & 4 & 4 \\ -2 & 3 & -7 \\ 2 & 5 & -7 \end{pmatrix}, \quad C = \begin{pmatrix} 4 & -1 & 2 \\ -8 & 2 & -4 \\ 2 & 1 & -4 \end{pmatrix}
$$

1. Compute $ A^T B $ and $ C + B $.  
2. Which of the matrices $ A $, $ B $, $ C $ are full rank?  
3. Calculate the Frobenius norm of $ C $ and the spectral norm of $ A $.  
4. Calculate the inverse of $ B $.


## Exercise 5

Consider the matrices of Exercise 3.

1. Calculate the determinants of the matrices $ A $, $ B $, and $ AB $.  
2. Calculate the determinants of the matrices $ C $ and $ D $.


## Exercise 6

Consider the following matrices:
$$
A = \begin{pmatrix} 2 & -1 \\ 4 & 3 \end{pmatrix}, \quad B = \begin{pmatrix} 2 & 0 \\ 4 & 5 \end{pmatrix}, \quad C = \begin{pmatrix} 6 & -9 \\ -4 & 6 \end{pmatrix}, \quad D = \begin{pmatrix} -1 & 6 & 2 \\ 0 & 1 & 0 \\ 3 & 0 & -5 \end{pmatrix}
$$

Calculate, if possible, the inverses of the matrices $ A $, $ B $, $ C $, and $ D $.


## Exercise 7

Consider the matrix:
$$
A = \begin{pmatrix} 2 & 2 & 3 \\ -2 & 7 & 4 \\ -3 & -3 & -4 \\ -8 & 2 & 3 \end{pmatrix}
$$

1. Add a column to $ A $ so that it is invertible.  
2. Remove a row from $ A $ so that it is invertible.  
3. Calculate $ AA^T $. Is it invertible?  
4. Calculate $ A^T A $. Is it invertible?


## Exercise 8

1. Calculate the inverse of the matrix $ M = \begin{pmatrix} 3 & 2 & -1 \\ 1 & -1 & 1 \\ 2 & -4 & 5 \end{pmatrix} $.  
2. Use this inverse to solve the linear system:
   $$
   \begin{cases}
   3x + 2y - z = 5 \\
   x - y + z = 1 \\
   2x - 4y + 5z = -3
   \end{cases}
   $$


## Exercise 9

Solve the systems:

1. 
$$
\begin{cases}
2x + 3y + 5z = 2 \\
7x + z = -1 \\
-2y + 2z = 3
\end{cases}
$$

2. 
$$
\begin{cases}
x + 2y - z = 2 \\
2x + 5y + 4z = 3 \\
3x + 7y + 4z = 1
\end{cases}
$$

