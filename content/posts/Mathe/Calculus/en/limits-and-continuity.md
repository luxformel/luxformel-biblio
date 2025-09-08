---
title: "Limits and Continuity"
date: 2025-09-07T06:44:19+02:00
# weight: 1
# aliases: ["/first"]
tags: ["Limits", "Continuity", "Calculus"]
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

# Limits and Continuity

## Exercise 1 

Find the following limits:

1. $\lim_{x \to 1} \frac{x^2 - 1}{x^3 - 1}$  
2. $\lim_{x \to 2} \frac{x^3 - 8}{x^2 - 4}$  
3. $\lim_{x \to 3} \frac{x^3 - 8}{x^2 - 4}$ *(Note the changed limit point)*  
4. $\lim_{x \to y} \frac{x^n - y^n}{x - y}$  
5. $\lim_{y \to x} \frac{x^n - y^n}{x - y}$  
6. $\lim_{h \to 0} \frac{\sqrt{a + h} - \sqrt{a}}{h}$  

## Exercise 2 

Find the following limits:

1. $\lim_{x \to 1} \frac{1 - \sqrt{x}}{1 - x}$  
2. $\lim_{x \to 0} \frac{1 - \sqrt{1 - x^2}}{x}$  
3. $\lim_{x \to 0} \frac{1 - \sqrt{1 - x^2}}{x^2}$  

## Exercise 3 

In each of the following cases, determine the limit $l$ for the given $a$, and prove that it is the limit by showing how to find a $\delta$ such  that $| f(x) - l | < \varepsilon$ where $\forall x$ satisfying $0 < |x-a| < \delta$

1. $f(x) = x[3 - \cos(x^2)], \ a = 0$  
2. $f(x) = x^2 + 5x - 2, \ a = 2$  
3. $f(x) = \frac{100}{x}, \ a = 1$  
4. $f(x) = x^4, \ \text{arbitrary } a$  
5. $f(x) = x^4 + \frac{1}{x}, \ a = 1$  
6. $f(x) = \frac{x}{2 - \sin^2 x}, \ a = 0$  
7. $f(x) = \sqrt{|x|}, \ a = 0$  
8. $f(x) = \sqrt{x}, \ a = 1$  

## Exercise 4 

Given functions $f$ and $g$ with properties:  
\[
\text{If } 0 < |x - 2| < \sin^2 \left( \frac{\epsilon^2}{9} \right) + \epsilon, \text{ then } |f(x) - 2| < \epsilon
\]
\[
\text{If } 0 < |x - 2| < \epsilon^2, \text{ then } |g(x) - 4| < \epsilon
\]

For each $\epsilon > 0$, find $\delta > 0$ such that:

1. If $0 < |x - 2| < \delta$, then $|f(x) + g(x) - 6| < \epsilon$  
2. If $0 < |x - 2| < \delta$, then $|f(x)g(x) - 8| < \epsilon$  
3. If $0 < |x - 2| < \delta$, then $\left| \frac{1}{g(x)} - \frac{1}{4} \right| < \epsilon$  
4. If $0 < |x - 2| < \delta$, then $\left| \frac{f(x)}{g(x)} - \frac{1}{2} \right| < \epsilon$  

## Exercise 5  

1. If $\lim\limits_{x\to a}f(x)$ and $\lim\limits_{x\to a}g(x)$ do not exist, can $\lim\limits_{x\to a}[f(x)+g(x)]$ exist? Can $\lim\limits_{x\to a}f(x)g(x)$ exist?  
2. If $\lim\limits_{x\to a}f(x)$ exists and $\lim\limits_{x\to a}[f(x)+g(x)]$ exists, must $\lim\limits_{x\to a}g(x)$ exist?  
3. If $\lim\limits_{x\to a}f(x)$ exists and $\lim\limits_{x\to a}g(x)$ does not exist, can $\lim\limits_{x\to a}[f(x)+g(x)]$ exist?  
4. If $\lim\limits_{x\to a}f(x)$ exists and $\lim\limits_{x\to a}f(x)g(x)$ exists, does it follow that $\lim\limits_{x\to a}g(x)$ exists?  

## Exercise 6  

