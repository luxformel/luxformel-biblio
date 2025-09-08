---
title: "Eigenvalues and Eigenvectors"
date: 2025-09-07T08:35:20+02:00
# weight: 1
# aliases: ["/first"]
tags: ["Linear Algebra", "Eigenvectors" , "Eigenvalues"]
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



# Eigenvalues and Eigenvectors

## Exercise 1
Confirm by multiplication that **x** is an eigenvector of **A**, and find the corresponding eigenvalue.

1. \( A = \begin{bmatrix} 1 & 2 \\ 3 & 2 \end{bmatrix}, \quad x = \begin{bmatrix} 1 \\ -1 \end{bmatrix} \)
2. \( A = \begin{bmatrix} 5 & -1 \\ 3 & 2 \end{bmatrix}, \quad x = \begin{bmatrix} 1 \\ 1 \end{bmatrix} \)
3. \( A = \begin{bmatrix} 4 & 0 & 0 \\ 2 & 3 & 2 \\ 1 & 0 & 4 \end{bmatrix}, \quad x = \begin{bmatrix} 1 \\ 1 \\ 1 \end{bmatrix} \)
4. \( A = \begin{bmatrix} 2 & -1 & -1 \\ -1 & 2 & -1 \\ -1 & -1 & 2 \end{bmatrix}, \quad x = \begin{bmatrix} 1 \\ 1 \\ 1 \end{bmatrix} \)


## Exercise 2
Find the characteristic equation, the eigenvalues, and bases for the eigenspaces of the matrix.

1. \( \begin{bmatrix} 1 & 4 \\ 2 & 3 \end{bmatrix} \)  
2. \( \begin{bmatrix} -2 & -1 \\ 2 & 3 \end{bmatrix} \)  
3. \( \begin{bmatrix} 1 & 0 \\ 0 & 1 \end{bmatrix} \)  
4. \( \begin{bmatrix} 1 & -2 \\ 0 & 1 \end{bmatrix} \)  
5. \( \begin{bmatrix} 1 & 2 \\ 2 & 0 \end{bmatrix} \)  
6. \( \begin{bmatrix} 0 & 2 \\ 2 & -1 \end{bmatrix} \)  
7. \( \begin{bmatrix} 2 & 0 \\ 0 & 2 \end{bmatrix} \)  
8. \( \begin{bmatrix} -2 & -1 \\ 2 & -1 \end{bmatrix} \)  
9.  \( \begin{bmatrix} 4 & 0 & 1 \\ -2 & 1 & 0 \\ 2 & 0 & 1 \end{bmatrix} \)  
10. \( \begin{bmatrix} 1 & 0 & -2 \\ 0 & -2 & 0 \\ 0 & -2 & 4 \end{bmatrix} \)  
11. \( \begin{bmatrix} 6 & 3 & -8 \\ 0 & -2 & 0 \\ 1 & 0 & -3 \end{bmatrix} \)  
12. \( \begin{bmatrix} 0 & 1 & 1 \\ 1 & 0 & 1 \\ 1 & 1 & 0 \end{bmatrix} \)  
13. \( \begin{bmatrix} 4 & 0 & -1 \\ 0 & 3 & 2 \\ 2 & 0 & 1 \end{bmatrix} \)  
14. \( \begin{bmatrix} 1 & -3 & -3 \\ 6 & -6 & 4 \\ 6 & -6 & -4 \end{bmatrix} \)  


## Exercise 3
Find the characteristic equation of the matrix by inspection.

1. \( \begin{bmatrix} 3 & 0 & 0 \\ -2 & 7 & 0 \\ 4 & 8 & 1 \end{bmatrix} \)  
2. \( \begin{bmatrix} 9 & -8 & 6 \\ -1 & 0 & 0 \\ 0 & 3 & 0 \\ 0 & 0 & 7 \end{bmatrix} \)  


