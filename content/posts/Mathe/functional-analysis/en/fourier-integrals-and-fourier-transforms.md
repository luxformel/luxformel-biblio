---
title: "Fourier Integrals and Fourier Transforms"
date: 2026-01-08T08:39:41+01:00
# weight: 1
# aliases: ["/first"]
tags: ["Functional Analysis", "Fourier Integrals", "Fourier Transforms", "Applied Mathematics"]
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

# Fourier Integrals and Fourier Transforms

## Exercise 1 : Fourier Series

For the following periodic function:
$$
f(t) = 
\begin{cases} 
-1 & \text{for } -\frac{T}{2} \leq t < 0 \\
1 & \text{for } 0 < t \leq \frac{T}{2}
\end{cases}
$$
Calculate the Fourier series for
$$
f(t) = 
\begin{cases} 
0 & \text{for } -\frac{T}{2} \leq t < -\frac{t_0}{2} \\
-1 & \text{for } -\frac{t_0}{2} \leq t < 0 \\
1 & \text{for } 0 < t \leq \frac{t_0}{2} \\
0 & \text{for } \frac{t_0}{2} < t \leq \frac{T}{2}
\end{cases}
$$

## Exercise 2 : Limiting Spectrum (T \to \infty)

Now perform the limiting process for $T \to \infty$ and obtain the amplitude spectrum.

## Exercise 3 : Spectral Sketches for Varying Periods

Sketch the frequency spectrum of the Fourier series for $T = t_0$ and $T = 2t_0$, $T = 4t_0$ and $T = 8t_0$ and then the amplitude spectrum of the Fourier integral.

## Exercise 4 : Complex Fourier Transform of the Pulse

Perform the Fourier transform in the complex representation for the function given in exercise 1 and obtain the amplitude function and the amplitude spectrum:

$$
f(t) = 
\begin{cases} 
-1 & \text{for } -\frac{t_0}{2} \leq t < 0 \\
1 & \text{for } 0 < t \leq \frac{t_0}{2}
\end{cases}
$$

## Exercise 5 : Amplitude Spectra for Different $t_0$

Sketch the function and the amplitude spectrum for the preceding exercise for $t_0 = 1$, $t_0 = 2$ and $t_0 = 4$.

## Exercise 6 : Shifted Pulse — Arbitrary Position

Determine amplitude function and amplitude spectrum for the function of the preceding exercise in an arbitrary position:

$$
f(t) = 
\begin{cases} 
1 & \text{for } t_1 < t \leq t_1 + \frac{t_0}{2}
\end{cases}
$$

## Exercise 7 : Convolution and Triangular Pulse

Let $g(t)$ be the rectangular pulse of width $t_0$ and unit amplitude centered at the origin (the pulse from Exercise 4 with $t_1=0$).

1. Compute the convolution $h(t)=g(t)*g(t)$ and show that $h(t)$ is a triangular pulse. Give an explicit expression for $h(t)$.
2. Using the Fourier transform, derive the amplitude function $H(\omega)$ and show how it relates to $G(\omega)$ (the transform of $g$).
3. Sketch the amplitude spectrum of $h(t)$ and compare it to the squared magnitude $|G(\omega)|^2$.

## Exercise 8 : Parseval's Theorem — Energy Equality

For the rectangular pulse $g(t)$ of width $t_0$ and unit amplitude:

1. Compute the signal energy $E=\int_{-\infty}^{\infty} |g(t)|^2\,dt$ directly.
2. Compute the energy using the Fourier transform via Parseval's theorem and verify both results agree.

## Exercise 9 : Modulation and Frequency Shifting

Let $g(t)$ be a finite-duration signal with Fourier transform $G(\omega)$.

1. Show that the modulated signal $g_m(t)=g(t)\cos(\omega_0 t)$ has a Fourier transform consisting of two shifted copies of $G(\omega)$ and write the expression for $G_m(\omega)$.
2. For the rectangular pulse from Exercise 4, compute and sketch the amplitude spectrum of $g_m(t)$ for $\omega_0 = 2\pi,\,4\pi$.

## Exercise 10 : Time Scaling and Bandwidth

Consider the time-scaled signal $g_a(t)=g(at)$ for real nonzero $a$.

1. Derive the relation between $G_a(\omega)$ and $G(\omega)$, and explain how time compression/expansion affects the amplitude spectrum and effective bandwidth.
2. For the rectangular pulse with $t_0=1$, sketch amplitude spectra for $a=0.5,\;1,\;2$.

## Exercise 11 : Sampling, Aliasing and the Poisson Summation Formula

Let $g(t)$ be bandlimited with transform $G(\omega)$ supported in $|\omega|\leq \Omega_m$.

1. Describe ideal sampling at period $T_s$ (multiplying by a comb) and derive the sampled-spectrum using the Poisson summation formula.
2. Determine the sampling condition to avoid aliasing and illustrate with sketches when $T_s$ is too large and when $T_s$ satisfies the Nyquist requirement.

## Exercise 12 : Gaussian Pulse — Transform and Properties

Let $g(t)=e^{-\alpha t^2}$ with $\alpha>0$.

1. Compute the Fourier transform $G(\omega)$ in closed form (you may use standard integrals) and show that it is a Gaussian in $\omega$.
2. Discuss the time–bandwidth product for this pulse and show that scaling $\alpha$ trades time-spread for frequency-spread.

## Exercise 13 : Hilbert Transform and Analytic Signal

Define the Hilbert transform $\mathcal{H}\{g\}(t)$ and the analytic signal $g_a(t)=g(t)+i\,\mathcal{H}\{g\}(t)$.

1. For a simple cosine $g(t)=\cos(\omega_0 t)$, compute the Hilbert transform and the analytic signal explicitly.
2. For a one-sided rectangular pulse (nonzero only for $t>0$), discuss qualitatively how the Hilbert transform affects the phase of the Fourier spectrum.

## Exercise 14 : Windowing, Spectral Leakage and Resolution

Take the infinite-duration sinusoid $s(t)=\cos(\omega_0 t)$ and multiply it by a finite window $w(t)$ (rectangular, Hamming, and Hann windows of duration $T_w$).

1. For each window, compute or sketch the resulting amplitude spectrum and point out main-lobe width and side-lobe behavior.
2. Discuss how window choice and window length $T_w$ affect frequency resolution and leakage. Provide sketches for $T_w=1,\;2,\;4$ and $\omega_0=5$.
