---
title: "Integrals"
date: 2025-09-07T06:44:19+02:00
# weight: 1
# aliases: ["/first"]
tags: ["Integrals", "Calculus"]
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

# Integrals

## Exercise 1 : Proofs

1. Prove $\int_{0}^{b} x^{3} dx = \frac{b^4}{4}$ using equal partitions and $\sum_{i=1}^{n} i^3$.
2. Prove $\int_{0}^{b} x^{4} dx = \frac{b^5}{5}$ analogously.
3. Show $\lim_{n \to \infty} \sum_{k=1}^{n} \frac{k^p}{n^{p+1}} = \frac{1}{p+1}$.  
4. Prove $\int_{0}^{b} x^p dx = \frac{b^{p+1}}{p+1}$.

## Exercise 2  

For $0 < a < b$, find $\int_{a}^{b} x^p dx$ using partitions with fixed ratios $r = t_i/t_{i-1}$: 

1. Show $t_i = a \cdot c^{i/n}$ where $c = b/a$.  
2. For $f(x) = x^p$, derive:  
   $$
   U(f,P) = (b^{p+1} - a^{p+1}) \frac{c^{p/n}}{1 + c^{1/n} + \cdots + c^{p/n}}
   $$  
   and find $L(f,P)$.  
3. Conclude $\int_{a}^{b} x^p dx = \frac{b^{p+1} - a^{p+1}}{p+1}$.

## Exercise 3  

Evaluate by symmetry:  

1. $\int_{-1}^{1} x^3 \sqrt{1-x^2} dx$  
2. $\int_{-1}^{1} (x^5 + 3)\sqrt{1-x^2} dx$

## Exercise 4  

Prove $\int_{0}^{x} \frac{\sin t}{t+1} dt > 0$ for all $x > 0$.

## Exercise 5  

Determine integrability on $[0,2]$ and compute when possible:  

1. $f(x) = \begin{cases} x & x \in [0,1) \\ x-2 & x \in [1,2] \end{cases}$  
2. $f(x) = \begin{cases} x & x \in [0,1] \\ x-2 & x \in (1,2] \end{cases}$  
3. $f(x) = x + \lfloor x \rfloor$  
4. $f(x) = \begin{cases} x + \lfloor x \rfloor & x \in \mathbb{Q} \\ 0 & x \notin \mathbb{Q} \end{cases}$  
5. $f(x) = \begin{cases} 1 & x = a + b\sqrt{2}, \, a,b \in \mathbb{Q} \\ 0 & \text{else} \end{cases}$  
6. $f(x) = \begin{cases} 1/\lfloor 1/x \rfloor & x \in (0,1] \\ 0 & x = 0 \text{ or } x > 1 \end{cases}$  
7. $f$ as in Figure 15.

## Exercise 6 : Area Calulations  

Find areas bounded by:  

1. $f(x) = x^2$ and $g(x) = x^2/2 + 2$  
2. $f(x) = x^2$, $g(x) = -x^2$, and $x = \pm 1$  
3. $f(x) = x^2$ and $g(x) = 1 - x^2$  
4. $f(x) = x^2$, $g(x) = 1 - x^2$, and $h(x) = 2$  
5. $f(x) = x^2$, $g(x) = x^2 - 2x + 4$, and $y$-axis  
6. $f(x) = \sqrt{x}$, $y = 0$, and $x = 2$

## Exercise 7 

Find $\int_{a}^{b} \left( \int_{c}^{d} f(x)g(y) dy \right) dx$ in terms of $\int f$ and $\int g$.

## Exercise 8  

Prove $m_i' + m_i'' \leq m_i$ using Theorem 5 notation.

## Exercise 9  

Characterize functions where:  

1. All lower = upper sums  
2. Some lower = some upper sum  
3. All lower sums equal (continuous case)  
4. All lower sums equal (integrable case)  

## Exercise 10 

If $f$ is integrable on $[a,d]$, show it's integrable on $[b,c]$ for $a < b < c < d$.

## Exercise 11 

1. Prove $\int_a^b f \geq 0$ if $f \geq 0$.  
2. Prove $\int_a^b f \geq \int_a^b g$ if $f \geq g$.

## Exercise 12  

Prove $\int_a^b f(x) dx = \int_{a+c}^{b+c} f(x-c) dx$ via partition correspondence.

## Exercise 13  

For $a,b > 1$, show $\int_1^a \frac{1}{t} dt + \int_1^b \frac{1}{t} dt = \int_1^{ab} \frac{1}{t} dt$.

## Exercise 14  

Prove $\int_{ca}^{cb} f(t) dt = c \int_a^b f(ct) dt$.

## Exercise 15  

Show the ellipse $\frac{x^2}{a^2} + \frac{y^2}{b^2} = 1$ has area $\pi a b$.

