---
title: "Fourier Series; Harmonic Analysis"
date: 2026-01-08T08:34:49+01:00
# weight: 1
# aliases: ["/first"]
tags: ["Functional Analysis", "Fourier Series", "Harmonic Analysis", "Applied Mathematics"]
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

# Fourier Series; Harmonic Analysis

## Exercise 1 : Symmetric rectangular pulse

Obtain the Fourier series of the 2\pi-periodic function

$$
f(x)=\begin{cases}
0, & -\pi\le x< -\tfrac{\pi}{2},\\
1, & -\tfrac{\pi}{2}\le x< \tfrac{\pi}{2},\\
0, & \tfrac{\pi}{2}\le x\le \pi,
\end{cases}
$$

State whether the periodic extension is even or odd, compute the nonzero Fourier coefficients, and write the series in sine/cosine form.

## Exercise 2 : Odd square wave

For the 2\pi-periodic function

$$
f(x)=\begin{cases}
1, & -\pi\le x<0,\\
-1, & 0\le x\le\pi,
\end{cases}
$$

Compute the Fourier series, indicate whether only sine terms appear, and derive the explicit formula for the coefficients.

## Exercise 3 : Full-wave rectified sine

Find the Fourier series of

$$
f(x)=|\sin x|=\begin{cases}
-\sin x, & -\pi<x<0,\\
\sin x, & 0<x<\pi.
\end{cases}
$$

Determine whether the function is even or odd, compute the cosine-series coefficients, and write the series in closed form.

## Exercise 4 : Pulse with period 4/pi

Obtain the Fourier series for the function with period $4\pi$:

$$
f(x)=\begin{cases}
0, & -2\pi\le x< -\pi,\\
1, & -\pi\le x< \pi,\\
0, & \pi\le x<2\pi.
\end{cases}
$$

Give the Fourier coefficients and express the series.

## Exercise 5 : General rectangular pulse

Let $f$ be the $T$-periodic rectangular pulse of width $t_0$ and unit height:

$$
f(t)=\begin{cases}
0, & -\tfrac{T}{2}\le t< -\tfrac{t_0}{2},\\
1, & -\tfrac{t_0}{2}\le t\le \tfrac{t_0}{2},\\
0, & \tfrac{t_0}{2}<t<\tfrac{T}{2}.
\end{cases}
$$

Derive the Fourier series (both real and complex forms) and simplify the coefficients to closed form (sinc-type expressions).

## Exercise 6 : Triangular wave (continuous, even)

Consider the even, 2\pi-periodic triangular wave defined on $[-\pi,\pi]$ by

$$
f(x)=1-\frac{|x|}{\pi},\qquad -\pi\le x\le\pi.
$$

Compute the Fourier cosine series and show that coefficients decay as $1/n^2$.

## Exercise 7 : Sawtooth wave (odd)

For the 2\pi-periodic sawtooth function

$$
f(x)=\frac{x}{\pi},\qquad -\pi<x<\pi
$$

obtain the Fourier sine series (odd extension) and derive the coefficient formula; discuss convergence at discontinuities.

## Exercise 8 : Half-wave rectified sine

Define the half-wave rectified sine with period $2\pi$ by

$$
f(x)=\begin{cases}
\sin x, & 0<x<\pi,\\
0, & -\pi<x<0.
\end{cases}
$$

Find the Fourier series (both sine and cosine terms may appear) and compute the coefficients explicitly.

## Exercise 9 : Even and odd extensions

Given a function $g(x)$ defined on $[0,\pi]$, explain how to form the even and odd $2\pi$-periodic extensions. Then, for $g(x)=x$ on $[0,\pi]$, compute both the Fourier cosine series (even extension) and the Fourier sine series (odd extension).

## Exercise 10 : Parseval identity application

Use Parseval's identity to compute the sum of squared Fourier coefficients. As a concrete task, compute the Fourier series of $|\sin x|$ and use Parseval's identity to evaluate a related infinite sum (state which sum you evaluate and show the steps).

## Exercise 11 : Gibbs phenomenon

For the 2\pi-periodic square wave defined by
$$
f(x)=\begin{cases}
1, & -\pi\le x<0,\\
-1, & 0\le x\le\pi,
\end{cases}
$$
compute the $N$-term partial sums of the Fourier series near a jump and numerically or analytically show the overshoot (Gibbs phenomenon). Quantify the limiting overshoot as $N\to\infty$.

## Exercise 12 : Complex Fourier coefficients for pulses

Consider the $T$-periodic rectangular pulse of width $t_0$ and unit height:

$$
f(t)=\begin{cases}
0, & -\tfrac{T}{2}\le t< -\tfrac{t_0}{2},\\
1, & -\tfrac{t_0}{2}\le t\le \tfrac{t_0}{2},\\
0, & \tfrac{t_0}{2}<t<\tfrac{T}{2}.
\end{cases}
$$

Derive its complex Fourier coefficients $c_n$. Show equivalence between the complex form and the real sine/cosine form.
