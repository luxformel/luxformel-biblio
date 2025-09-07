---
title: "Inner Products"
date: 2025-09-07T07:26:03+02:00
# weight: 1
# aliases: ["/first"]
tags: ["Linear Algebra", "Inner Products"]
categories: ["Mathé"]
author: "Damon"
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
searchHidden: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: true
ShowRssButtonInSectionTermList: true
UseHugoToc: true
---

# Inner Products

## Exercise 1 

Let $\mathbb{R}^2$ have the weighted Euclidean inner product:
$$ \langle u, v \rangle = 2u_1v_1 + 3u_2v_2  $$

and let $u = (1, 1)$, $v = (3, 2)$, $w = (0, -1)$, and $k = 3$. Compute the stated quantities.

1. $ \langle u,v \rangle $

2. $ \langle ku,w \rangle $

3. $ \langle u+v , w \rangle $

4. $ \| v \| $

5. $ d\langle u,v \rangle $

6. $ \| u-kv \| $


## Exercise 2

Let $\mathbb{R}^2$ have the weighted Euclidean inner product:

$$ \langle u, v \rangle = \frac{1}{2} u_1v_1 + 5u_2v_2 $$

and let $u = (1, 1)$, $v = (3, 2)$, $w = (0, -1)$, and $k = 3$. Compute the stated quantities.

1. $ \langle u,v \rangle $
   
2. $ \langle ku,w \rangle $
   
3. $ \langle u+v , w \rangle $
   
4. $ \| v \| $
   
5. $ d\langle u,v \rangle $
    
6.  $ \| u-kv \| $

## Exercise 3

Let $V = \mathbb{R}^3$ with the standard dot product. Let  
$ u = (1, -1, 2) $,  
$ v = (0, 1, 1) $,  
$ w = (-1, 1, 0) $.  

1. Compute $ \langle u, v \rangle $.
2. Are $ u $ and $ w $ orthogonal?
3. Find $ \| u \| $ and $ \| v \| $.
4. Compute $ \langle u + w, v \rangle $.
5. Compute the distance between $ u $ and $ v $.

## Exercise 4

Let the inner product on $\mathbb{R}^2$ be defined by the matrix $ A = \begin{pmatrix} 2 & 0 \\ 0 & 5 \end{pmatrix} $ via:

$$ \langle u, v \rangle_A = u^\top A v $$

with $ u = (1, 2), v = (-1, 1) $.

1. Compute $ \langle u, v \rangle_A $
2. Compute $ \| u \|_A $
3. Find if $ u $ and $ v $ are orthogonal under this inner product.
4. Compute the projection of $ v $ onto $ u $ under $ \langle \cdot, \cdot \rangle_A $.

## Exercise 5

Let $ f(x) = x $, $ g(x) = x^2 $, $ h(x) = 1 $ in the space $ C[0,1] $ with inner product:

$$ \langle f, g \rangle = \int_0^1 f(x)g(x) \, dx $$

1. Compute $ \langle f, g \rangle $
2. Compute $ \| f \| $
3. Check if $ f $ and $ h $ are orthogonal
4. Find the projection of $ g $ onto $ f $

## Exercise 6

Let $ V = \mathbb{R}^3 $ with inner product $ \langle u, v \rangle = u_1v_1 + 4u_2v_2 + u_3v_3 $. Let  

$ u = (1,2,0) $,  
$ v = (0,1,1) $,  
$ w = (1,1,1) $.  

1. Compute $ \langle u,v \rangle $
2. Compute $ \langle u, w \rangle $
3. Compute $ \| w \| $
4. Is $ v $ orthogonal to $ u $?
5. Find the angle between $ u $ and $ w $

## Exercise 7

Use the Gram-Schmidt process to orthonormalize the set $ \{ (1,1,0), (1,0,1) \} $ in $ \mathbb{R}^3 $ with the standard dot product.

1. Find the first orthonormal vector $ e_1 $
2. Find the second orthonormal vector $ e_2 $
3. Verify orthonormality of $ \{ e_1, e_2 \} $

## Exercise 8

Let $ u, v \in \mathbb{R}^n $ and let $ \langle u,v \rangle = u^\top B v $, where $ B $ is a symmetric positive definite matrix.

1. Prove that $ \langle \cdot, \cdot \rangle $ defines an inner product.
2. Show that $ \| u \| = \sqrt{\langle u, u \rangle} $ is a norm.
3. Give an example of such a matrix $ B $ and two vectors $ u, v \in \mathbb{R}^2 $, and compute $ \langle u, v \rangle $.

## Exercise 9

In $ \mathbb{R}^2 $ with standard inner product, let $ u = (3,4) $, $ v = (1,-2) $.

1. Normalize both vectors.
2. Compute the cosine of the angle between them.
3. Compute the projection of $ u $ onto $ v $.
4. Find the component of $ u $ orthogonal to $ v $.

## Exercise 10

Let $ f(x) = \sin(x) $, $ g(x) = \cos(x) $, and define the inner product over $ [0, 2\pi] $ as:

$$ \langle f, g \rangle = \int_0^{2\pi} f(x)g(x) \, dx $$

1. Compute $ \langle f, g \rangle $
2. Are $ f $ and $ g $ orthogonal?
3. Compute $ \| f \| $ and $ \| g \| $
4. Normalize $ f $ and $ g $

## Exercise 11

Let $ \mathbb{C}^2 $ have the Hermitian inner product:

$$
\langle u, v \rangle = u_1\overline{v_1} + u_2\overline{v_2}
$$

with $ u = (1+i, 2), v = (i, 3-i) $.

1. Compute $ \langle u, v \rangle $
2. Verify that $ \langle v, u \rangle = \overline{\langle u, v \rangle} $
3. Compute $ \| u \| $ and $ \| v \| $
4. Are $ u $ and $ v $ orthogonal?

## Exercise 12

Let $ P_2 $ be the space of real polynomials of degree $\leq$ 2, with inner product:

$$
\langle f, g \rangle = \int_{-1}^1 f(x)g(x) \, dx
$$

Let $ f(x) = 1+x $, $ g(x) = x $, and $ h(x) = x^2 $.

1. Compute $ \langle f, g \rangle $
2. Compute $ \langle g, h \rangle $
3. Determine whether $ g $ is orthogonal to $ h $
4. Orthonormalize $ \{1, x, x^2\} $ using Gram-Schmidt

## Exercise 13

Let $ u = (1,2,3), v = (4,5,6) $ in $ \mathbb{R}^3 $ with the standard inner product.

1. Prove the Cauchy-Schwarz inequality:
   $$ |\langle u, v \rangle| \leq \|u\| \cdot \|v\| $$
2. Verify the equality numerically
3. Prove the triangle inequality:
   $$ \|u + v\| \leq \|u\| + \|v\| $$

## Exercise 14

Let $ V $ be the space of continuous functions on $[0,1]$, and define the inner product:

$$
\langle f, g \rangle = \int_0^1 f(x)g(x) \, dx
$$

Let $ f(x) = x $, $ g(x) = x - \frac{1}{2} $, $ h(x) = 1 $.

1. Compute $ \langle f, g \rangle $
2. Show that $ g $ is orthogonal to $ h $
3. Find the projection of $ f $ onto the span of $ g $
4. Find an orthonormal basis of $ \text{span}\{f, h\} $

## Exercise 15

Let $ V = \mathbb{R}^3 $, and define the inner product by:

$$
\langle u, v \rangle = u^\top M v, \quad \text{where } M = \begin{pmatrix} 1 & 1 & 0 \\ 1 & 2 & 1 \\ 0 & 1 & 2 \end{pmatrix}
$$

Let $ u = (1,0,1), v = (0,1,1) $.

1. Compute $ \langle u, v \rangle $
2. Compute $ \| u \| $
3. Is this matrix $ M $ positive definite? Justify.
4. Are $ u $ and $ v $ orthogonal in this inner product?

## Exercise 16

Let $ f(x) = e^x $, $ g(x) = e^{-x} $, and define:

$$
\langle f, g \rangle = \int_0^1 f(x)g(x) \, dx
$$

1. Compute $ \langle f, g \rangle $
2. Find $ \| f \| $
3. Normalize $ f $ and $ g $
4. Are they orthogonal?

## Exercise 17

Prove the following general properties of inner products:

1. $ \langle u, u \rangle \geq 0 $, and equality holds iff $ u = 0 $
2. $ \langle u, v \rangle = \overline{\langle v, u \rangle} $
3. $ \langle au + bv, w \rangle = a\langle u, w \rangle + b\langle v, w \rangle $, for scalars $ a, b $

Then give explicit examples in $ \mathbb{R}^2 $ or $ \mathbb{C}^2 $.

## Exercise 18

Let $ u = (1,2), v = (3,4) $, and consider an inner product defined by:

$$
\langle u, v \rangle = u_1v_1 + k u_2v_2
$$

1. For what value of $ k > 0 $ are $ u $ and $ v $ orthogonal?
2. Compute $ \| u \| $ and $ \| v \| $ for $ k = 2 $
3. Prove that this defines an inner product if $ k > 0 $

## Exercise 19

Let $ V = \mathbb{R}^4 $ with the dot product. Let:

$ u = (1, 0, 1, 0) $,  
$ v = (0, 1, 0, 1) $,  
$ w = (1, 1, -1, -1) $

1. Check whether $ u $ and $ v $ form an orthonormal set
2. Compute $ \text{proj}_{\text{span}(u,v)}(w) $
3. Find the component of $ w $ orthogonal to $ \text{span}(u,v) $

## Exercise 20

True or False? Justify with a proof or counterexample:

1. If $ \langle u, v \rangle = 0 $, then $ u = 0 $ or $ v = 0 $
2. Every inner product space has an orthonormal basis
3. The inner product of two orthogonal vectors is always 1
4. Norm induced by an inner product satisfies the triangle inequality