Prove that $\lim\limits_{x\to a}f(x) = \lim\limits_{h\to 0}f(a+h)$.  

## Exercise 7  

1. Prove that $\lim\limits_{x\to a}f(x) = l$ if and only if $\lim\limits_{x\to a}[f(x)-l] = 0$.  
2. Prove that $\lim\limits_{x\to 0}f(x) = \lim\limits_{x\to a}f(x-a)$.  
3. Prove that $\lim\limits_{x\to 0}f(x) = \lim\limits_{x\to 0}f(x^3)$.  
4. Give an example where $\lim\limits_{x\to 0}f(x^2)$ exists, but $\lim\limits_{x\to 0}f(x)$ does not.  

## Exercise 8  
Suppose there is a $\delta > 0$ such that $f(x) = g(x)$ when $0 < |x-a| < \delta$. Prove that $\lim\limits_{x\to a}f(x) = \lim\limits_{x\to a}g(x)$.  

## Exercise 9  

1. Suppose that $f(x) \leq g(x)$ for all $x$. Prove that $\lim\limits_{x\to a}f(x) \leq \lim\limits_{x\to a}g(x)$, provided these limits exist.  
2. How can the hypotheses be weakened?  
3. If $f(x) < g(x)$ for all $x$, does it necessarily follow that $\lim\limits_{x\to a}f(x) < \lim\limits_{x\to a}g(x)$?  

## Exercise 10  
Suppose that $f(x) \leq g(x) \leq h(x)$ and that $\lim\limits_{x\to a}f(x) = \lim\limits_{x\to a}h(x)$. Prove that $\lim\limits_{x\to a}g(x)$ exists and equals $\lim\limits_{x\to a}f(x) = \lim\limits_{x\to a}h(x)$.  

## Exercise 11  
1. Prove that if $\lim\limits_{x\to 0}\frac{f(x)}{x} = l$ and $b \neq 0$, then $\lim\limits_{x\to 0}\frac{f(bx)}{x} = bl$.  
2. What happens if $b = 0$?  
3. Find $\lim\limits_{x\to 0}\frac{\sin 2x}{x}$ using $\lim\limits_{x\to 0}\frac{\sin x}{x}$ and another method.  

## Exercise 12  
Evaluate in terms of $\alpha = \lim\limits_{x\to 0}\frac{\sin x}{x}$: 

1. $\lim\limits_{x\to 0}\frac{\sin 3x}{x}$  
2. $\lim\limits_{x\to 0}\frac{\sin ax}{\sin bx}$  
3. $\lim\limits_{x \to 0} \frac{\sin^2 2x}{x}$  
4. $\lim\limits_{x \to 0} \frac{\sin^2 2x}{x^2}$  
5. $\lim\limits_{x \to 0} \frac{1 - \cos x}{x^2}$  
6. $\lim\limits_{x \to 0} \frac{\tan^2 x + 2x}{x + x^2}$  
7. $\lim\limits_{x \to 0} \frac{x \sin x}{1 - \cos x}$  
8. $\lim\limits_{h \to 0} \frac{\sin(x + h) - \sin x}{h}$  
9. $\lim\limits_{x \to 1} \frac{\sin(x^2 - 1)}{x - 1}$  
10. $\lim\limits_{x \to 0} \frac{x^2 (3 + \sin x)}{(x + \sin x)^2}$  
11. $\lim\limits_{x \to 1} (x^2 - 1)^3 \sin \left( \frac{1}{x - 1} \right)^3$  

## Exercise 13  
1. Prove that if $\lim\limits_{x \to a} f(x) = l$, then $\lim\limits_{x \to a} |f|(x) = |l|$  
2. Prove that if $\lim\limits_{x \to a} f(x) = l$ and $\lim\limits_{x \to a} g(x) = m$, then:  
   a. $\lim\limits_{x \to a} \max(f, g)(x) = \max(l, m)$  
   b. Similarly for min  

## Exercise 14  
1. Prove that $\lim\limits_{x \to 0} 1/x$ does not exist (show $\lim\limits_{x \to 0} 1/x = l$ is false for every $l$)  
2. Prove that $\lim\limits_{x \to 1} 1/(x - 1)$ does not exist  

