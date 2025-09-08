---
title: "Fonctions de plusieurs variables"
date: 2025-09-07T07:21:58+02:00
# weight: 1
# aliases: ["/first"]
tags: ["Analyse", "Fonctions"]
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

# Fonctions de plusieurs variables

## Exercice 1 : Continuité de fonctions de deux variables

Étudier la continuité en $(0,0)$ des fonctions suivantes :

1. $$f(x, y) = \frac{xy(x^2 - y^2)}{x^2 + y^2}, \quad f(0,0) = 0.$$

2. $$f(x, y) = \frac{x^4 + y^4}{x^2 + y^2}, \quad f(0,0) = 0.$$

3. $$f(x, y) = \frac{x^2 y^2}{x^2 + y^2}, \quad f(0,0) = 0.$$

4. $$f(x, y) = \frac{xy^2}{x^2 + y^4}, \quad f(0,0) = 0.$$

5. $$f(x, y) = \frac{\sin{|xy|}}{x^2 + y^4}, \quad f(0,0) = 0.$$

6. $$f(x, y) = \frac{x^4y^4}{x^2 + 2xy + y^2}, \quad f(0,0) = 0.$$

7. $$f(x, y) = \frac{x^2 + 2xy + y^2}{x^2 + y^2}, \quad f(0,0) = 0.$$


## Exercice 2 : Différentiabilité de fonctions de deux variables

Étudier la continuité et la différentiabilité des fonctions suivantes, puis lorsqu'elles sont différentiables, donner l'équation de leur plan tangent à la surface d'équation $z = f(x, y)$ en $(1,0,f(1,0))$ :


1. $$f(x, y) = x^2 y^2 \ln(x^2 + y^2), \quad f(0,0) = 0.$$

2. $$f(x, y) = (x^2 + y^2) \sin\left(\frac{1}{\sqrt{x^2 + y^2}}\right), \quad f(0,0) = 0.$$

3. $$f(x, y) = \frac{x^2y}{x^2 + y^2}, \quad f(0,0) = 0.$$

4. $$f(x, y) = xy \frac{x^2 - y^2}{x^2 + y^2}, \quad f(0,0) = 0.$$


## Exercice 3 : Une fonction de deux variables

On définit $ f : \mathbb{R}^2 \rightarrow \mathbb{R} $ par :

$$
f(x, y) = 
\begin{cases}
\frac{x^2 y \sqrt{x^2 + y^2}}{x^4 + y^2} & \text{si } (x, y) \neq (0,0) \\
0 & \text{si } (0,0)
\end{cases}
$$

1. Étudiez la continuité de $ f $ en $ (0,0) $.

2. Étudiez l’existence de dérivées partielles $ \frac{\partial f}{\partial x} $ et $ \frac{\partial f}{\partial y} $ en $ (0,0) $.

3. Soit un vecteur $ u = (1, \alpha) $. Étudiez l’existence d’une dérivée selon le vecteur $ u $ en $ (0,0) $. Déterminez cette dérivée si possible.

4. Étudiez la différentiabilité de $ f $ en $ (0,0) $.

5. Étudiez la continuité de $ f $ en un point quelconque $ (x, y) \neq (0,0) $.

6. La fonction $ f $ est-elle de classe $ C^1 $ ? Pourquoi ?

7. Peut-il y avoir un extrémum (maximum ou minimum) en $ (0,0) $ ? Pourquoi ? (*réponse courte !*)

## Exercice 4 : Étude de points critiques

Soit $ f : \mathbb{R}^2 \rightarrow \mathbb{R} $ la fonction définie par :

$$f(x, y) = x^2 - 2xy + \frac{y^4}{2}.$$

1. Déterminer l’équation du plan tangent à la surface $ z = f(x, y) $ en $ (1,0,1) $.

2. Déterminer l’ensemble des points $ (x, y) $ tels que $ df(x, y) = 0 $. Préciser s’il s’agit d’extrémum.


## Exercice 5 : Décomposition des polynômes en éléments irréductibles dans $ \mathbb{C} $

On considère un polynôme à coefficients complexes :

$$
P = a_n X^n + a_{n-1} X^{n-1} + \dots + a_1 X + a_0,
$$

