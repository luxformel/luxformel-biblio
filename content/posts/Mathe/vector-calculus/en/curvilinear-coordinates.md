---
title: "Curvilinear Coordinates"
date: 2025-12-18T14:00:11+01:00
# weight: 1
# aliases: ["/first"]
tags: ["Vector Calculus", "Coordinates"]
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

# Curvilinear Coordinates

## Exercise 1 : Inverting Spherical Coordinates

Invert the transformation $x = r\sin\theta\cos\phi$, $y = r\sin\theta\sin\phi$, $z = r\cos\theta$ to express $(r, \theta, \phi)$ in terms of $(x, y, z)$.

## Exercise 2 : Coordinate Examples (Conversions)

Invert the transformation $x = r\sin\theta\cos\phi$, $y = r\sin\theta\sin\phi$, $z = r\cos\theta$ to express $(r, \theta, \phi)$ in terms of $(x, y, z)$.

1. Express the point $(x, y, z) = (2, -2, 1)$ in spherical and cylindrical coordinates.
2. Express $(r, \theta, \phi) = (3, \pi/3, \pi/4)$ in Cartesian coordinates.
3. Express $(s, \phi, z) = (4, 5\pi/6, -2)$ in Cartesian coordinates.

## Exercise 3 : Spherical Unit Vectors

Express the spherical unit vectors $\hat{\mathbf{r}}$, $\hat{\boldsymbol{\theta}}$, $\hat{\boldsymbol{\phi}}$ in terms of the Cartesian unit vectors $\hat{\mathbf{x}}$, $\hat{\mathbf{y}}$, $\hat{\mathbf{z}}$, i.e., derive:

$$
\begin{aligned}
\hat{\mathbf{r}} &= \sin\theta\cos\phi\,\hat{\mathbf{x}} + \sin\theta\sin\phi\,\hat{\mathbf{y}} + \cos\theta\,\hat{\mathbf{z}}, \\
\hat{\boldsymbol{\theta}} &= \cos\theta\cos\phi\,\hat{\mathbf{x}} + \cos\theta\sin\phi\,\hat{\mathbf{y}} - \sin\theta\,\hat{\mathbf{z}}, \\
\hat{\boldsymbol{\phi}} &= -\sin\phi\,\hat{\mathbf{x}} + \cos\phi\,\hat{\mathbf{y}}.
\end{aligned}
$$

Verify by also finding the inverse relations expressing $\hat{\mathbf{x}}$, $\hat{\mathbf{y}}$, $\hat{\mathbf{z}}$ in terms of $\hat{\mathbf{r}}$, $\hat{\boldsymbol{\theta}}$, $\hat{\boldsymbol{\phi}}$.

## Exercise 4 : Cylindrical Unit Vectors

Express the cylindrical unit vectors $\hat{\mathbf{s}}$, $\hat{\boldsymbol{\phi}}$, $\hat{\mathbf{z}}$ in terms of the Cartesian unit vectors:

$$
\begin{aligned}
\hat{\mathbf{s}} &= \cos\phi\,\hat{\mathbf{x}} + \sin\phi\,\hat{\mathbf{y}}, \\
\hat{\boldsymbol{\phi}} &= -\sin\phi\,\hat{\mathbf{x}} + \cos\phi\,\hat{\mathbf{y}}, \\
\hat{\mathbf{z}} &= \hat{\mathbf{z}}.
\end{aligned}
$$

Invert these formulas to get $\hat{\mathbf{x}}$, $\hat{\mathbf{y}}$, $\hat{\mathbf{z}}$ in terms of $\hat{\mathbf{s}}$, $\hat{\boldsymbol{\phi}}$, $\hat{\mathbf{z}}$.

## Exercise 5 : Unit Vector Relationships

Unit vector relationships:

1. Show that $\hat{\mathbf{r}} \cdot \hat{\boldsymbol{\theta}} = 0$ and $\hat{\boldsymbol{\theta}} \cdot \hat{\boldsymbol{\phi}} = 0$ using their Cartesian representations from Problem 1.38.
2. Prove that $\frac{\partial \hat{\mathbf{r}}}{\partial \phi} = \sin\theta\,\hat{\boldsymbol{\phi}}$.
3. Find $\frac{\partial \hat{\boldsymbol{\theta}}}{\partial \theta}$ and $\frac{\partial \hat{\boldsymbol{\phi}}}{\partial \phi}$.

## Exercise 6 : Vector Operations in Spherical Coordinates

Vector operations practice:

1. Compute $\nabla r$, $\nabla \theta$, and $\nabla \phi$ in spherical coordinates.
2. Verify that $\nabla \times (\nabla T) = 0$ for $T = r^2 \sin \theta \cos \phi$.

## Exercise 7 : Gradient and Laplacian Practice

For the scalar function $T = r(\cos \theta + \sin \theta \cos \phi)$:

1. Compute $\nabla T$ and $\nabla^2 T$ in spherical coordinates.
2. Verify $\nabla^2 T$ by converting $T$ to Cartesian coordinates and using $\nabla^2 T = \frac{\partial^2 T}{\partial x^2} + \frac{\partial^2 T}{\partial y^2} + \frac{\partial^2 T}{\partial z^2}$.
3. Test the gradient theorem $\int_a^b (\nabla T)\cdot d\mathbf{l} = T(b) - T(a)$ along the path from $(0,0,0)$ to $(0,0,2)$ shown in the figure.

## Exercise 8 : Divergence in Spherical Coordinates

For the vector field $\mathbf{v} = (r \cos \theta) \hat{\mathbf{r}} + (r \sin \theta) \hat{\boldsymbol{\theta}} + (r \sin \theta \cos \phi) \hat{\boldsymbol{\phi}}$:

1. Compute $\nabla \cdot \mathbf{v}$.
2. Verify the divergence theorem using the inverted hemispherical bowl of radius $R$ resting on the $xy$-plane and centered at the origin.

## Exercise 9 : Divergence and Curl Examples

Divergence and curl computations:

1. Compute $\nabla \cdot (r^n \hat{\mathbf{r}})$ for arbitrary $n$.
2. For $\mathbf{A} = f(r)\hat{\mathbf{r}}$, show that $\nabla \times \mathbf{A} = 0$.

## Exercise 10 : Radial Functions — Laplacian & Curl

Challenging problem: For an arbitrary scalar function $f(r)$ and vector function $\mathbf{g}(r)\hat{\mathbf{r}}$:

1. Show that $\nabla^2 f(r) = \frac{1}{r^2}\frac{d}{dr}\left(r^2\frac{df}{dr}\right)$.
2. Prove that $\nabla \times [\mathbf{g}(r)\hat{\mathbf{r}}] = 0$.
3. Find the most general form of $\mathbf{v}(r,\theta,\phi)$ such that $\nabla \times \mathbf{v} = 0$ in spherical coordinates.

## Exercise 11 : Gradients in Cylindrical Coordinates

Compute $\nabla s$, $\nabla \phi$, and $\nabla z$ in cylindrical coordinates.

## Exercise 12 : Cylindrical Divergence & Curl

For $\mathbf{v} = s(2 + \sin^2\phi)\,\hat{\mathbf{s}} + s\sin\phi\cos\phi\,\hat{\boldsymbol{\phi}} + 3z\,\hat{\mathbf{z}}$:

1. Compute $\nabla \cdot \mathbf{v}$ in cylindrical coordinates.
2. Compute $\nabla \times \mathbf{v}$.
3. Verify the divergence theorem using the quarter-cylinder defined by $0 \leq s \leq 2$, $0 \leq \phi \leq \pi/2$, $0 \leq z \leq 5$.

## Exercise 13 : Curl in Cylindrical Coordinates

Compute $\nabla \times (\phi \hat{\mathbf{z}})$ in cylindrical coordinates.

## Exercise 14 : Divergence Theorem Applications

Verify the divergence theorem $\int_{\mathcal{V}} (\nabla\cdot\mathbf{v})\,d\tau = \oint_{\mathcal{S}} \mathbf{v}\cdot d\mathbf{a}$ for:

1. $\mathbf{v}_1 = r^2 \hat{\mathbf{r}}$ over a sphere of radius $R$ centered at the origin.
2. $\mathbf{v}_2 = (1/r^2) \hat{\mathbf{r}}$ over the same volume. Compare with Problem 1.16.

## Exercise 15 : Volume and Surface Elements

Volume and surface elements:

1. Derive the spherical volume element $d\tau = r^2\sin\theta\,dr\,d\theta\,d\phi$ from the Jacobian determinant.
2. Derive the cylindrical surface element $da = s\,d\phi\,dz$ for a surface of constant $s$.
3. Find the area element on a sphere of radius $R$ (constant $r$ surface).

## Exercise 16 : Coordinate Representations of a Field

Practical applications:

1. Express the vector field $\mathbf{F} = -y\hat{\mathbf{x}} + x\hat{\mathbf{y}}$ in both cylindrical and spherical coordinates.
2. Compute $\nabla \cdot \mathbf{F}$ and $\nabla \times \mathbf{F}$ in all three coordinate systems.
3. What physical field does $\mathbf{F}$ represent?

## Exercise 17 : Laplacian in Spherical Symmetry

Derive the expression for the Laplacian $\nabla^2 f(r)$ in spherical coordinates for functions depending only on $r$, and apply it to $f(r)=1/r$.

## Exercise 18 : Poisson's Equation (Radial)

Solve Poisson's equation $\nabla^2 V(r) = -\rho(r)/\epsilon_0$ for a spherically symmetric charge density $\rho(r)=\rho_0$ for $r<R$ and $0$ for $r>R$, matching boundary conditions at $r=R$.

## Exercise 19 : Divergence Theorem on a Cone

Use the divergence theorem to compute the flux of $\mathbf{F}=r^n\hat{\mathbf{r}}$ outward through the surface of a right circular cone of height $h$ and base radius $a$ (centered on the z-axis).