## Exercise 15  
Prove that if $\lim\limits_{x \to a} f(x) = l$, then $\exists \delta > 0$ and $M$ such that $|f(x)| < M$ when $0 < |x - a| < \delta$  

## Exercise 16  
Prove that if:  

1. $f(x) = 0$ for irrational $x$  
2. $f(x) = 1$ for rational $x$  
Then $\lim\limits_{x \to a} f(x)$ does not exist for any $a$  

## Exercise 17  
Prove that if:  

1. $f(x) = x$ for rational $x$  
2. $f(x) = -x$ for irrational $x$  
Then $\lim\limits_{x \to a} f(x)$ does not exist if $a \neq 0$  

## Exercise 18  
1. Prove that if $\lim\limits_{x \to 0} g(x) = 0$, then $\lim\limits_{x \to 0} g(x) \sin(1/x) = 0$  
2. Generalization: If $\lim\limits_{x \to 0} g(x) = 0$ and $|h(x)| \leq M$ for all $x$, then $\lim\limits_{x \to 0} g(x)h(x) = 0$  

## Exercise 19  
Consider a function $f$ with the property: if $g$ is any function where $\lim\limits_{x \to 0} g(x)$ DNE, then $\lim\limits_{x \to 0} [f(x) + g(x)]$ also DNE. Prove this occurs if and only if $\lim\limits_{x \to 0} f(x)$ exists.  

## Exercise 20  
1. If $\lim\limits_{x \to 0} f(x)$ exists and is $\neq 0$, and $\lim\limits_{x \to 0} g(x)$ DNE, prove $\lim\limits_{x \to 0} f(x)g(x)$ DNE  
2. Prove the same when $\lim\limits_{x \to 0} |f(x)| = \infty$  
3. If neither condition holds, show there exists $g$ where $\lim\limits_{x \to 0} g(x)$ DNE but $\lim\limits_{x \to 0} f(x)g(x)$ exists  

## Exercise 21  
1. For finite sets $A_n \subset [0,1]$ with $A_n \cap A_m = \emptyset$ ($m \neq n$), define:  
   \[ f(x) = \begin{cases} 
   1/n, & x \in A_n \\
   0, & x \notin \bigcup A_n
   \end{cases} \]  
   Prove $\lim\limits_{x \to a} f(x) = 0$ for all $a \in [0,1]$  

## Exercise 22  
Explain why these are all correct definitions of $\lim\limits_{x \to a} f(x) = l$:  

For $\delta > 0$, $\exists \varepsilon > 0$ such that:  
1. $0 < |x - a| < \varepsilon \implies |f(x) - l| < \delta$  
2. $0 < |x - a| < \varepsilon \implies |f(x) - l| \leq \delta$  
3. $0 < |x - a| < \varepsilon \implies |f(x) - l| < 5\delta$  
4. $0 < |x - a| < \varepsilon/10 \implies |f(x) - l| < \delta$  

## Exercise 23  
Give counterexamples showing these definitions are incorrect:  

1. For all $\delta > 0$, $\exists \varepsilon > 0$ such that $0 < |x - a| < \delta \implies |f(x) - l| < \varepsilon$  
2. For all $\varepsilon > 0$, $\exists \delta > 0$ such that $|f(x) - l| < \varepsilon \implies 0 < |x - a| < \delta$  

## Exercise 24  
Prove that $\lim\limits_{x \to a} f(x)$ exists if $\lim\limits_{x \to a^+} f(x) = \lim\limits_{x \to a^-} f(x)$  

## Exercise 25  
Prove the following limit relations: 

1. $\lim\limits_{x \to 0^+} f(x) = \lim\limits_{x \to 0^-} f(-x)$  
2. $\lim\limits_{x \to 0} f(|x|) = \lim\limits_{x \to 0^+} f(x)$  
3. $\lim\limits_{x \to 0} f(x^2) = \lim\limits_{x \to 0^+} f(x)$  

## Exercise 26  
1. If $\lim\limits_{x \to a^-} f(x) < \lim\limits_{x \to a^+} f(x)$, prove $\exists \delta > 0$ such that $f(x) < f(y)$ whenever $x < a < y$ and $|x - a| < \delta$, $|y - a| < \delta$  
2. Determine whether the converse holds  

