---
title: "Laplace Transforms"
date: 2026-01-08T11:04:12+01:00
# weight: 1
# aliases: ["/first"]
tags: ["Differential Equations", "Applied Mathematics"]
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

# Laplace Transforms

## Exercise 1 : Applying Laplace Transforms

Obtain the Laplace transforms for the following functions:

1. $\frac{1}{4}t^3$
2. $5e^{-2t}$
3. $4\cos 3t$
4. $\sin^2 t$

## Exercise 2 : Inverse Laplace Transforms

Obtain the inverse transforms for the following:

1. $\frac{1}{4s^2 + 1}$
2. $\frac{1}{s(s + 4)}$
3. $\frac{2}{s(s^2 + 9)}$
4. $\frac{6}{1 - s^2}$
5. $\frac{1}{s^2(s^2 + 1)}$
6. $\frac{4}{s(s^2 - 6s + 8)}$

## Exercise 3 : Solving Linear ODEs via Laplace

Solve the following linear differential equations with constant coefficients:

1. $\ddot{y} + 5\dot{y} + 4y = 0$ (initial conditions: $y = 0$, $\dot{y} = 2$ at $t = 0$)
2. $\ddot{y} + 9y = \sin 2t$ (initial conditions: $y = 1$, $\dot{y} = -1$ at $t = 0$)
3. $\ddot{y} + 2\dot{y} = \cos t$ (initial conditions: $y = 1$ at $t = 0$)

## Exercise 4 : Transform and Solve (Verification)

If $\ddot{y} - 3\dot{y} + 2y = 4$ and $y = 2$, $\dot{y} = 3$ at $t = 0$, show that $\bar{y} = \frac{2s^2 - 3s + 4}{s(s - 1)(s - 2)}$, and hence find the solution for $y$.

## Exercise 5 : Nonhomogeneous Forcing (Exponentials and Polynomials)

Given $\ddot{y} + \dot{y} = e^t + t + 1$ with the initial conditions $y = 0$, $\dot{y} = 0$ at $t = 0$, obtain $y$.

## Exercise 6 : Coupled First-Order System (Forced)

Solve the following simultaneous equations for $y$:

  $\dot{y} + 2\dot{x} + y - x = 25e^t$
  $2\dot{y} + x = 25e^t$
Initial conditions: $y = 0$, $x = 25$ at $t = 0$.

## Exercise 7 : Coupled Homogeneous System

Solve for $y$ and $x$ given:

  $4\dot{x} - \dot{y} + x = 1$
  $4\dot{x} - 4\dot{y} - y = 0$
Initial conditions: $x = 0$, $y = 0$ at $t = 0$.

## Exercise 8 : Series LC Circuit (Forced Sinusoid)

An electrical circuit consists of a capacitor, $C$ farads, and an inductor, $L$ henries, in series, to which a voltage $E \sin \omega t$ is applied. If $Q$ is the charge on the capacitor in coulombs, show that
$$
Q = \frac{E}{L(\omega^2 - 1/LC)} \left[ \frac{\omega}{s^2 + 1/LC} - \frac{\omega}{s^2 + \omega^2} \right], \quad \omega^2 LC \neq 1
$$
and hence calculate $Q$ given that $C = 50 \times 10^{-6}F$, $L = 0.1H$, $\omega = 500  \frac{rad}{s}$, $E = 2V$, and $Q = \dot{Q} = 0$ at $t = 0$.

## Exercise 9 : Unit Step and Time-Shifting (Heaviside)

1. Find the Laplace transforms of $u(t-a)$ and $u(t-a)f(t-a)$ where $u$ is the unit step and $a>0$.
2. Compute the inverse transform of $\frac{e^{-2s}}{s(s+1)}$ and write the piecewise time-domain expression.
3. Solve $\ddot{y}+y = u(t-\pi)$ with zero initial conditions using Laplace transforms.

## Exercise 10 : Dirac Delta and Impulse Response

1. Compute $\mathcal{L}\{\delta(t-a)\}$ and $\mathcal{L}\{\delta'(t)\}$.
2. Solve $\ddot{y}+3\dot{y}+2y=\delta(t-1)$ with zero initial conditions; interpret the solution as an impulse response.
3. If a system has impulse response $h(t)=e^{-t}u(t)$, find its response to input $x(t)=\delta(t-2)$.

## Exercise 11 : Convolution Theorem and System Response

1. Use convolution to find the inverse Laplace transform of $\frac{1}{(s+1)(s^2+1)}$.
2. Given $H(s)=\frac{1}{s^2+2s+2}$ and input $x(t)=\sin t\,u(t)$, compute the output $y(t)=h*x$ using Laplace-domain multiplication and inverse transform.

## Exercise 12 : Initial and Final Value Theorems

1. Use the initial and final value theorems to evaluate $\lim_{t\to0^+}f(t)$ and $\lim_{t\to\infty}f(t)$ for $F(s)=\frac{s+2}{s^2+3s+2}$, if the limits exist.
2. Apply the theorems to determine the steady-state value of the solution of $\dot{y}+2y=5$ with $y(0)=0$ via Laplace transforms.

## Exercise 13 : Transfer Functions, Poles and Stability

1. For the ODE $\ddot{y}+4\dot{y}+5y = u(t)$, find the transfer function $H(s)=Y(s)/U(s)$ and list its poles. Is the system stable?
2. Find the natural response and comment on damping.

## Exercise 14 : Periodic Forcing and Steady-State Response

1. A square-wave of period $T$ with amplitude 1 can be expressed as a Fourier series. Briefly outline how Laplace transforms and the series combine to find the steady-state response of a linear system.
2. As a concrete task, find the Laplace transform of a periodic pulse train of period $2$ consisting of unit pulses of width $0.5$.

## Exercise 15 : Advanced Partial Fractions Practice

1. Compute inverse Laplace transforms for the following using partial fractions:
    - $\frac{3s^2+2s+1}{s(s^2+2s+2)}$
    - $\frac{s^3+2s^2+s+1}{s^2(s+1)(s^2+1)}$
2. Solve $\dddot{y}+\ddot{y}+\dot{y}+y=\sin t$ with zero initial conditions using transforms and partial fractions.
