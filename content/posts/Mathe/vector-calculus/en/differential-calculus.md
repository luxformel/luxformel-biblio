---
title: "Differential Calculus"
date: 2025-12-18T14:35:07+01:00
# weight: 1
# aliases: ["/first"]
tags: ["Vector Calculus"]
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

# Differential Calculus

## Exercise 1

Calculate the directional derivative of $f(x,y,z) = x^2y + y^2z$ in the direction of $\hat{\mathbf{n}} = (\hat{\mathbf{x}} + \hat{\mathbf{y}} + \hat{\mathbf{z}})\sqrt{3}$ at point $(1,2,3)$.

## Exercise 2

Compute the gradient of the following scalar fields: 

1. $f(x,y,z) = x^2 + 2xy + 3z + 4$  
2. $g(x,y,z) = \sin x \sin y \sin z$  
3. $h(x,y,z) = e^{-5x}\sin 4y\cos 3z$

## Exercise 3

For the vector field $\mathbf{F} = x^2\hat{\mathbf{x}} + 3xz^2\hat{\mathbf{y}} - 2xz\hat{\mathbf{z}}$:  
1. Calculate $\nabla\cdot\mathbf{F}$  
2. Calculate $\nabla\times\mathbf{F}$

## Exercise 4

For $\mathbf{V} = (2xy+z^3)\hat{\mathbf{x}} + (x^2+2y)\hat{\mathbf{y}} + (3xz^2-2z)\hat{\mathbf{z}}$:

1. Determine if $\mathbf{V}$ is conservative  
2. If so, find the corresponding potential function

## Exercise 5

Verify the product rule $\nabla(fg) = f\nabla g + g\nabla f$ for:  
$f(x,y,z) = x^2 + y^2$ and $g(x,y,z) = e^{-z}\sin x$

## Exercise 6

For $\mathbf{A} = x\hat{\mathbf{x}} + 2y\hat{\mathbf{y}} + 3z\hat{\mathbf{z}}$ and $\mathbf{B} = 3y\hat{\mathbf{x}} - 2x\hat{\mathbf{y}}$:  

1. Verify $\nabla(\mathbf{A}\cdot\mathbf{B}) = \mathbf{A}\times(\nabla\times\mathbf{B}) + \mathbf{B}\times(\nabla\times\mathbf{A}) + (\mathbf{A}\cdot\nabla)\mathbf{B} + (\mathbf{B}\cdot\nabla)\mathbf{A}$  
2. Verify $\nabla\cdot(\mathbf{A}\times\mathbf{B}) = \mathbf{B}\cdot(\nabla\times\mathbf{A}) - \mathbf{A}\cdot(\nabla\times\mathbf{B})$  
3. Verify $\nabla\times(\mathbf{A}\times\mathbf{B}) = (\mathbf{B}\cdot\nabla)\mathbf{A} - (\mathbf{A}\cdot\nabla)\mathbf{B} + \mathbf{A}(\nabla\cdot\mathbf{B}) - \mathbf{B}(\nabla\cdot\mathbf{A})$

## Exercise 7

For $\mathbf{F} = xy\hat{\mathbf{x}} + yz\hat{\mathbf{y}} + zx\hat{\mathbf{z}}$ and $g(x,y,z) = x^2 + y^2 + z^2$:  
Verify $\nabla\times(g\mathbf{F}) = g(\nabla\times\mathbf{F}) - \mathbf{F}\times(\nabla g)$

## Exercise 8

Derive and verify the quotient rules:  
1. $\nabla\left(\frac{f}{g}\right) = \frac{g\nabla f - f\nabla g}{g^2}$  
2. $\nabla\cdot\left(\frac{\mathbf{A}}{g}\right) = \frac{g\nabla\cdot\mathbf{A} - \mathbf{A}\cdot\nabla g}{g^2}$  
3. $\nabla\times\left(\frac{\mathbf{A}}{g}\right) = \frac{g(\nabla\times\mathbf{A}) + \mathbf{A}\times\nabla g}{g^2}$  
Use $f(x,y,z) = x^2 + y^2$, $\mathbf{A} = x\hat{\mathbf{x}} + y\hat{\mathbf{y}} + z\hat{\mathbf{z}}$, and $g(x,y,z) = x^2 + y^2 + z^2$ for verification.