## Exercise 4
Find the eigenvalues and a basis for each eigenspace of the linear operator defined by the stated formula.

1. \( T(x, y) = (x + 4y, 2x + 3y) \)  
2.  \( T(x, y, z) = (2x - y - z, x - z, -x + y + 2z) \)  


## Exercise 5
 Let \( D^2: C^\infty(-\infty, \infty) \to C^\infty(-\infty, \infty) \) be the operator that maps a function into its second derivative.  
    
1. Show that \( D^2 \) is linear.  
2. Show that if \( \omega \) is a positive constant, then \( \sin(\sqrt{\omega}x) \) and \( \cos(\sqrt{\omega}x) \) are eigenvectors of \( D^2 \), and find their corresponding eigenvalues. 
    
## Exercise 6

Let \( D^2: C^\infty \to C^\infty \) be the linear operator in _Exercise 5_. Show that if \( \omega \) is a positive constant, then \( \sinh(\sqrt{\omega}x) \) and \( \cosh(\sqrt{\omega}x) \) are eigenvectors of \( D^2 \), and find their corresponding eigenvalues.  



## Exercise 7

Find the eigenvalues and the corresponding eigenspaces of the stated matrix operator on \( \mathbb{R}^2 \). No computations are needed.
 
   1. Reflection about the line \( y = x \).  
   2. Orthogonal projection onto the \( x \)-axis.  
   3. Rotation about the origin through a positive angle of 90°.  
   4. Contraction with factor \( k \) ( \( 0 \leq k < 1 \) ).  
   5. Shear in the \( x \)-direction by a factor \( k \) ( \( k \neq 0 \) ).  

## Exercise 8

Find the eigenvalues and the corresponding eigenspaces of the stated matrix operator on \( \mathbb{R}^2 \). No computations are needed.

   1. Reflection about the \( y \)-axis.  
   2. Rotation about the origin through a positive angle of 180°.  
   3. Dilation with factor \( k \) ( \( k > 1 \) ).  
   4. Expansion in the \( y \)-direction with factor \( k \) ( \( k > 1 \) ).  
   5. Shear in the \( y \)-direction by a factor \( k \) ( \( k \neq 0 \) ).  


## Exercise 9

Find the eigenvalues and corresponding eigenspaces of the stated matrix operator on \( \mathbb{R}^3 \). No computations are needed.
 
1. Reflection about the \( xy \)-plane.  
2. Orthogonal projection onto the \( xz \)-plane.  
3. Counterclockwise rotation about the positive \( x \)-axis through an angle of 90°.  
4. Contraction with factor \( k \) ( \( 0 \leq k < 1 \) ).  

## Exercise 10

Find the eigenvalues and corresponding eigenspaces of the stated matrix operator on \( \mathbb{R}^3 \). No computations are needed.

1. Reflection about the \( xz \)-plane.  
2. Orthogonal projection onto the \( yz \)-plane.  
3. Counterclockwise rotation about the positive \( y \)-axis through an angle of 180°.  
4. Dilation with factor \( k \) ( \( k > 1 \) ).  


## Exercise 11
Let **A** be a \(2 \times 2\) matrix, and call a line through the origin of \(\mathbb{R}^2\) **invariant** under **A** if \(Ax\) lies on the line when \(x\) does. Find equations for all lines in \(\mathbb{R}^2\), if any, that are invariant under the given matrix.

1. \( A = \begin{bmatrix} 4 & -1 \\ 2 & 1 \end{bmatrix} \)  
2. \( A = \begin{bmatrix} 0 & 1 \\ -1 & 0 \end{bmatrix} \)  

## Exercise 12
Find \(\det(A)\) given that **A** has \(p(\lambda)\) as its characteristic polynomial.

1. \( p(\lambda) = \lambda^3 - 2\lambda^2 + \lambda + 5 \)  
2. \( p(\lambda) = \lambda^3 - \lambda + 7 \)  


