---
title: "Développements en séries de Taylor"
date: 2025-09-07T07:08:24+02:00
# weight: 1
# aliases: ["/first"]
tags: ["Analyse", "Taylor", "Séries"]
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
# Développements en séries de Taylor

## Exercice 1 : Développements limités des fonctions paires et impaires

Soit $ n \in \mathbb{N} $ et soit $ f : \mathbb{R} \to \mathbb{R} $ une fonction de classe $ C^{n+1} $.

1. Montrer que si $ f $ est paire, alors le développement limité en 0 de $ f $ à l’ordre $ n $ n’a que des termes de degré pair (et tous les termes de degré impair sont nuls).
2. Montrer de même que si $ f $ est impaire, tous les termes de degré pair de son développement limité en 0 sont nuls.


## Exercice 2 : Calculs de développements limités

Calculer les développements limités en 0 des fonctions suivantes, aux ordres précisés :

1. $ x \mapsto \sin(x)\cos(x) $ à l’ordre 8.  
   *(On pourra faire le calcul en multipliant les développements limités, puis le vérifier en utilisant une formule de trigonométrie.)*
2. $ \cos \circ \sin $ à l’ordre 5.
3. $ \tanh $ à l’ordre 4.
4. $ \arcsin $ à l’ordre 4.
5. $ \text{arsinh} $ à l’ordre 4.


## Exercice 3 : Développements limités en d’autres points

1. Déterminer le développement limité à l’ordre 5 de la fonction $ \sin $ en $ \pi/2 $.
2. De même pour le développement limité de la fonction $ \log $ en 1 à l’ordre 5.


## Exercice 4 : Limites de fonctions

Déterminer l’ensemble de définition puis la limite en 0 des fonctions suivantes :

1.  
   $$
   \frac{\sin(t) - \sinh(t)}{t(\cos(t) - \cosh(t))}
   $$
2.  
   $$
   \frac{t(\sin(t) - \sinh(t))}{\cos(t) + \cosh(t) - 2}
   $$

## Exercice 5 : Limites de suites

Déterminer les limites des suites dont les termes généraux sont :

1.  
   $$
   u_n = n^2 (\cosh(1/n) - \cos(1/n))
   $$
2.  
   $$
   v_n = n \frac{\sinh(1/n) - \sin(1/n)}{\cosh(1/n) - \cos(1/n)}
   $$
