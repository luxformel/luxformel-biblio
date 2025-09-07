---
title: "Riemann Sums"
date: 2025-09-07T06:56:51+02:00
# weight: 1
# aliases: ["/first"]
tags: ["Riemann Sums", "Calculus"]
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

# Riemann Sums

## Exercise 1 : Approximation of Integral Products
Let \(f,g\) be continuous on \([a,b]\). For any partition \(P = \{t_0,\ldots,t_n\}\) of \([a,b]\), choose points \(x_i, u_i \in [t_{i-1},t_i]\). 

Show that sums of the form  
\[\sum_{i=1}^n f(x_i)g(u_i)(t_i-t_{i-1})\]  
can be made arbitrarily close to \(\int_a^b fg\) by choosing sufficiently fine partitions \(P\).


## Exercise 2 : Approximation of Composite Functions
Let \(f,g\) be continuous and nonnegative on \([a,b]\). Show that for sufficiently fine partitions \(P\), sums  
\[\sum_{i=1}^n \sqrt{f(x_i)+g(u_i)}(t_i-t_{i-1})\]  
approximate \(\int_a^b \sqrt{f+g}\) within any \(\varepsilon > 0\).

## Exercise 3 : Parametric Curve Length
For a parametric curve \(c(t) = (u(t),v(t))\) on \([a,b]\), define the length of an inscribed polygonal approximation for partition \(P\) as:  
\[\ell(c,P) = \sum_{i=1}^n \sqrt{[u(t_i)-u(t_{i-1})]^2 + [v(t_i)-v(t_{i-1})]^2} \]

Show that if \(u,v\) are continuously differentiable, then:  
\[\sup_P \ell(c,P) = \int_a^b \sqrt{u'(t)^2 + v'(t)^2}\, dt\]


## Exercise 4 : Riemann Sum Convergence
Let \(f\) be continuous on \([0,1]\). Show that:  
\[\lim_{n\to\infty} \frac{1}{n} \sum_{k=1}^n f\left(\frac{k}{n}\right) = \int_0^1 f(x)\,dx\]


## Exercise 5 : Midpoint Rule Insight
For \(f\) continuous on \([a,b]\), prove that the midpoint Riemann sums:  
\[\sum_{i=1}^n f\left(\frac{t_{i-1}+t_i}{2}\right)(t_i-t_{i-1})\]  
converge to \(\int_a^b f\) as \(\|P\|\to 0\).


## Exercise 6 : Non-Rectangular Approximations
Let \(f,g\geq 0\) be continuous on \([a,b]\). Consider "product area" sums:  
\[\sum_{i=1}^n f(x_i)g(y_i)(t_i-t_{i-1})\]  
where \(x_i,y_i\in[t_{i-1},t_i]\) may differ. Show these still converge to \(\int_a^b fg\).