## Exercise 16 : Cavalieri's method  

Cavalieri's method for $\int x^n dx$:  

1. Show $\int_0^a x^n dx = c_n a^{n+1}$ where $c_n = \int_0^1 x^n dx$.  
2. Prove $2^{n+1} c_n = 2 \sum_{k \text{ even}} \binom{n}{k} c_k$.  
3. Conclude $c_n = 1/(n+1)$.

## Exercise 17  

If $f$ is bounded on $[a,b]$ and continuous except at $x_0 \in (a,b)$, show $f$ is integrable.

## Exercise 18  

For nondecreasing $f$:  

1. Find $L(f,P)$ and $U(f,P)$.  
2. Show $U(f,P) - L(f,P) = \delta (f(b) - f(a))$ for equal-width partitions.  
3. Prove $f$ is integrable.  
4. Give a nondecreasing function on $[0,1]$ with infinite discontinuities.

## Exercise 19  

For increasing $f$:  

1. Show $L(f^{-1},P) + U(f,P') = b f^{-1}(b) - a f^{-1}(a)$.  
2. Prove $\int_a^b f^{-1} = b f^{-1}(b) - a f^{-1}(a) - \int_{f^{-1}(a)}^{f^{-1}(b)} f$.  
3. Find $\int_a^b \sqrt{x} dx$ ($0 \leq a < b$).

## Exercise 20 : Young's inequality  

For continuous increasing $f$ with $f(0)=0$, prove Young's inequality:  
$$ ab \leq \int_0^a f + \int_0^b f^{-1} $$  
with equality iff $b = f(a)$.

## Exercise 21  

1. Show $\int_a^b f = (b-a)\mu$ for some $\mu \in [m,M]$.  
2. If $f$ is continuous, $\int_a^b f = (b-a)f(\xi)$ for some $\xi \in [a,b]$.  
3. Give a counterexample without continuity.  
4. Mean Value Theorem: For continuous $f$ and nonnegative integrable $g$,  
   $$ \int_a^b fg = f(\xi) \int_a^b g \text{ for some } \xi $$  
5. Extend to nonpositive $g$.  
6. Show $g$ must have constant sign.

## Exercise 22  

For polar curve $r = f(\theta)$, show the area between $\theta_0$ and $\theta_1$ is:  
$$ \frac{1}{2} \int_{\theta_0}^{\theta_1} f(\theta)^2 d\theta $$

## Exercise 23

Let $ f $ be continuous on $[a, b]$. For any partition $ P = \{t_0, \ldots, t_n\} $ of $[a, b]$, define the polygonal length:
$$
\ell(f, P) = \sum_{i=1}^n \sqrt{(t_i - t_{i-1})^2 + [f(t_i) - f(t_{i-1})]^2}
$$
The **length** of $f$ on $[a,b]$ is $\sup\{\ell(f,P)\}$ (if bounded).

1. Show that for linear $f$, $\ell(f)$ equals the distance between $(a,f(a))$ and $(b,f(b))$.
2. For nonlinear $f$, find a partition $P = \{a,t,b\}$ where $\ell(f,P)$ exceeds this distance. *(Use Problem 4-9.)*
3. Conclude that linear functions minimize length among all $f$ with fixed endpoints.
4. If $f'$ is bounded, prove for any partition $P$:
   $$
   L(\sqrt{1+(f')^2}, P) \leq \ell(f,P) \leq U(\sqrt{1+(f')^2}, P)
   $$
   *(Hint: Mean Value Theorem)*
5. Why is $\sup\{L(\sqrt{1+(f')^2}, P)\} \leq \sup\{\ell(f,P)\}$? *(Straightforward)*
6. Show $\sup\{\ell(f,P)\} \leq \inf\{U(\sqrt{1+(f')^2}, P)\}$, proving that when $\sqrt{1+(f')^2}$ is integrable:
   $$
   \ell(f) = \int_a^b \sqrt{1+(f')^2} \, dx
   $$
   *(Hint: Compare $P'$ and $P''$ via common refinement)*
7. Let $\mathcal{L}(x)$ be the graph length on $[a,x]$ and $d(x)$ the endpoint distance. If $\sqrt{1+(f')^2}$ is integrable and $f'$ continuous at $a$, prove:
   $$
   \lim_{x \to a^+} \frac{\mathcal{L}(x)}{d(x)} = 1
   $$
   *(Hint: Multiple MVT applications)*
8. For the function in Figure 21, show the conclusion from (7) fails.

## Exercise 24

A **step function** $s$ on $[a,b]$ is constant on each $(t_{i-1}, t_i)$ for some partition $P$.

1. Prove that for integrable $f$ and $\epsilon > 0$, there exist step functions $s_1 \leq f \leq s_2$ with:
   $$
   \int_a^b (s_2 - s_1) < \epsilon
   $$
2. Show $f$ is integrable if such $s_1, s_2$ exist for all $\epsilon > 0$.  
3. Find a non-step $f$ with $\int_a^b f = L(f, P)$ for some $P$.

## Exercise 25

For integrable $f$ on $[a,b]$ and $\epsilon > 0$, find continuous $g \leq f \leq h$ with:
$$
\int_a^b (h - g) < \epsilon
$$
*(Hint: Approximate $f$ via step functions first)*

## Exercise 26

1. Prove the sum of step functions is a step function.
2. Show directly that $\int_a^b (s_1 + s_2) = \int_a^b s_1 + \int_a^b s_2$.
3. Use (2) and Problem 26 to reprove Theorem 5 (linearity of integrals).

## Exercise 27

For integrable $f$ on $[a,b]$, find $x \in [a,b]$ where:
$$
\int_a^x f = \int_x^b f
$$
*(Show $x$ may not be in $(a,b)$.)*

## Exercise 28

Prove integrable functions have many continuity points:

1. Given $U(f,P) - L(f,P) < b - a$, show $M_i - m_i < 1$ for some $i$.
2. Construct nested intervals $[a_n,b_n]$ with $\sup f - \inf f < 1/n$ on $[a_n,b_n]$.
3. Apply the Nested Interval Theorem to find infinitely many continuity points.

## Exercise 29

1. Find $f \geq 0$ with $f(x) > 0$ somewhere but $\int_a^b f = 0$.
2. If $f \geq 0$ and continuous at $x_0$ with $f(x_0) > 0$, prove $\int_a^b f > 0$.
3. For integrable $f > 0$ on $[a,b]$, show $\int_a^b f > 0$. *(Use Problem 30.)*

## Exercise 30

1. Let $f$ be continuous on $[a,b]$. If $\int_a^b fg = 0$ for all continuous $g$, prove $f = 0$.
2. If $\int_a^b fg = 0$ for all continuous $g$ with $g(a) = g(b) = 0$, show $f = 0$.  
   *(Hint: Assume $f(x_0) \neq 0$ and construct bump $g$.)*

## Exercise 31

Let $f(x) = x$ (rational) and $f(x) = 0$ (irrational).

1. Compute $L(f,P)$ for all partitions $P$ of $[0,1]$.
2. Find $\inf\{U(f,P)\}$.

## Exercise 32

For $f(x) = 0$ (irrational) and $f(x) = 1/q$ ($x = p/q$ lowest terms). Prove $f$ is integrable on $[0,1]$ with $\int_0^1 f = 0$.

## Exercise 33

Find integrable $f, g$ such that $g \circ f$ is not integrable. *(Relate to Problem 34.)*

## Exercise 34

For bounded $f$ on $[a,b]$:

1. Show $M_i' - m_i' \leq M_i - m_i$ for $|f|$.
2. If $f$ is integrable, prove $|f|$ is integrable.
3. For integrable $f,g$, show $\max(f,g)$ and $\min(f,g)$ are integrable.
4. Prove $f$ is integrable iff $\max(f,0)$ and $\min(f,0)$ are integrable.

## Exercise 35

For integrable $f$ on $[a,b]$, prove:
$$
\left| \int_a^b f\ \right| \leq \int_a^b |f|
$$

## Exercise 36

For integrable $f,g \geq 0$ on $[a,b]$:

1. Show $M_i \leq M_i'M_i''$ and $m_i \geq m_i'm_i''$ for $fg$.
2. Prove:
   $$
   U(fg,P) - L(fg,P) \leq \sum [M_i'M_i'' - m_i'm_i''](t_i - t_{i-1})
   $$
3. If $|f|,|g| \leq M$, show $U(fg,P) - L(fg,P) \leq M[U(f,P) - L(f,P) + U(g,P) - L(g,P)]$.
4. Conclude $fg$ is integrable, extending to general $f,g$.

## Exercise 37

For integrable $f,g$ on $[a,b]$:

1. Prove the Cauchy-Schwarz inequality:
   $$
   \left( \int_a^b fg \right)^2 \leq \left( \int_a^b f^2 \right) \left( \int_a^b g^2 \right)
   $$
2. Provide three proofs (algebraic, geometric, creative).
3. If equality holds, must $f = \lambda g$? Does continuity matter?
4. Show $\left( \int_0^1 f \right)^2 \leq \int_0^1 f^2$. Extend to $[a,b]$.

## Exercise 38

If $f$ is integrable on $[0,x]$ for all $x > 0$ and $\lim_{x \to \infty} f(x) = a$, prove:
$$
\lim_{x \to \infty} \frac{1}{x} \int_0^x f(t) \, dt = a
$$
*(Hint: Split integral at $N$ where $f \approx a$ for $t \geq N$.)*