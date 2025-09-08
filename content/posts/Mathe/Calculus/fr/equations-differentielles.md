---
title: "Équations Différentielles"
date: 2025-09-07T07:12:52+02:00
# weight: 1
# aliases: ["/first"]
tags: ["Analyse", "Équations Différentielles"]
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

# Équations Différentielles

## Exercice 1 : Applications Directes

Résoudre les équations différentielles suivantes :

1. $ xy' + 2y = 4x^2 $, avec la condition initiale $ y(1) = 2 $.
2. $ y' \sin(x) - y = 1 - \cos x $.
3. $ (1 - x^2)y' + xy = 1 $.
4. $ xy' + y = y^2 \log(x) $.
5. $ y' + 2xy + xy^4 = 0 $.
6. $ y - xy' + \log x = 0 $.
7. $ x^3y' + (2 - 3x^2)y = x^3 $.
8. $ y' + y = y^2 (\cos x - \sin x) $.

## Exercice 2 : Équations du premier ordre à variable séparée
On considère les équations de la forme :

$$ y' = u(x) f(y) $$

où $ u : I \to \mathbb{R} $ et $ f : J \to \mathbb{R} $ sont des fonctions, avec $ J $ un intervalle ouvert de $ \mathbb{R} $.

1. Que peut-on dire pour le cas particulier où $ f $ est la fonction constante égale à 1 ?
2. De même si $ f(y) = y $ pour tout $ y $ ?
3. On suppose qu'il existe $ y_0 \in J $ tel que $ f(y_0) = 0 $. Montrer que la fonction constante $ y(x) = y_0 $ est solution.
4. On suppose maintenant que $ f $ ne s'annule pas sur $ J $, on note $ U $ une primitive de $ u $ et $ G $ une primitive de $ 1/f $. Soit $ I' \subset I $ un intervalle ouvert et $ y : I' \to J $. Montrer que $ y $ est solution de l'équation sur $ I' $ si et seulement si il existe $ c \in \mathbb{R} $ tel que $ G(y(x)) = U(x) + C $ pour tout $ x \in I' $.
5. En déduire que, sous les mêmes hypothèses, il existe pour tout $ x_0 \in I $ et tout $ y_0 \in J $ un intervalle $ I' \subset I $ et une fonction $ C^1 $, soit $ y : I' \to J $ tels que $ y $ est solution de l'équation sur $ I' $ et ne peut pas être étendue en une solution sur un intervalle contenant strictement $ I' $.
6. Traiter comme cas particulier l'équation : $ y' = y^2 $, avec la condition initiale $ y(0) = y_0 > 0 $.

## Exercice 3 : Équations différentielles linéaires du second ordre

On considère l'équation de Legendre :

$$ (1 - x^2)y'' - 2xy' + 2y = 0 $$

sur l'intervalle $ ] -1,1[ $. Vérifier que $ y = x $ est solution, et en déduire toutes les solutions.

## Exercice 4 : Equations différentielles linéaires du second ordre 1
On considère l'équation :

$$ x^2 y'' - 2y = 0 $$

sur l'intervalle $ ]0, \infty[ $. Vérifier que $ y = x^2 $ est solution, et en déduire toutes les solutions de l'équation.

## Exercice 5 : Equations différentielles linéaires du second ordre 2
On considère l'équation :

$$ x^2 y'' - xy' + y = x^2 $$

sur l'intervalle $ ]0, \infty[ $. Vérifier que $ y = x $ est solution de l'équation homogène, et en déduire l'ensemble des solutions satisfaisant $ y(1) = 1 $ et $ y'(1) = 0 $.

## Exercice 6 : Équations différentielles linéaires à coefficients constants

Résoudre les équations suivantes :

1. $ y'' + y = \tan(x) $.
2. $ y'' - y = \frac{2e^x}{e^x -1} $.
3. $ y'' + a^2 y = e^x $, $ a \in \mathbb{R} $.
4. $ y'' - y = e^x $.
5. $ y''' + y = x $.
6. $ y''' - 4y' = \sin x $.
7. $ y''' + y = 2 \cosh x + x^2 \cos x $.
8. $ y'' - 2y' + 3y = x^3 + \sin(x) $.
9. $ y'' - 4y' + 4y = x^3 e^{2x} + x e^{2x} $.
10. $ y'' - 5y' + 6y = x + (x^2 + 1)e^{2x} $.

## Exercice 7 : Équations diverses

1. On considère une équation **exacte**, soit de la forme :
   
   $$ y' = -\frac{f(x,y)}{g(x,y)} $$
   
   avec $$ \frac{\partial f(x,y)}{\partial y} = \frac{\partial g(x,y)}{\partial x}. $$
   
   Montrer que les solutions sont les fonctions $ y $ qui satisfont l'équation implicite :
   
   $$ U(x,y) = C $$
   
   où $ C $ est une constante et $ U(x,y) $ est définie par l’une des formules équivalentes :
   
   $$ U(x,y) = \int_{x_0}^{x} f(t, y_0) dt + \int_{y_0}^{y} g(x,t) dt = \int_{y_0}^{y} g(x_0,t) dt + \int_{x_0}^{x} f(t, y) dt, $$
   
   $ x_0 $ et $ y_0 $ étant des constantes arbitraires. Appliquer ce résultat à l’équation :
   
   $$ y' = -\frac{y}{x+y}. $$
   
2. On considère **l'équation de Lagrange**, du type :
   
   $$ y = x f(y') + g(y') $$
   
   avec $ f(u) \neq u $ pour tout $ u $. Montrer que la résolution de cette équation se ramène à celle d’une équation du premier ordre. (On pourra poser $ y' = p $, puis prendre $ p $ comme paramètre.)
   
3. On considère maintenant **l'équation de Clairaut**, de la forme :
   
   $$ y = xy' + g(y'). $$
   
   Montrer qu’on peut exprimer la solution sous forme paramétrique en $ (x,y) $ dépendant du paramètre $ p $ défini par $ p = y' $.