## Exercise 27  
1. Prove $\lim\limits_{x \to \infty} \frac{a_n x^n + \cdots + a_0}{b_m x^m + \cdots + b_0}$ exists iff $m \geq n$ ($a_n, b_m \neq 0$)  
2. Determine the limit when:  
   a. $m = n$  
   b. $m > n$  

## Exercise 28  
Find the following limits:  

1. $\lim\limits_{x \to \infty} \frac{x + \sin^3 x}{5x + 6}$  
2. $\lim\limits_{x \to \infty} \frac{x \sin x}{x^2 + 5}$  
3. $\lim\limits_{x \to \infty} \sqrt{x^2 + x} - x$  
4. $\lim\limits_{x \to \infty} \frac{x^2 (1 + \sin^2 x)}{(x + \sin x)^2}$  

## Exercise 29  
Prove $\lim\limits_{x \to 0^+} f(1/x) = \lim\limits_{x \to \infty} f(x)$  

## Exercise 30  
Find in terms of $\alpha = \lim\limits_{x \to 0} \frac{\sin x}{x}$: 

1. $\lim\limits_{x \to \infty} \frac{\sin x}{x}$  
2. $\lim\limits_{x \to \infty} x \sin \frac{1}{x}$  

## Exercise 31  
1. Define $\lim\limits_{x \to -\infty} f(x) = l$  
2. Find $\lim\limits_{x \to -\infty} \frac{a_n x^n + \cdots + a_0}{b_m x^m + \cdots + b_0}$  
3. Prove $\lim\limits_{x \to -\infty} f(x) = \lim\limits_{x \to \infty} f(-x)$  
4. Prove $\lim\limits_{x \to 0^-} f(1/x) = \lim\limits_{x \to -\infty} f(x)$  

## Exercise 32  
1. Define $\lim\limits_{x \to a} f(x) = \infty$ (with formal $\epsilon-\delta$ definition)  
2. Show $\lim\limits_{x \to 3} \frac{1}{(x-3)^2} = \infty$  
3. If $f(x) > \epsilon > 0$ for all $x$ and $\lim\limits_{x \to a} g(x) = 0$, prove $\lim\limits_{x \to a} \frac{f(x)}{|g(x)|} = \infty$  

## Exercise 33  
1. Define:  
   a. $\lim\limits_{x \to a^+} f(x) = \infty$  
   b. $\lim\limits_{x \to a^-} f(x) = \infty$  
2. Prove $\lim\limits_{x \to 0^+} \frac{1}{x} = \infty$  
3. Prove $\lim\limits_{x \to 0^+} f(x) = \infty \iff \lim\limits_{x \to \infty} f(1/x) = \infty$  

## Exercise 34  
Find these limits when they exist: 

1. $\lim\limits_{x \to \infty} \frac{x^3 + 4x - 7}{7x^2 - x + 1}$  
2. $\lim\limits_{x \to \infty} x(1 + \sin^2 x)$  
3. $\lim\limits_{x \to \infty} x \sin^2 x$  
4. $\lim\limits_{x \to \infty} x^2 \sin \frac{1}{x}$  
5. $\lim\limits_{x \to \infty} \sqrt{x^2 + 2x} - x$  
6. $\lim\limits_{x \to \infty} x(\sqrt{x + 2} - \sqrt{x})$  
7. $\lim\limits_{x \to \infty} \frac{\sqrt{|x|}}{x}$  

## Exercise 35  
1. Find perimeter of regular $n$-gon inscribed in circle radius $r$  
2. Determine perimeter's limiting value as $n \to \infty$  
3. Identify the fundamental limit this suggests  

## Exercise 36  
1. For $c > 1$, prove $\lim\limits_{n \to \infty} c^{1/n} = 1$  
   *Hint:* Show $c^{1/n} \leq 1 + \epsilon$ for large $n$ and any $\epsilon > 0$  
2. Generalize to $c > 0$, prove $\lim\limits_{n \to \infty} c^{1/n} = 1$