## Exercise 9

Calculate the Laplacian of:  

1. $T_a = x^2 + 2xy + 3z + 4$  
2. $T_b = \sin x \sin y \sin z$  
3. $T_c = e^{-5x}\sin 4y\cos 3z$  
4. $\mathbf{v} = x^2\hat{\mathbf{x}} + 3xz^2\hat{\mathbf{y}} - 2xz\hat{\mathbf{z}}$

## Exercise 10

Prove the following identities:  

1. $\nabla\times(\nabla f) = 0$ for any scalar field $f$  
2. $\nabla\cdot(\nabla\times\mathbf{F}) = 0$ for any vector field $\mathbf{F}$

## Exercise 11

Verify $\nabla\times(\nabla f) = 0$ using $f(x,y,z) = \sin x \sin y \sin z$.

## Exercise 12

Verify $\nabla\cdot(\nabla\times\mathbf{F}) = 0$ using $\mathbf{F} = x^2\hat{\mathbf{x}} + 3xz^2\hat{\mathbf{y}} - 2xz\hat{\mathbf{z}}$.

## Exercise 13

Construct a non-constant vector field that satisfies both $\nabla\cdot\mathbf{F} = 0$ and $\nabla\times\mathbf{F} = 0$ everywhere.

## Exercise 14

For $\mathbf{F} = (x^2+y^2)\hat{\mathbf{x}} + (y^2+z^2)\hat{\mathbf{y}} + (z^2+x^2)\hat{\mathbf{z}}$:  

1. Show that $\nabla\times\mathbf{F} \neq 0$ but has a simple form  
2. Interpret the physical meaning of your result

## Exercise 15

Express the Laplacian $\nabla^2$ in cylindrical coordinates $(\rho,\phi,z)$ for a scalar function $\Phi$.

## Exercise 16

Express the gradient operator $\nabla$ in spherical coordinates $(r,\theta,\phi)$.

## Exercise 17

For vector fields $\mathbf{A}$ and $\mathbf{B}$:  

1. Define the operator $(\mathbf{A}\cdot\nabla)\mathbf{B}$ and express it in Cartesian components  
2. Compute $(\hat{\mathbf{r}}\cdot\nabla)\hat{\mathbf{r}}$ where $\hat{\mathbf{r}} = \mathbf{r}/|\mathbf{r}|$  
3. For $\mathbf{v}_a = x^2\hat{\mathbf{x}} + 3xz^2\hat{\mathbf{y}} - 2xz\hat{\mathbf{z}}$ and $\mathbf{v}_b = xy\hat{\mathbf{x}} + 2yz\hat{\mathbf{y}} + 3zx\hat{\mathbf{z}}$, evaluate $(\mathbf{v}_a\cdot\nabla)\mathbf{v}_b$

## Exercise 18

Prove the vector triple product identity for the gradient:  

$\nabla\times(\mathbf{A}\times\mathbf{B}) = (\mathbf{B}\cdot\nabla)\mathbf{A} - (\mathbf{A}\cdot\nabla)\mathbf{B} + \mathbf{A}(\nabla\cdot\mathbf{B}) - \mathbf{B}(\nabla\cdot\mathbf{A})$

## Exercise 19

Prove the gradient of a dot product identity:  

$\nabla(\mathbf{A}\cdot\mathbf{B}) = \mathbf{A}\times(\nabla\times\mathbf{B}) + \mathbf{B}\times(\nabla\times\mathbf{A}) + (\mathbf{A}\cdot\nabla)\mathbf{B} + (\mathbf{B}\cdot\nabla)\mathbf{A}$

## Exercise 20

Show that:  

1. Any vector field of the form $\mathbf{F} = \nabla f$ is irrotational  
2. Any vector field of the form $\mathbf{F} = \nabla\times\mathbf{G}$ is solenoidal  
3. Discuss the Helmholtz decomposition theorem in this context