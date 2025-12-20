---
title: "Vector Algebra"
date: 2025-12-19T18:12:08+01:00
# weight: 1
# aliases: ["/first"]
tags: ["Vector Calculus", "Vectors"]
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

# Vector Algebra

## Exercise 1 : Distributivity of Dot and Cross

Prove that the dot and cross products are distributive, using definitions and diagrams:

1. for three coplanar vectors
2. in the general case

## Exercise 2 : Cross Product Associativity?

Is the cross product associative? That is, does the following hold? 
$$ (A \times B) \times C = A \times (B \times C) $$ 
Prove or provide a counterexample.

## Exercise 3 : BAC-CAB Identity

Prove the vector identity:  
$A \times (B \times C) = B\,(A \cdot C) - C\,(A \cdot B)$ (the *BAC-CAB* rule) by writing both sides in component form.

## Exercise 4 : Jacobi Identity

Verify the Jacobi identity:  
$$[A \times (B \times C)] + [B \times (C \times A)] + [C \times (A \times B)] = 0$$  
Under what condition does $A \times (B \times C) = (A \times B) \times C$?

## Exercise 5 : Cyclic Cross Products

Show that if $A + B + C = 0$, then $A \times B = B \times C = C \times A$.

## Exercise 6 : Angle Between Body Diagonals

Find the angle between the body diagonals of a cube.

## Exercise 7 : Unit Normal to a Plane

Find the components of the unit vector perpendicular to a plane defined by three given points or a diagram.

## Exercise 8 : Rotation Matrices

1. Prove that the 2D rotation matrix preserves dot products.  
2. What constraints must the elements $R_{ij}$ of a 3D rotation matrix satisfy to preserve vector lengths?

## Exercise 9 : 120° Rotation About (1,1,1)

Find the transformation matrix for a $120^\circ$ clockwise rotation about the axis through $(1,1,1)$.


## Exercise 10 : Coordinate Transformations

How do vector components transform under:

1. translation: $\bar{x}=x,\ \bar{y}=y-a,\ \bar{z}=z$?
2. inversion: $\bar{x}=-x,\ \bar{y}=-y,\ \bar{z}=-z$?
3. How does a cross product transform under inversion? Is the cross product of two pseudovectors a vector or pseudovector? Give two examples of pseudovectors in mechanics.
5. How does the scalar triple product transform under inversion?

## Exercise 11 : Divergence as a Scalar (2D)

Show that in two dimensions, the divergence transforms as a scalar under rotations.

## Exercise 12 : Gradient Transforms as a Vector

Show that the gradient of a scalar function transforms as a vector under rotations.

## Exercise 13 : Compute Gradients

Compute the gradient of:

1. $f(x,y,z) = x^2 + y^3 + z^4$
2. $f(x,y,z) = x^2 y^3 z^4$
3. $f(x,y,z) = e^x \sin y \ln z$

## Exercise 14 : Hilltop and Slope

For the hill height \(h(x,y) = 10(2xy - 3x^2 - 4y^2 - 18x + 28y + 12)\):

1. Locate the top of the hill.
2. Find its height.
3. Find the slope (in ft/mi) and direction of steepest ascent at \((1,1)\).

## Exercise 15 : Gradients of Powers of r

For $r$ from $(x',y',z')$ to $(x,y,z)$ with $r = |r|$:

1. Show $\nabla(r^2) = 2r$
2. Show $\nabla(1/r) = -\hat{r}/r^2$
3. Find $\nabla(r^n)$ for integer $n$.

## Exercise 16 : Divergence Calculations

Calculate the divergence of and divergence of:

1. $v_a = x^2\hat{x} + 3xz^2\hat{y} - 2xz\hat{z}$
2. $v_b = xy\hat{x} + 2yz\hat{y} + 3zx\hat{z}$
3. $v_c = y^2\hat{x} + (2xy+z^2)\hat{y} + 2yz\hat{z}$

## Exercise 17 : Divergence of Radial Field

Sketch $v = \hat{r}/r^2$ and compute its divergence. Explain any surprising result.

## Exercise 18 : Tangential Field Curl

For a clockwise-tangential vector field around a circle in the $xy$-plane:

1. Determine signs of $\partial v_x/\partial y$ and $\partial v_y/\partial x$
2. Find the direction of $\nabla \times {v}$ and interpret geometrically.

## Exercise 19 : Vector Calculus Identities

Verify these identities for arbitrary scalar field $\phi$ and vector field ${v}$:

1. $\nabla \cdot (\phi {v}) = \phi(\nabla \cdot {v}) + {v} \cdot (\nabla \phi)$
2. $\nabla \times (\phi {v}) = \phi(\nabla \times {v}) - {v} \times (\nabla \phi)$
Verify these identities for arbitrary scalar field $\phi$ and vector field $v$:

1. $\nabla \cdot (\phi v) = \phi(\nabla \cdot v) + v \cdot (\nabla \phi)$
2. $\nabla \times (\phi v) = \phi(\nabla \times v) - v \times (\nabla \phi)$

## Exercise 20 : Electrostatic Field Candidates

Which of the following vector fields could represent an electrostatic field? (Electrostatic fields have zero curl.)

1. $y\hat{x} + x\hat{y}$
2. $y\hat{x} - x\hat{y}$
3. $x\hat{x} + y\hat{y}$
4. $x^2\hat{x} + 2xy\hat{y}$

## Exercise 21 : Separation Vector

Find the separation vector from source point $(2,8,7)$ to field point $(4,6,8)$. Determine its magnitude and unit vector.

## Exercise 22 : Point Charge Field Properties

If $E = kq\frac{r}{r^3}$ is the electric field of a point charge, verify that:

1. $\nabla \cdot E = 0$ for $r \neq 0$
2. $\nabla \times E = 0$ for $r \neq 0$
  (What happens at $r=0$?)

## Exercise 23 : Line Integrals and Conservativeness

For a vector function ${F} = (3x^2 + 2y)\hat{x} + (x - 4y^3)\hat{y}$:

1. Compute the line integral from $(0,0)$ to $(1,1)$ along the path $y=x^2$
2. Compute the same integral along the straight line $y=x$
3. Is ${F}$ conservative? Explain.