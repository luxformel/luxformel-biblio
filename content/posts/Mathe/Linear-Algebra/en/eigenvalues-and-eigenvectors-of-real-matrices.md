---
title: "Eigenvalues and Eigenvectors of Real Matrices"
date: 2026-01-08T10:36:10+01:00
# weight: 1
# aliases: ["/first"]
tags: ["Linear Algebra", "Eigenvalues", "Eigenvectors", "Matrices", "Applied Mathematics"]
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

# Eigenvalues and Eigenvectors of Real Matrices

## Exercise 1 : Eigenvalues — 2x2 real matrix

For $A = \begin{pmatrix} 4 & 2 \\ 1 & 3 \end{pmatrix}$ find the eigenvalues.  

## Exercise 2 : Real vs Complex Eigenvalues — 2x2 question

Is it possible for a real $2 \times 2$ matrix to have one real and one complex eigenvalue?

## Exercise 3 : No Real Eigenvalues — rotation-like matrix

Prove that there are no real eigenvalues of the matrix $A = \begin{pmatrix} 3 & 2 \\ -2 & 1 \end{pmatrix}$

## Exercise 4 : Eigenvalues and Eigenvectors — 3x3 computation

1. For $A = \begin{pmatrix} -1 & -1 & 1 \\ -4 & 2 & 4 \\ -1 & 1 & 5 \end{pmatrix}$ find all the eigenvalues.   
2. Find corresponding eigenvectors.

## Exercise 5 : Defective Matrix — repeated eigenvalue

Find the roots of the characteristic equation for $A = \begin{pmatrix} 1 & 1 \\ 0 & 1 \end{pmatrix}$. Then try to find corresponding eigenvectors.

## Exercise 6 : Diagonalization Criteria — theory and practice

1. State the necessary and sufficient conditions for a real matrix to be diagonalizable over $\mathbb{R}$.  
2. Decide whether the matrix $B=\begin{pmatrix} 2 & 0 & 0 \\ 0 & 3 & 1 \\ 0 & 0 & 3 \end{pmatrix}$ is diagonalizable. Justify your answer.

## Exercise 7 : Algebraic and Geometric Multiplicity — multiplicities

For $C=\begin{pmatrix} 4 & 1 & 0 \\ 0 & 4 & 1 \\ 0 & 0 & 4 \end{pmatrix}$ compute the algebraic multiplicity and geometric multiplicity of the eigenvalue $4$. Explain the relationship between them and consequences for diagonalizability.

## Exercise 8 : Symmetric Matrices — orthogonal diagonalization

1. Show that a real symmetric matrix has real eigenvalues and orthogonal eigenvectors (state the spectral theorem for symmetric matrices).
2. Compute the eigenvalues and an orthonormal set of eigenvectors for $D=\begin{pmatrix} 2 & -1 \\ -1 & 2 \end{pmatrix}$.

## Exercise 9 : Complex Eigenpairs and Real Matrices — conjugate pairs

Let $E=\begin{pmatrix} 0 & -1 \\ 1 & 0 \end{pmatrix}$.  

1. Compute the eigenvalues and eigenvectors of $E$ over $\mathbb{C}$.  
2. Explain why complex eigenvalues of real matrices occur in conjugate pairs and how to form real 2D invariant subspaces from such pairs.

## Exercise 10 : Jordan Blocks and Generalized Eigenvectors — small Jordan example

1. For $F=\begin{pmatrix} 5 & 1 \\ 0 & 5 \end{pmatrix}$ find the Jordan normal form and a chain of generalized eigenvectors.  
2. Explain why the presence of a nontrivial Jordan block prevents diagonalization.

## Exercise 11 : Matrix Exponential via Diagonalization and Jordan Form

1. If $A$ is diagonalizable with $A=SDS^{-1}$, express $e^{tA}$ in terms of $S,D$.  
2. Compute $e^{tF}$ for $F$ from Exercise 10 using its Jordan form.

## Exercise 12 : Applications — mechanical system and modes

Consider the matrix $M=\begin{pmatrix} 0 & 1 \\ -2 & -3 \end{pmatrix}$ arising from a simple damped oscillator linearization.  

1. Find eigenvalues and determine whether the system is overdamped, underdamped, or critically damped.  
2. If eigenvectors exist, write the general solution of $\dot{x}=Mx$ using eigen-decomposition (or explain the Jordan approach if defective).
