---
title: "Derivatives"
date: 2025-09-07T07:04:16+02:00
# weight: 1
# aliases: ["/first"]
tags: ["Calculus", "Derivatives"]
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

# Derivatives 

## Exercise 1
1. Using the definition, prove that if $f(x)=1/x$, then $f'(a)=-1/a^{2}$ for $a\neq 0$.  
2. Show that the tangent line to $f$ at $(a, 1/a)$ intersects $f$ only at $(a, 1/a)$.

## Exercise 2
1. Using the definition, prove that if $f(x)=1/x^{2}$, then $f'(a)=-2/a^{3}$ for $a\neq 0$.  
2. Show that the tangent line at $(a, 1/a^{2})$ intersects $f$ at exactly one other point, on the opposite side of the y-axis.

## Exercise 3
Prove that if $f(x)=\sqrt{x}$, then $f'(a)=1/(2\sqrt{a})$ for $a>0$. (Hint: Rationalize the difference quotient.)

## Exercise 4
Let $S_n(x)=x^n$. Given $S_1'(x)=1$, $S_2'(x)=2x$, and $S_3'(x)=3x^2$, conjecture and prove a general formula for $S_n'(x)$. (Use the binomial theorem.)

## Exercise 5
Find $f'$ for $f(x)=\lfloor x \rfloor$ (floor function).

## Exercise 6
Prove from the definition:

1. If $g(x)=f(x)+c$, then $g'(x)=f'(x)$  
2. If $g(x)=cf(x)$, then $g'(x)=cf'(x)$

## Exercise 7
Let $f(x)=x^3$:

1. Compute $f'(9)$, $f'(25)$, $f'(36)$  
2. Compute $f'(3^2)$, $f'(5^2)$, $f'(6^2)$  
3. Find $f'(a^2)$ and $f'(x^2)$  
4. Compare $f'(x^2)$ with $g'(x)$ where $g(x)=f(x^2)$

## Exercise 8
1. If $g(x)=f(x+c)$, prove $g'(x)=f'(x+c)$ from the definition.  
2. If $g(x)=f(cx)$, prove $g'(x)=c\cdot f'(cx)$.  
3. If $f$ is differentiable and periodic with period $a$, prove $f'$ is also periodic.

## Exercise 9
Find $f'(x)$ and $f'(x+3)$ for:

1. $f(x)=(x+3)^5$  
2. $f(x+3)=x^5$  
3. $f(x+3)=(x+5)^7$

## Exercise 10
Find $f'(x)$ if:

1. $f(x)=g(t+x)$  
2. $f(t)=g(t+x)$

## Exercise 11
Let $L(x)$ be speed limit at position $x$, with cars $A(t)$ and $B(t)$:

1. What equation shows $A$ always obeys the speed limit?  
2. If $B(t)=A(t-1)$, show $B$ obeys the limit.  
3. If $B$ stays a fixed distance behind $A$, when does $B$ obey the limit?

## Exercise 12
Let $f(a)=g(a)$ with $f_-'(a)=g_+'(a)$. Define $h(x)$ as $f(x)$ for $x\leq a$ and $g(x)$ for $x\geq a$. Prove $h$ is differentiable at $a$.

## Exercise 13
Let $f(x)=x^2$ for rational $x$, 0 otherwise. Prove $f$ is differentiable at 0.

## Exercise 14
1. If $|f(x)|\leq x^2$ for all $x$, prove $f$ is differentiable at 0.  
2. Generalize using $|g(x)|$ instead of $x^2$. What property must $g$ have?

## Exercise 15
For $\alpha>1$, if $|f(x)|\leq|x|^\alpha$, prove $f$ is differentiable at 0.

## Exercise 16
For $0<\beta<1$, if $|f(x)|\geq|x|^\beta$ and $f(0)=0$, prove $f$ is not differentiable at 0.

## Exercise 17
Let $f(x)=0$ (irrational) or $1/q$ for $x=p/q$ (lowest terms). Prove $f$ is nowhere differentiable.

## Exercise 18
1. If $f(a)=g(a)=h(a)$, $f(x)\leq g(x)\leq h(x)$ for all $x$, and $f'(a)=h'(a)$, prove $g$ is differentiable at $a$ with $g'(a)=f'(a)$.  
2. Show the conclusion fails without $f(a)=g(a)=h(a)$.

## Exercise 19
For polynomial $f$ with tangent line $g$ at $(a,f(a))$, let $d(x)=f(x)-g(x)$:  
1. Find $d(x)$ when $f(x)=x^4$ and show $(x-a)^2$ divides it.  
2. Prove $(x-a)^2$ always divides $d(x)$ for any polynomial $f$.

## Exercise 20
1. Show $f'(a)=\lim_{x\to a}[f(x)-f(a)]/(x-a)$.  
2. Prove derivatives are local: if $f=g$ near $a$, then $f'(a)=g'(a)$.

## Exercise 21
1. If $f$ is differentiable at $x$, prove $f'(x)=\lim_{h\to 0}\frac{f(x+h)-f(x-h)}{2h}$.  
2. More generally, prove $f'(x)=\lim_{h,k\to 0^+}\frac{f(x+h)-f(x-k)}{h+k}$.

## Exercise 22
Prove that if $f$ is even, then $f'(x)=-f'(-x)$. Illustrate.

## Exercise 23
Prove that if $f$ is odd, then $f'(x)=f'(-x)$. Illustrate.

## Exercise 24
Find $f''(x)$ for:

1. $f(x)=x^3$  
2. $f(x)=x^5$  
3. $f'(x)=x^4$  
4. $f(x+3)=x^5$

## Exercise 25
For $S_n(x)=x^n$ and $0\leq k\leq n$, prove:
\[S_n^{(k)}(x)=\frac{n!}{(n-k)!}x^{n-k}=k!\binom{n}{k}x^{n-k}\]

## Exercise 26
1. For $f(x)=|x|^3$:  
2. Find $f'$ and $f''$  
3. Does $f'''$ exist everywhere?  
4. Analyze similarly for $f(x)=x^4$ ($x\geq 0$) and $f(x)=-x^4$ ($x\leq 0$)

## Exercise 27
Let $f(x)=x^n$ ($x\geq 0$) and $f(x)=0$ ($x\leq 0$). Prove $f^{(n-1)}$ exists but $f^{(n)}(0)$ does not.

## Exercise 28
Interpret these Leibniz notation statements (all from previous problems):

1. $ \frac{dx^n}{dx} = nx^{n-1} $  
2. $ \frac{dz}{dy} = -\frac{1}{y^2} \quad \text{if } z = \frac{1}{y} $  
3. $ \frac{d[f(x) + c]}{dx} = \frac{df(x)}{dx} $  
4. $ \frac{d[ cf(x) ]}{dx} = c \frac{df(x)}{dx} $  
5. $ \frac{dz}{dx} = \frac{dy}{dx} \quad \text{if } z = y + c $  
6. $ \left. \frac{dx^3}{dx} \right|_{x=a^2} = 3a^4 $  
7. $ \left. \frac{df(x+a)}{dx} \right|_{x=b} = \left. \frac{df(x)}{dx} \right|_{x=b+a} $  
8. $ \left. \frac{df(cx)}{dx} \right|_{x=b} = c \cdot \left. \frac{df(x)}{dx} \right|_{x=cb} $  
9. $ \left. \frac{df(cx)}{dx} \right|_{x=ax} = c \cdot \left. \frac{df(y)}{dy} \right|_{y=cx} $  
10. $ \left. \frac{d^k x^n}{dx^k} \right|_k^n = k! \binom{n}{k} x^{n-k} $