---
title: "Séries numériques"
date: 2025-09-07T07:20:47+02:00
# weight: 1
# aliases: ["/first"]
tags: ["Analyse", "Séries"]
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

# Séries numériques

## Exercice 1 : Calculs de séries

Calculer les sommes des séries suivantes :

1. $$
   \sum_{k=0}^{+\infty} \left(\frac{2}{3}\right)^k
   $$
2. $$
   \sum_{k=0}^{+\infty} 3^{-2k+1}
   $$
3. $$
   \sum_{k=0}^{+\infty} \sin(2ka)e^{-ka}
   $$
4. $$
   \sum_{k=0}^{+\infty} \frac{k}{2^k} \quad \text{(plus difficile).}
   $$

## Exercice 2 : Convergence de séries

Étudier la convergence de la série $\sum_{n=1}^{+\infty} u_n$, pour :

1. $$
   u_n = \frac{n}{n^2 + 1}
   $$
2. $$
   u_n = \frac{\cosh n}{\cosh(2n)}
   $$
3. $$
   u_1 = 0 \quad \text{et} \quad u_n = \frac{1}{\sqrt{n^2-1}} - \frac{1}{\sqrt{n^2+1}} \quad \text{pour } n > 1
   $$
4. $$
   u_n = \frac{n!}{n^n}
   $$
5. $$
   u_n = e - \left(1 + \frac{1}{n}\right)^n
   $$



6. $$ u_n = \left( \frac{n}{n+1} \right)^{n^2} $$

7. $$ u_n = \int_0^1 \sin \left( \frac{t}{n} \right) dt $$

8. $$ u_n = \frac{1}{\cos^2 n} $$


## Exercice 3 : Convergence absolue

Pour chacune des séries suivantes, dites si elle converge absolument et si les sommes partielles convergent.

1. $$ \sum_{k \geq 0} \frac{k \cdot 2^k}{3^{2k+1}} $$

2. $$ \sum_{k \geq 1} \frac{k^5 \cdot 7^{6k}}{2^{k^2}} $$

3. $$ \sum_{k \geq 0} \frac{1}{k^2 + 2k + 2} $$

4. $$ \sum_{k \geq 1} \frac{k^2 + 1}{3k^3 - 2k} $$

5. $$ \sum_{k \geq 1} \frac{(-1)^k}{\sqrt{k}} $$

6. $$ \sum_{k \geq 1} \frac{(-1)^k \cdot \sqrt{k}+1}{2k} $$


## Exercice 4 : Un critère de convergence

On souhaite étudier la convergence de la série $ S(\alpha) := \sum_{n=1}^{+\infty} u_n $ lorsque $ (u_n)_{n \in \mathbb{N}} $ est une suite numérique positive vérifiant
$$ \frac{u_{n+1}}{u_n} = 1 - \frac{\alpha}{n} + \mathcal{O} \left( \frac{1}{n^2} \right), \quad \alpha \in \mathbb{R}. $$

1. Pour $ (v_n)_{n \in \mathbb{N}} \subset \mathbb{R} $, montrer que
$$ \sum_{n=1}^{+\infty} v_{n+1} - v_n \text{ converge } \iff (v_n)_{n \in \mathbb{N}} \text{ converge}. $$

2. Pour $ (v_n)_{n \in \mathbb{N}} $ définie par $ v_n = n^{\alpha} u_n $, montrer que $ (v_n)_{n \in \mathbb{N}} $ est convergente.

3. Conclure sur la convergence de $ S(\alpha) $.

