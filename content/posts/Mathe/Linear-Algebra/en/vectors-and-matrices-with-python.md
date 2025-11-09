---
title: "Vectors and Matrices in Python"
date: 2025-11-09T17:52:23+01:00
# weight: 1
# aliases: ["/first"]
tags: ["Linear Algebra", "Vectors", "Matrices", "Python"]
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

# Vectors and Matrices in Python

In this worksheet, you will use **Python (NumPy)** to perform vector and matrix operations.  
For each exercise, write Python code to compute the required results and verify them numerically.

---

## Exercise 1 : Vectors in $\mathbb{R}^7$

Consider the following vectors:
$$
u = (0.5, 0.4, 0.4, 0.5, 0.1, 0.4, 0.1), \quad v = (-1, -2, 1, -2, 3, 1, -5)
$$

Using **Python and NumPy**:

1. Check whether $u$ and $v$ are unit vectors.  
2. Compute the dot product of $u$ and $v$.  
3. Determine if $u$ and $v$ are orthogonal.


## Exercise 2 : Norms and Orthogonality

Consider the following vectors in $\mathbb{R}^9$:
$$
u = (1, 2, 5, 2, -3, 1, 2, 6, 2), \quad v = (-4, 3, -2, 2, 1, -3, 4, 1, -2), \quad w = (3, 3, -3, -1, 6, -1, 2, -5, -7)
$$

Using Python:

1. Check which pairs of these vectors are orthogonal.  
2. Calculate the **Euclidean norm** of $u$.  
3. Calculate the **infinity norm** of $w$.


## Exercise 3 : Matrix Operations

Consider the matrices:
$$
A = \begin{pmatrix} 2 & -2 \\ 0 & 1 \end{pmatrix}, \quad B = \begin{pmatrix} 3 & 1 \\ 6 & 2 \end{pmatrix}, \quad C = \begin{pmatrix} 4 & 1 & -1 \\ 2 & 5 & -2 \\ 1 & 1 & 2 \end{pmatrix}, \quad D = \begin{pmatrix} -3 & 1 & -1 \\ -7 & 5 & -1 \\ -6 & 6 & -2 \end{pmatrix}
$$
$$
E = \begin{pmatrix} 2 \\ -1 \\ 3 \end{pmatrix}, \quad F = \begin{pmatrix} -2 & 1 & 0 \end{pmatrix}, \quad G = \begin{pmatrix} 1 & -1 & 0 & 0 \\ 1 & 4 & 0 & 0 \end{pmatrix}
$$

Using Python:

1. Compute (if possible):  
   - $A + B$, $B - A$, $B + C$, $AB$, $BA$, $BG$, $CE$, $EF$, $FE$  
2. Compute the transposes of $A$ and $B$ and then their product.  
   Observe and explain any property you find.


## Exercise 4 : Matrix Rank and Norms

Consider the following matrices:
$$
A = \begin{pmatrix} 2 & -2 \\ -3 & 1 \\ 5 & -3 \end{pmatrix}, \quad B = \begin{pmatrix} 4 & 4 & 4 \\ -2 & 3 & -7 \\ 2 & 5 & -7 \end{pmatrix}, \quad C = \begin{pmatrix} 4 & -1 & 2 \\ -8 & 2 & -4 \\ 2 & 1 & -4 \end{pmatrix}
$$

Using Python:

1. Compute $A^T B$ and $C + B$.  
2. Determine which of $A$, $B$, and $C$ are full rank.  
3. Compute the **Frobenius norm** of $C$ and the **spectral norm** of $A$.  
4. Attempt to compute the inverse of $B$.

## Exercise 5 : Determinants

Using the matrices from **Exercise 3**, and Python:

1. Compute $\det(A)$, $\det(B)$, and $\det(AB)$.  
2. Compute $\det(C)$ and $\det(D)$.


## Exercise 6 : Inverses

Consider the matrices:
$$
A = \begin{pmatrix} 2 & -1 \\ 4 & 3 \end{pmatrix}, \quad B = \begin{pmatrix} 2 & 0 \\ 4 & 5 \end{pmatrix}, \quad C = \begin{pmatrix} 6 & -9 \\ -4 & 6 \end{pmatrix}, \quad D = \begin{pmatrix} -1 & 6 & 2 \\ 0 & 1 & 0 \\ 3 & 0 & -5 \end{pmatrix}
$$

Using Python, calculate (if possible) the inverses of $A$, $B$, $C$, and $D$.


## Exercise 7 : Invertibility

Consider the matrix:
$$
A = \begin{pmatrix} 2 & 2 & 3 \\ -2 & 7 & 4 \\ -3 & -3 & -4 \\ -8 & 2 & 3 \end{pmatrix}
$$

Using Python:

1. Add a column to $A$ to make it invertible.  
2. Remove a row from $A$ to make it invertible.  
3. Compute $AA^T$ and check if it is invertible.  
4. Compute $A^T A$ and check if it is invertible.


## Exercise 8 : Matrix Inversion and Systems of Equations

Using Python:

1. Compute the inverse of
   $$
   M = \begin{pmatrix} 3 & 2 & -1 \\ 1 & -1 & 1 \\ 2 & -4 & 5 \end{pmatrix}.
   $$
2. Use this inverse to solve the linear system:
   $$
   \begin{cases}
   3x + 2y - z = 5 \\
   x - y + z = 1 \\
   2x - 4y + 5z = -3
   \end{cases}
   $$


## Exercise 9 : Solving Linear Systems

Use Python to solve the following systems:

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