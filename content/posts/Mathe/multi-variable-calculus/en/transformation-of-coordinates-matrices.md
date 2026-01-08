---
title: "Transformation of Coordinates; Matrices"
date: 2026-01-08T11:36:28+01:00
# weight: 1
# aliases: ["/first"]
tags: ["Multi Variable Calculus", "Matrices", "Coordinate Systems", "Applied Mathematics"]
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

# Transformation of Coordinates; Matrices

## Exercise 1 : Shift Paraboloid

The vertex of the paraboloid shown in Fig. 14.18 is at a distance 2 from the origin of the coordinates. The equation is $z = 2 + x^2 + y^2$. What is the transformation which will shift the paraboloid so that its vertex coincides with the origin O?

## Exercise 2 : Line Under Translation

The equation of a certain straight line is $y = -3x + 5$. What will its equation be in a new $x'$-$y'$ coordinate system due to a shift of the origin of $(-2,3)$?

## Exercise 3 : Rotation (2D)

A two-dimensional system of coordinates is rotated through an angle of $\pi/3$. The transformation matrix is:

$$
\begin{pmatrix}
\frac{1}{2} & \frac{\sqrt{3}}{2} \\
-\frac{\sqrt{3}}{2} & \frac{1}{2}
\end{pmatrix}
$$

What is the new vector $\mathbf{r}'$ if $\mathbf{r} = (2,4)$?

## Exercise 4 : Rotated Line Equation

Given the equation $y = -x/\sqrt{3} + 2$, if the system of coordinates is rotated through an angle of $60^\circ$ obtain an expression for the equation in the rotated system.

## Exercise 5 : Rotation About z-Axis (3D)

A three-dimensional system of coordinates is rotated about the $z$-axis through an angle of $30^\circ$. Obtain the transformed vector $\mathbf{r}'$ if $\mathbf{r} = (3,3,3)$.

## Exercise 6 : Matrix Addition and Subtraction

Given the two matrices $A$ and $B$ where:

$$
A = \begin{pmatrix}
1 & 3 \\
2 & 5
\end{pmatrix}
\quad \text{and} \quad
B = \begin{pmatrix}
2 & 0 \\
-1 & 3
\end{pmatrix}
$$
evaluate

1. $A + B$,
2. $A - B$.

## Exercise 7 : Scalar Multiplication and Noncommutativity

Let
$$
A = \begin{pmatrix}
2 & 7 \\
3 & 0
\end{pmatrix}
\quad \text{and} \quad
B = \begin{pmatrix}
9 & 3 \\
1 & -2
\end{pmatrix}
$$

1. Evaluate the matrix $6A$.
2. Show that the expression $AB \neq BA$.

## Exercise 8 : Matrix Multiplication

Given
$$
A = \begin{pmatrix}
1 & 2 \\
7 & 3
\end{pmatrix}
\quad \text{and} \quad
B = \begin{pmatrix}
-1 & 0 \\
2 & 3
\end{pmatrix}
$$
evaluate $AB$.

## Exercise 9 : Matrix-Vector Product

Evaluate the product $A \mathbf{r}$ if
$$
A = \begin{pmatrix} 1 & -2 \\
5 & 7 \end{pmatrix}, \quad \mathbf{r} = \begin{pmatrix} x \\
y \end{pmatrix}
$$

## Exercise 10 : Transpose Properties

Given
$$
A = \begin{pmatrix} 1 & 2 \\
4 & -3 \\
3 & 0 \end{pmatrix}
$$
evaluate

1. $A^T$
2. $(A^T)^T$

## Exercise 11 : Skew-Symmetric Matrix

How many independent entries are there in a skew-symmetric $3 \times 3$ matrix?

## Exercise 12 : Skew-Symmetric Matrix Decomposition

Decompose into a symmetric and a skew-symmetric matrix:
$$
\begin{pmatrix} 54 & 1 & 1 \\
0 & 26 & 20 \\
8 & 84 & 9 \end{pmatrix}
$$

## Exercise 13 : Inverse Matrix

If
$$
A = \begin{pmatrix} 1 & 0 & 3 \\
2 & -3 & 1 \\
1 & 2 & 2 \end{pmatrix} \quad \text{and} \quad A^{-1} = \frac{1}{13} \begin{pmatrix} -8 & 6 & 9 \\
-3 & -1 & 5 \\
7 & -2 & -3 \end{pmatrix}
$$
show that $A A^{-1} = A^{-1} A = I$.

## Exercise 14 : Determinant and Volume

Compute the determinant of
$$
B = \begin{pmatrix} 2 & 1 & 0 \\
1 & 3 & 4 \\
0 & -1 & 2 \end{pmatrix}
$$
and interpret the absolute value of $\det(B)$ as the volume scaling factor of the linear map in $\mathbb{R}^3$.

## Exercise 15 : Rank and Linear Independence

Find the rank of
$$
C = \begin{pmatrix} 1 & 2 & 3 \\
2 & 4 & 6 \\
1 & 0 & 1 \end{pmatrix}
$$
and determine whether its columns are linearly independent.

## Exercise 16 : Eigenvalues and Eigenvectors

Find the eigenvalues and eigenvectors of
$$
D = \begin{pmatrix} 4 & 1 \\
2 & 3 \end{pmatrix}
$$
Compute the characteristic polynomial and diagonalize if possible.

## Exercise 17 : Diagonalization

Determine whether
$$
E = \begin{pmatrix} 3 & 1 & 0 \\
0 & 3 & 0 \\
0 & 0 & 2 \end{pmatrix}
$$
is diagonalizable. If so, find an invertible $P$ and diagonal $\Lambda$ such that $E = P \Lambda P^{-1}$.

## Exercise 18 : Orthogonal Projection

Find the matrix that projects vectors in $\mathbb{R}^3$ orthogonally onto the line spanned by $\mathbf{u} = (1,2,2)$.

## Exercise 19 : Gram-Schmidt Orthonormalization

Apply the Gram--Schmidt process to the vectors $\mathbf{v}_1 = (1,1,0)$, $\mathbf{v}_2 = (1,0,1)$ to produce an orthonormal set.

## Exercise 20 : Change of Basis

Let $\mathcal{B} = \{(1,1),(1,-1)\}$ be a basis of $\mathbb{R}^2$. Find the change-of-basis matrix from $\mathcal{B}$-coordinates to standard coordinates, and compute the coordinates of $(3,1)$ in the $\mathcal{B}$ basis.

## Exercise 21 : Composition of Transformations

Consider a rotation in the plane by $45^\circ$ followed by a reflection in the $x$-axis. Write down the matrices for each transformation, compute their product, and describe the resulting transformation.