## Exercise 13
Suppose that the characteristic polynomial of some matrix **A** is found to be \( p(\lambda) = (\lambda - 1)(\lambda - 3)^2(\lambda - 4)^3 \). In each part, answer the question and explain your reasoning.

1. What is the size of **A**?  
2. Is **A** invertible?  
3. How many eigenspaces does **A** have?  

## Exercise 14
The eigenvectors that we have been studying are sometimes called **right eigenvectors** to distinguish them from **left eigenvectors**, which are \( 1 \times n \) row matrices \( y^T \) that satisfy the equation \( y^T A = \mu y^T \) for some scalar \(\mu\). For a given matrix, how are the right eigenvectors and their corresponding eigenvalues related to the left eigenvectors and their corresponding eigenvalues?

## Exercise 15
Find a \( 3 \times 3 \) matrix **A** that has eigenvalues \( 1, -1, \) and \( 0 \), and for which

\[
\begin{bmatrix} -1 \\ 1 \\ 1 \end{bmatrix}, \quad
\begin{bmatrix} 1 \\ 1 \\ 0 \end{bmatrix}, \quad
\begin{bmatrix} 1 \\ 0 \\ -1 \end{bmatrix}
\]

are their corresponding eigenvectors.

## Exercise 16
Prove that the characteristic equation of a \( 2 \times 2 \) matrix **A** can be expressed as

\[
\lambda^2 - \text{tr}(A)\lambda + \det(A) = 0
\]

where \(\text{tr}(A)\) is the trace of **A**.

## Exercise 17
Use the result in _Exercise 16_ to show that if  

\[
A = \begin{bmatrix} a & b \\ c & d \end{bmatrix}
\]

then the solutions of the characteristic equation of **A** are

\[
\lambda = \frac{1}{2} \left( (a + d) \pm \sqrt{(a - d)^2 + 4bc} \right)
\]

Use this result to show that **A** has:

1. Two distinct real eigenvalues if \( (a - d)^2 + 4bc > 0 \).  
2. Two repeated real eigenvalues if \( (a - d)^2 + 4bc = 0 \).  
3. Complex conjugate eigenvalues if \( (a - d)^2 + 4bc < 0 \).  

## Exercise 18
Let **A** be the matrix in _Exercise 17_. Show that if \( b \neq 0 \), then  

\[
x_1 = \begin{bmatrix} -b \\ (a - \lambda_1) \end{bmatrix}, \quad
x_2 = \begin{bmatrix} -b \\ (a - \lambda_2) \end{bmatrix}
\]

are eigenvectors of **A** that correspond, respectively, to the eigenvalues  

\[
\lambda_1 = \frac{1}{2} \left( (a + d) + \sqrt{(a - d)^2 + 4bc} \right)
\]

and  

\[
\lambda_2 = \frac{1}{2} \left( (a + d) - \sqrt{(a - d)^2 + 4bc} \right).
\]

## Exercise 19
Use the result of _Exercise 17_ to prove that if

\[
p(\lambda) = \lambda^2 + c_1\lambda + c_2
\]

is the characteristic polynomial of a \( 2 \times 2 \) matrix, then  

\[
p(A) = A^2 + c_1 A + c_2 I = 0.
\]

(Informally, **A** satisfies its characteristic equation. This result is true for \( n \times n \) matrices as well.)

## Exercise 20
Prove:

1. If \( a, b, c, d \) are integers such that \( a + b = c + d \), then  

   \[
   A = \begin{bmatrix} a & b \\ c & d \end{bmatrix}
   \]

   has integer eigenvalues.  

2. If \( \lambda \) is an eigenvalue of an invertible matrix **A** and \( x \) is a corresponding eigenvector, then \( 1/\lambda \) is an eigenvalue of \( A^{-1} \) and \( x \) is a corresponding eigenvector.  

