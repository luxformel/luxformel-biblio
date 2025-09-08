---
title: "Wave Function"
date: 2025-09-07T08:38:35+02:00
# weight: 1
# aliases: ["/first"]
tags: ["Quantum Mechanics", "Waves" ,"Wave Function"]
categories: ["Physik"]
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

# Wave Function

## Exercise 1

Consider the Gaussian distribution  
$$
\rho(x) = Ae^{-\lambda(x - a)^2}
$$  
where $ A, a, \lambda $ are positive real constants.

1. Use the normalization condition $\int_{-\infty}^{+\infty} \rho(x)\, dx = 1$ to determine $A$.  
2. Find $\langle x \rangle$, $\langle x^2 \rangle$, and the standard deviation $\sigma$.  
3. Sketch the graph of $\rho(x)$.

## Exercise 2

At time $ t = 0 $, a particle is represented by the wave function:
$$
\Psi(x, 0) = 
\begin{cases} 
A(x/a), & 0 \leq x \leq a \\
A(b - x)/(b - a), & a \leq x \leq b \\
0, & \text{otherwise}
\end{cases}
$$
where $ A, a, b $ are positive constants.

1. Find $A$ in terms of $a$ and $b$.  
2. Sketch $\Psi(x, 0)$.  
3. Where is the particle most likely to be found at $t = 0$?  
4. Compute $P(x < a)$ and verify your result for:  
   - $b = a$  
   - $b = 2a$  
5. Calculate $\langle x \rangle$.

## Exercise 3

Given the wave function:
$$
\Psi(x,t) = Ae^{-\lambda|x|}e^{-i\omega t}
$$
with $A, \lambda, \omega > 0$:

1. Normalize $\Psi$.  
2. Compute $\langle x \rangle$, $\langle x^2 \rangle$, and the standard deviation $\sigma_x$.  
3. Sketch $|\Psi(x,t)|^2$ and mark $\langle x \rangle \pm \sigma_x$.  
4. What is the probability that the particle lies outside this interval?

## Exercise 4

Why can't you perform integration by parts directly on the expression:
$$
\frac{d \langle x \rangle}{dt} = \int x \frac{\partial}{\partial t} |\Psi|^2\, dx = \frac{i \hbar}{2m} \int x \frac{\partial}{\partial t} \left( \Psi^* \frac{\partial \Psi}{\partial x} - \frac{\partial \Psi^*}{\partial x} \Psi \right)\, dx
$$
and then pull the time derivative onto $x$, claiming $\partial x/\partial t = 0$, and conclude that $\frac{d\langle x \rangle}{dt} = 0$? Discuss the mistake.

## Exercise 5

Calculate the time derivative of the expectation value of momentum:
$$
\frac{d\langle p \rangle}{dt} = \left\langle -\frac{\partial V}{\partial x} \right\rangle
$$
This is Ehrenfest's theorem, showing correspondence with Newton's law.

## Exercise 6

Suppose the potential energy is shifted by a constant: $V(x) \to V(x) + V_0$, where $V_0$ is independent of $x$ and $t$.

1. Show that the wave function picks up a phase factor $\exp(-iV_0 t/\hbar)$.  
2. What effect does this phase have on expectation values of observables?

## Exercise 7

A particle of mass $m$ has wave function:
$$
\Psi(x, t) = A e^{-a\left[\frac{m x^2}{\hbar} + i t\right]}
$$

1. Find the normalization constant $A$.  
2. For what potential $V(x)$ is this a solution of the Schrödinger equation?  
3. Compute $\langle x \rangle$, $\langle x^2 \rangle$, $\langle p \rangle$, $\langle p^2 \rangle$.  
4. Compute $\sigma_x$, $\sigma_p$, and check if the uncertainty principle is satisfied.

## Exercise 8

A classical particle of mass $m$ moves in a potential $V(x)$ between turning points $a$ and $b$.

