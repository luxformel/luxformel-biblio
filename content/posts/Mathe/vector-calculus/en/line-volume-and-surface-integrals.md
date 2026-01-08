---
title: "Line, Volume and Surface Integrals"
date: 2025-12-18T15:08:39+01:00
# weight: 1
# aliases: ["/first"]
tags: ["Vector Calculus", "Integrals"]
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

# Line, Volume and Surface Integrals

## Exercise 1 : Basic Line Integral

For $\mathbf{v} = x^2\,\hat{\mathbf{x}} + 2yz\,\hat{\mathbf{y}} + y^2\,\hat{\mathbf{z}}$, compute $\int_C \mathbf{v} \cdot d\mathbf{l}$ from $(0,0,0)$ to $(1,1,1)$ along:

1. $(0,0,0) \to (1,0,0) \to (1,1,0) \to (1,1,1)$  
2. $(0,0,0) \to (0,0,1) \to (0,1,1) \to (1,1,1)$  
3. The straight line $x = y = z$
4. Evaluate $\oint \mathbf{v} \cdot d\mathbf{l}$ around the closed loop: out via 1., back via 2..

## Exercise 2 : Gradient Field Verification

Given $\phi = e^{xyz}$, compute $\nabla \phi$ and verify the gradient theorem:
$\int_{\mathbf{a}}^{\mathbf{b}} \nabla \phi \cdot d\mathbf{l} = \phi(\mathbf{b}) - \phi(\mathbf{a})$
for $\mathbf{a} = (0,0,0)$ and $\mathbf{b} = (1,1,1)$ along two different paths.

## Exercise 3 : Gradient Theorem

Verify the gradient theorem for $T = x^2 + 4xy + 2yz^3$ from $\mathbf{a} = (0,0,0)$ to $\mathbf{b} = (1,1,1)$ along:

1. $(0,0,0) \to (1,0,0) \to (1,1,0) \to (1,1,1)$  
2. $(0,0,0) \to (0,0,1) \to (0,1,1) \to (1,1,1)$  
3. The parabolic path $z = x^2$, $y = x$

## Exercise 4 : Basic Surface Integral

Consider $\mathbf{v} = x^2\,\hat{\mathbf{x}} + 2yz\,\hat{\mathbf{y}} + y^2\,\hat{\mathbf{z}}$ over the bottom face ($z = 0$, $0 \le x,y \le 1$) of a unit cube.

1. Compute $\int_S \mathbf{v} \cdot d\mathbf{a}$ with upward as positive.  
2. Does this surface integral depend only on the boundary?  
3. Find the total flux through the *closed* surface of the cube (positive direction outward).

## Exercise 5 : Stokes' Theorem Application

For $\mathbf{v} = (xy)\,\hat{\mathbf{x}} + (2yz)\,\hat{\mathbf{y}} + (3zx)\,\hat{\mathbf{z}}$, compute the surface integral over the *five* faces of the cube $0 \le x,y,z \le 1$ (back face open) and compare with the line integral around its boundary.

## Exercise 6 : Basic Volume Integral

Evaluate $\int_V T \, d\tau$ for $T = z^2$ over the tetrahedron with vertices  
$(0,0,0)$, $(1,0,0)$, $(0,1,0)$, and $(0,0,1)$.

## Exercise 7 : Divergence Theorem Practice

For $\mathbf{G} = x^2 y\,\hat{\mathbf{x}} + z\,\hat{\mathbf{y}} + xy\,\hat{\mathbf{z}}$:

1. Find $\nabla \cdot \mathbf{G}$  
2. Compute $\iiint_V (\nabla \cdot \mathbf{G})\, d\tau$ over the volume bounded by $z = 0$, $z = 1 - x - y$, $x \ge 0$, $y \ge 0$  
3. Compute the outward flux $\iint_{\partial V} \mathbf{G} \cdot d\mathbf{a}$ and check the divergence theorem

## Exercise 8 : Divergence Theorem

Test the divergence theorem for $\mathbf{v} = (xy)\,\hat{\mathbf{x}} + (2yz)\,\hat{\mathbf{y}} + (3zx)\,\hat{\mathbf{z}}$ over a cube centered at the origin with side length $2$.

## Exercise 9 : Stokes' Theorem

Test Stokes' theorem for $\mathbf{v} = (xy)\,\hat{\mathbf{x}} + (2yz)\,\hat{\mathbf{y}} + (3zx)\,\hat{\mathbf{z}}$ using the triangular surface with vertices  
$(0,0,0)$, $(0,2,0)$, and $(0,0,2)$.

## Exercise 10 : Comprehensive Stokes' Theorem

Let $\mathbf{F} = (y^2, xz, z^3)$  

1. Compute $\nabla \times \mathbf{F}$  
2. Evaluate $\int_C \mathbf{F} \cdot d\mathbf{l}$ along the helix $\mathbf{r}(t) = (\cos t, \sin t, t)$ from $t = 0$ to $t = 2\pi$  
3. Compute $\iint_S (\nabla \times \mathbf{F}) \cdot d\mathbf{a}$ over the hemispherical surface $x^2 + y^2 + z^2 = 1$, $z \ge 0$, and verify Stokes' theorem

## Exercise 11 : Integration Identities

Prove the following:

1. $$ \int_S f(\nabla \times \mathbf{A}) \cdot d\mathbf{a} = \int_S [ \mathbf{A} \times (\nabla f) ] \cdot d\mathbf{a} + \oint_{\partial S} f\mathbf{A} \cdot d\mathbf{l} $$
2. $$ \int_V \mathbf{B} \cdot ( \nabla \times \mathbf{A}) \, d\tau = \int_V \mathbf{A} \cdot (\nabla \times \mathbf{B}) \, d\tau + \oint_{\partial V} ( \mathbf{A} \times \mathbf{B}) \cdot d\mathbf{a} $$