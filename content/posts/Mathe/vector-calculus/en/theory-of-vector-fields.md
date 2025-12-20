---
title: "Theory of Vector Fields"
date: 2025-12-19T23:06:37+01:00
# weight: 1
# aliases: ["/first"]
tags: ["Vector Calculus", "Vector Fields"]
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

# Theory of Vector Fields

## Exercise 1 : Basic Operations on Vector Fields

Given the vector fields:
- $\mathbf{F}_1 = x^2 \hat{\mathbf{z}}$
- $\mathbf{F}_2 = x \hat{\mathbf{x}} + y \hat{\mathbf{y}} + z \hat{\mathbf{z}}$
- $\mathbf{F}_3 = yz\hat{x} + zx\hat{y} + xy\hat{z}$

1. Calculate $\nabla \cdot \mathbf{F}_i$ and $\nabla \times \mathbf{F}_i$ for $i=1,2,3$.
2. Which fields are conservative? Find scalar potentials where possible.
3. Which fields are solenoidal? Find vector potentials where possible.
4. Show that $\mathbf{F}_3$ can be expressed both as a gradient and a curl.

## Exercise 2 : Helmholtz Theorem Implications

For a vector field $\mathbf{F}$ in 3D, prove the following implications:

1. $\mathbf{F} = -\nabla V$ ⇒ $\nabla \times \mathbf{F} = \mathbf{0}$
2. $\nabla \times \mathbf{F} = \mathbf{0}$ ⇒ $\oint \mathbf{F} \cdot d\mathbf{l} = 0$
3. $\oint \mathbf{F} \cdot d\mathbf{l} = 0$ ⇒ $\mathbf{F} = -\nabla V$

## Exercise 3 : Divergence Theorem Applications

Check the divergence theorem for:

1. $\mathbf{v}_1 = r^2 \cos \theta \, \hat{\mathbf{r}} + r^2 \cos \phi \, \hat{\boldsymbol{\theta}} - r^2 \cos \theta \sin \phi \, \hat{\boldsymbol{\phi}}$
   Use one octant of a sphere of radius $R$. [Answer: $\pi R^4/4$]

2. $\mathbf{v}_2 = r^2 \sin \theta \, \hat{\mathbf{r}} + 4r^2 \cos \theta \, \hat{\boldsymbol{\theta}} + r^2 \tan \theta \, \hat{\boldsymbol{\phi}}$
   Use an "ice-cream cone" volume (spherical cap with cone). [Answer: $\frac{\pi R^4}{12}(2\pi + 3\sqrt{3})$]

## Exercise 4 : Stokes' Theorem Applications

Verify Stokes' theorem for:

1. $\mathbf{v}_1 = a y \, \hat{\mathbf{x}} + b x \, \hat{\mathbf{y}}$ over a circular path of radius $R$ in the $xy$-plane. [Answer: $\pi R^2(b-a)$]
2. $\mathbf{v}_2 = y \hat{\mathbf{z}}$ over a triangular surface. [Answer: $a^2$]

## Exercise 5 : Line Integrals and Stokes' Theorem

Compute the line integral of:

1. $\mathbf{v} = 6\hat{\mathbf{x}} + yz^2\hat{\mathbf{y}} + (3y+z)\hat{\mathbf{z}}$ along a triangular path. Verify with Stokes' theorem. [Answer: $8/3$]
2. $\mathbf{v} = (r\cos^2\theta)\hat{\mathbf{r}} - (r\cos\theta\sin\theta)\hat{\boldsymbol{\theta}} + 3r\hat{\boldsymbol{\phi}}$ around a specified path. [Answer: $3\pi/2$]

## Exercise 6 : Fundamental Theorem Relationships

1. Combine the gradient theorem corollary with Stokes' theorem. Show consistency with properties of second derivatives.
2. Combine the Stokes' theorem corollary with the divergence theorem. Show consistency.
3. Prove: $\nabla \times (\nabla T) = \mathbf{0}$ using integral theorems.
4. Prove: $\nabla \cdot (\nabla \times \mathbf{v}) = 0$ using integral theorems.

## Exercise 7 : Vector Calculus Identities

Prove these corollaries of the fundamental theorems:

1. $\int_V (\nabla T) \, d\tau = \oint_S T \, d\mathbf{a}$
2. $\int_V (\nabla \times \mathbf{v}) \, d\tau = -\oint_S \mathbf{v} \times d\mathbf{a}$
3. $\int_V [T\nabla^2 U + (\nabla T)\cdot(\nabla U)] \, d\tau = \oint_S (T\nabla U)\cdot d\mathbf{a}$
4. $\oint_S \nabla T \times d\mathbf{a} = -\oint_P T \, d\mathbf{l}$