3. If \( \lambda \) is an eigenvalue of **A**, \( x \) is a corresponding eigenvector, and \( s \) is a scalar, then \( \lambda - s \) is an eigenvalue of \( A - sI \) and \( x \) is a corresponding eigenvector.  

4. If \( \lambda \) is an eigenvalue of **A** and \( x \) is a corresponding eigenvector, then \( s\lambda \) is an eigenvalue of \( sA \) for every scalar \( s \) and \( x \) is a corresponding eigenvector.  

## Exercise 21
Find the eigenvalues and bases for the eigenspaces of

\[
A = \begin{bmatrix} -2 & 3 & 3 \\ -2 & 3 & 2 \\ -4 & 2 & 5 \end{bmatrix}
\]

and then use _Exercises 20.2_ and _Exercises 20.3_ to find the eigenvalues and bases for the eigenspaces of:

1. \( A^{-1} \)  
2. \( A - 3I \)  
3. \( A + 2I \)  

## Exercise 22
Prove that the characteristic polynomial of an \( n \times n \) matrix **A** has degree \( n \) and that the coefficient of \( \lambda^n \) in that polynomial is 1.

## Exercise 23
1. Prove that if **A** is a square matrix, then **A** and \( A^T \) have the same eigenvalues.  
   **Hint:** Look at the characteristic equation \( \det(\lambda I - A) = 0 \).  

2. Show that **A** and \( A^T \) need not have the same eigenspaces.  
   **Hint:** Use the result in Exercise 18 to find a \( 2 \times 2 \) matrix for which **A** and \( A^T \) have different eigenspaces.  

3. Prove that the intersection of any two distinct eigenspaces of a matrix **A** is \(\{ 0 \}\).


## Exercises 24 : True-False 

Determine whether the statement is true or false, and justify your answer.

1. If **A** is a square matrix and \( Ax = \lambda x \) for some nonzero scalar \(\lambda\), then \( x \) is an eigenvector of **A**.  
2. If \( \lambda \) is an eigenvalue of a matrix **A**, then the linear system \( (\lambda I - A)x = 0 \) has only the trivial solution.  
3. If the characteristic polynomial of a matrix **A** is \( p(\lambda) = \lambda^2 + 1 \), then **A** is invertible.  
4. If \( \lambda \) is an eigenvalue of a matrix **A**, then the eigenspace of **A** corresponding to \( \lambda \) is the set of eigenvectors of **A** corresponding to \( \lambda \).  
5. The eigenvalues of a matrix **A** are the same as the eigenvalues of the reduced row echelon form of **A**.  
6. If \( 0 \) is an eigenvalue of a matrix **A**, then the set of columns of **A** is linearly independent.  



## Exercise 25 : Working with technology
For the given matrix **A**, find the characteristic polynomial and the eigenvalues, and find bases for the eigenspaces.

\[
A = \begin{bmatrix} 
-8 & 33 & 38 & 173 & -30 \\ 
0 & 0 & -1 & -4 & 0 \\ 
0 & 0 & -5 & -25 & 1 \\ 
0 & 0 & 0 & 5 & 0 \\ 
4 & -16 & -19 & -86 & 15 
\end{bmatrix}
\]

## Exercise 26 : Working with technology 2
The **Cayley–Hamilton Theorem** states that every square matrix satisfies its characteristic equation; that is, if **A** is an \( n \times n \) matrix whose characteristic equation is  

\[
\lambda^n + c_1\lambda^{n-1} + \dots + c_n = 0
\]

then  

\[
A^n + c_1 A^{n-1} + \dots + c_n = 0.
\]

1. Verify the Cayley–Hamilton Theorem for the matrix  

   \[
   A = \begin{bmatrix} 0 & 1 & 0 \\ 0 & 0 & 1 \\ 2 & -5 & 4 \end{bmatrix}
   \]

2. Use the result in _Exercise 16_ to prove the Cayley–Hamilton Theorem for \( 2 \times 2 \) matrices.