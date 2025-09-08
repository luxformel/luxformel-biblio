---
title: "L’intégrale au sens de Riemann"
date: 2025-09-07T07:10:03+02:00
# weight: 1
# aliases: ["/first"]
tags: ["Analyse", "Riemann", "Intérgales"]
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
# L’intégrale au sens de Riemann

## Exercice 1 : Fonctions d’intégrale nulle

1. Donner un exemple d’une fonction $ f : [a,b] \to \mathbb{R}_{\geq 0} $ intégrable, non identiquement nulle mais d’intégrale nulle.
2. Montrer que si $ f : [a,b] \to \mathbb{R}_{\geq 0} $ est continue et non identiquement nulle, alors son intégrale est strictement positive.

## Exercice 2 : Valeurs particulières et intégrales

Soit $ f : [0,1] \to \mathbb{R} $ une fonction continue.

1. Montrer que si $ \int_0^1 f(t)dt = 0 $, alors l’équation $ f(x) = 0 $ admet une solution sur $ ]0,1[ $.
2. Montrer que si $ \int_0^1 f(t)dt = \frac{1}{2} $, alors $ f $ a un point fixe sur $ ]0,1[ $.

## Exercice 3 : Une fonction intégrable non continue

Soit $ f : [0,1] \to \mathbb{R} $ la fonction définie par $ f(t) = \sin(1/t) $ si $ t > 0 $ et par $ f(0) = 0 $.

1. La fonction $ f $ est-elle continue ?
2. Montrer que pour tout $ a \in ]0,1] $, $ f $ est intégrable sur $ [a,1] $.
3. En déduire que $ f $ est intégrable sur $ [0,1] $.

## Exercice 4 : Produits de fonctions

Soit $ f : [a,b] \to \mathbb{R}_{\geq 0} $ intégrable, et soit $ g : [a,b] \to \mathbb{R} $ continue.

1. Montrer qu’il existe $ m, M \in \mathbb{R} $ tels que  
   $$
   m \int_a^b f(t)dt \leq \int_a^b f(t)g(t)dt \leq M \int_a^b f(t)dt.
   $$
2. Montrer qu’il existe $ c \in [a,b] $ tel que  
   $$
   \int_a^b f(t)g(t)dt = g(c) \int_a^b f(t)dt.
   $$

## Exercice 5 : Intégrale de $ t^2 $ comme somme de Riemann

1. Montrer par récurrence sur $ n $ que pour tout $ n > 0 $ entier,  
   $$
   1^2 + 2^2 + \dots + n^2 = \frac{n(n+1)(2n+1)}{6}.
   $$
2. Calculer  
   $$
   \int_0^1 t^2dt
   $$
   en la considérant comme une limite de sommes de Riemann.

## Exercice 6 : Sommes de Riemann

Calculer les limites des suites dont le terme général est donné ci-dessous, en les considérant comme des sommes de Riemann.

1. $ v_n = \frac{1}{n+1} + \frac{1}{n+2} + \dots + \frac{1}{2n} $.
2. $ w_n = \frac{\sqrt{1} + \sqrt{2} + \dots + \sqrt{n}}{n \sqrt{n}} $.
3. $ u_n = \frac{n}{n^2+1} + \frac{n}{n^2+4} + \cdots + \frac{n}{n^2+n^2} $.
4. $ x_n = \frac{1}{n} \sum_{k=1}^{n} \sin(k\pi/n) $.

## Exercice 7 : Limites et sommes de Riemann

Calculer les limites des suites de terme général :

1. $ a_n = \sum_{k=1}^n \frac{n}{n^2 + k^2} $
2. $ b_n = \sum_{k=1}^n \frac{k}{n^2 + k^2} $
3. $ c_n = \sum_{k=1}^n \frac{1}{ \sqrt{n^2 + 2kn}} $
4. $ d_n = \left( \frac{ \left( 2n \right) ! }{ n^n n ! } \right)^{\frac{1}{n}} $
5. $ e_n = \left( \prod_{k=1}^n \left( 1 + \frac{k}{n} \right) \right)^{\frac{1}{n}} $ 