## Exercise 8 : Vector Area Concept

For $\mathbf{a} \equiv \int_S d\mathbf{a}$:

1. Find $\mathbf{a}$ for a hemispherical bowl of radius $R$.
2. Prove $\mathbf{a} = \mathbf{0}$ for any closed surface.
3. Show $\mathbf{a}$ is invariant for surfaces with the same boundary.
4. Prove $\mathbf{a} = \frac{1}{2}\oint \mathbf{r} \times d\mathbf{l}$.
5. Show $\oint (\mathbf{c}\cdot\mathbf{r}) \, d\mathbf{l} = \mathbf{a} \times \mathbf{c}$ for constant $\mathbf{c}$.

## Exercise 9 : Delta Function Representations

1. Compute $\nabla \cdot (\hat{\mathbf{r}}/r)$ directly and via divergence theorem. Is there a delta function at the origin?
2. Find the general formula for $\nabla \cdot (r^n \hat{\mathbf{r}})$. [Answer: $(n+2)r^{n-1}$ except $n=-2$ gives $4\pi\delta^3(\mathbf{r})$]
3. Compute $\nabla \times (r^n \hat{\mathbf{r}})$. [Answer: $\mathbf{0}$]

## Exercise 10 : Regularized Laplacian

Consider $D(r,\epsilon) \equiv -\frac{1}{4\pi}\nabla^2\left(\frac{1}{\sqrt{r^2+\epsilon^2}}\right)$:

1. Show $D(r,\epsilon) = \frac{3\epsilon^2}{4\pi}(r^2+\epsilon^2)^{-5/2}$
2. Verify $D(0,\epsilon) \to \infty$ as $\epsilon \to 0$
3. Verify $D(r,\epsilon) \to 0$ as $\epsilon \to 0$ for $r \neq 0$
4. Show $\int_{\text{all space}} D(r,\epsilon) \, d\tau = 1$
5. Conclude $\nabla^2(1/r) = -4\pi\delta^3(\mathbf{r})$

## Exercise 11 : Conservative Field and Line Integral

For $\mathbf{F} = (2xy+z^3)\hat{\mathbf{x}} + x^2\hat{\mathbf{y}} + 3xz^2\hat{\mathbf{z}}$:

1. Is $\mathbf{F}$ conservative? If so, find its potential.
2. Compute $\nabla \times \mathbf{F}$.
3. Evaluate $\int_C \mathbf{F}\cdot d\mathbf{l}$ from $(0,0,0)$ to $(1,1,1)$ along $x=t, y=t^2, z=t^3$.

## Exercise 12 : Divergence & Stokes — Simple Examples

Verify both divergence and Stokes' theorems for $\mathbf{v} = x\hat{\mathbf{x}} + y\hat{\mathbf{y}} + z\hat{\mathbf{z}}$ over:

1. A cube of side length $a$
2. A sphere of radius $R$

## Exercise 13 : Vector Potentials for Common Fields

Find vector potentials for:

1. $\mathbf{B} = \frac{\mu_0 I}{2\pi}\frac{1}{r}\hat{\boldsymbol{\phi}}$ (magnetic field of a wire)
2. $\mathbf{B} = B_0\hat{\mathbf{z}}$ (uniform field)

## Exercise 14 : Uniqueness from Vanishing Divergence & Curl

Show that if $\nabla\cdot\mathbf{F} = 0$ and $\nabla\times\mathbf{F} = \mathbf{0}$ everywhere, and $\mathbf{F} \to 0$ at infinity, then $\mathbf{F} \equiv \mathbf{0}$.

## Exercise 15 : Coordinate-Free Vector Identities

Prove without using coordinates:

1. $\nabla \cdot (\mathbf{A} \times \mathbf{B}) = \mathbf{B}\cdot(\nabla\times\mathbf{A}) - \mathbf{A}\cdot(\nabla\times\mathbf{B})$
2. $\nabla \times (\mathbf{A} \times \mathbf{B}) = \mathbf{A}(\nabla\cdot\mathbf{B}) - \mathbf{B}(\nabla\cdot\mathbf{A}) + (\mathbf{B}\cdot\nabla)\mathbf{A} - (\mathbf{A}\cdot\nabla)\mathbf{B}$
3. $\nabla(\mathbf{A}\cdot\mathbf{B}) = \mathbf{A}\times(\nabla\times\mathbf{B}) + \mathbf{B}\times(\nabla\times\mathbf{A}) + (\mathbf{A}\cdot\nabla)\mathbf{B} + (\mathbf{B}\cdot\nabla)\mathbf{A}$