1. Show that $\rho(x) = 1 / (v(x)T)$ using energy conservation and derive $v(x)$.  
2. For a harmonic oscillator $V(x) = \frac{1}{2} k x^2$, find and plot $\rho(x)$. Normalize it.  
3. Find $\langle x \rangle$, $\langle x^2 \rangle$, and $\sigma_x$.

## Exercise 9

Now consider momentum in the classical harmonic oscillator.

1. Derive the classical probability distribution $\rho(p)$.  
2. Find $\langle p \rangle$, $\langle p^2 \rangle$, and $\sigma_p$.  
3. Compute $\sigma_x \sigma_p$. Discuss what happens as $E \to 0$ and compare to the quantum minimum.

## Exercise 10

Let $P_{ab}(t)$ be the probability of finding the particle between $a$ and $b$.

1. Show that:
$$
\frac{dP_{ab}}{dt} = J(a, t) - J(b, t)
$$
where
$$
J(x, t) = \frac{i\hbar}{2m} \left( \psi \frac{\partial \psi^*}{\partial x} - \psi^* \frac{\partial \psi}{\partial x} \right)
$$
2. What are the units of $J(x, t)$?  
3. Find $J(x, t)$ for $\Psi(x, t) = A e^{-a\left[(m x^2/\hbar)+i t\right]}$.

## Exercise 11

Show that:
$$
\frac{d}{dt} \int_{-\infty}^{\infty} \psi_1^*(x,t) \psi_2(x,t)\, dx = 0
$$
for any two solutions $\psi_1$, $\psi_2$ of the Schrödinger equation with the same $V(x)$.

## Exercise 12

At time $t = 0$, the wave function is:
$$
\psi(x, 0) = 
\begin{cases} 
A(a^2 - x^2), & -a \leq x \leq a \\
0, & \text{otherwise}
\end{cases}
$$

1. Normalize $\psi(x)$.  
2. Compute $\langle x \rangle$, $\langle x^2 \rangle$, $\langle p \rangle$, $\langle p^2 \rangle$.  
3. Find $\sigma_x$, $\sigma_p$, and verify the uncertainty principle.

## Exercise 13

Suppose the total probability decays exponentially:
$$
P(t) = \int |\psi(x,t)|^2 dx = e^{-t/\tau}
$$

If $V = V_0 - i\Gamma$, show that:

1. $\frac{dP}{dt} = -\frac{2\Gamma}{\hbar} P$
2. Solve for $P(t)$ and express $\tau$ in terms of $\Gamma$.

## Exercise 14

Quantum mechanics applies when the de Broglie wavelength is greater than system size.

1. For a solid with lattice spacing $d = 0.3$ nm, find temperatures below which electrons and nuclei are quantum mechanical (use silicon).  
2. For a gas, derive a condition on $T$ and $P$ for quantum behavior.


## Exercise 15 : Fourier Transform

Given $\psi(x) = \left( \frac{\alpha}{\pi} \right)^{1/4} e^{-\alpha x^2/2}$:

1. Find $\phi(p)$ via Fourier transform.  
2. Show $\phi(p)$ is normalized.  
3. Compute $\langle p \rangle$, $\langle p^2 \rangle$, and $\sigma_p$.  
4. Compare $\sigma_x \sigma_p$ with the uncertainty principle.

## Exercise 16 : Energy in Infinite Well

For $\psi_n(x) = \sqrt{2/L} \sin(n\pi x/L)$:

1. Find $\langle x \rangle$, $\langle x^2 \rangle$, $\sigma_x$.  
2. Find $\langle E \rangle$ and verify it matches $E_n = \frac{n^2 \pi^2 \hbar^2}{2mL^2}$.

## Exercise 17 : Time Evolution of a Superposition

Let:
$$
\psi(x, 0) = \frac{1}{\sqrt{2}} \psi_1(x) + \frac{1}{\sqrt{2}} \psi_2(x)
$$

1. Find $\psi(x, t)$.  
2. Compute $|\psi(x,t)|^2$ and determine if it's time-dependent.  
3. Compute $\langle x \rangle(t)$ and discuss its behavior.  
4. Explain the physics of this non-stationary state.