avec $ n \geq 1, \ a_0, a_1, \dots, a_n \in \mathbb{C}, \ a_n \neq 0 $.  
On va s’intéresser à la fonction $ f : z \mapsto |P(z)|^2 $ définie sur $ \mathbb{C} $, où $ \mathbb{C} $ est identifié avec $ \mathbb{R}^2 $.

1. Montrer que :

$$
\lim_{r \to \infty} \min_{|z| = r} |P(z)|^2 = \infty.
$$

2. En déduire que $ f $ admet au moins un minimum local, en un point $ z_0 \in \mathbb{C} $. On va montrer que $ z_0 $ est nécessairement une racine de $ P $.

3. On note $ Q(X) = P(X - z_0) $. Montrer que $ z \mapsto |Q(z)|^2 $ admet un minimum local en 0, et que 0 est une racine de $ Q $ si et seulement si $ z_0 $ est une racine de $ P $.

4. Montrer qu’on peut écrire :

$$
Q = b_n X^n + \dots + b_1 X + b_0,
$$

avec $ b_n \neq 0 $.

5. Montrer qu’il existe un plus petit entier $ k \geq 1 $ tel que $ b_k \neq 0 $ mais que $ b_l = 0 $ pour $ 1 \leq l < k $.  
On le notera $ p $. Montrer qu’on a alors :

$$
Q = b_n X^n + \cdots + b_p X^p + b_0.
$$

6. On suppose maintenant que $ b_0 \neq 0 $. Montrer qu’il existe $ z_1 \in \mathbb{C} $ tel que pour $ t > 0 $ assez proche de 0, $ |b_p (tz_1)^p + b_0|^2 < |b_0|^2 $.

7. En déduire que $ z \mapsto |Q(z)|^2 $ ne peut pas admettre de minimum local non nul en 0, puis que 0 est racine de $ Q $.

8. Expliquer pourquoi ceci montre que $ P $ admet au moins une racine complexe.

9. En déduire que si $ P \in \mathbb{C}[X] $ est un polynôme de degré $ n $ unitaire, il existe $ z_1, \dots, z_n \in \mathbb{C} $ tel que

$$
P = (X - z_1)(X - z_2) \cdots (X - z_n).
$$


## Exercice 6 : Laplacien

Soit $ f : U \subset \mathbb{R}^p \rightarrow \mathbb{R} $ de classe au moins $ C^2 $.  
On appelle **Laplacien** et on note l’application :

$$
\Delta : f \mapsto \Delta f := \sum_{i=1}^p \frac{\partial^2 f}{\partial x_i^2}.
$$

On dit que $ f $ est **harmonique** lorsque $ \Delta f = 0 $.  
Calculer le Laplacien des fonctions suivantes :

1. $ f(x, y) = e^x \cos y $

2. $ f(x, y, z) = \sqrt{x^2 + y^2 + z^2} $

3. $ f(x, y) = \frac{1}{\sqrt{x^2 + y^2}} $

4. $ f(x, y) = \ln \sqrt{x^2 + y^2} $

5. Soit $ \mathbb{R}^2 \rightarrow \mathbb{R}^2, \ (\rho, \theta) \mapsto (x, y) = (\rho \cos \theta, \rho \sin \theta) $.  
   Calculer :

   $$
   \frac{\partial^2 f}{\partial \rho^2} + \frac{1}{\rho^2} \frac{\partial^2 f}{\partial \theta^2}
   $$

   d’une fonction $ C^2 : \mathbb{R}^2 \rightarrow \mathbb{R}, \ (x, y) \mapsto f(x, y) $


## Exercice 7 : Théorème des fonctions implicites

1. Montrer que la relation :

$$
x^4 + y^3 - 2x^2 y - 1 = 0
$$

définit implicitement $ y $ en fonction de $ x $ au voisinage de $ (0, 1) $, puis donner un développement limité à l’ordre 3 au voisinage de 0 de la fonction qui à $ x $ associe $ y $.

2. Montrer que la relation :

$$
\sin x + y + e^x = 1
$$

définit implicitement $ y $ en fonction de $ x $ au voisinage de $ (0, 0) $, puis donner un développement limité à l’ordre 3 au voisinage de 0 de la fonction qui à $ x $ associe $ y $.
