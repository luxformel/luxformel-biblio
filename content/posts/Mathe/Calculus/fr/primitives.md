---
title: "Primitives"
date: 2025-09-07T07:11:27+02:00
# weight: 1
# aliases: ["/first"]
tags: ["Analyse", "Primitives"]
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

# Primitives

## Exercice 1 : Calculs d’intégrales

Calculer :  

1. $$
   \int_0^x t e^t dt.
   $$

2. $$
   \int_1^e \frac{\ln t}{t} dt.
   $$

3. $$
   \int_1^{e^2} \frac{dt}{t \ln t}.
   $$

4. $$
   \int_{\pi/4}^{\pi/2} \tan t dt.
   $$

5. $$
   \int_0^x \frac{1}{1+t^2} dt.
   $$

6. $$
   \int_0^1 e^t \cos t dt.
   $$

7. Pour $ x > 0 $, calculer :

   $$
   \int_1^x \ln t dt.
   $$

8. $$
   \int_0^x \cos^5 t e^t dt.
   $$

9. $$
   \int_0^1 \sqrt{1 - t^2} dt.
   $$


## Exercice 2 : Une famille d'intégrales

Soit $ x \in \left] \frac{\pi}{2}, \frac{\pi}{2} \right[ $ et $ n \in \mathbb{N} $. On définit :
$$ F_n(x) = \int_0^x (\tan t)^n dt. $$

1. Calculer $ F_0(x) $, $ F_1(x) $ et $ F_2(x) $.
2. Montrer que :
   $$ F_{n+2}(x) + F_n(x) = \frac{1}{n+1} (\tan x)^{n+1}, $$
   puis calculer $ F_4(x) $.
3. Soit $ I_n = F_n \left( \frac{\pi}{4} \right) $. Montrer que $ (I_n)_{n \in \mathbb{N}} $ est une suite décroissante et convergente.
4. Montrer que pour tout $ x \in \left[ 0, \frac{\pi}{4} \right] $, $ \tan^n x \leq \frac{1}{\cos^2 x} \tan^n x $. En déduire que $ I_n \leq \frac{1}{n+1} $ et calculer $ \lim_{n \to \infty} I_n $.



## Exercice 3 : Fractions rationnelles

Déterminer une primitive des fonctions suivantes :

1. $ \frac{dt}{t^2 + a^2} $, $ a \neq 0 $.
2. $ \frac{1}{x^2 + 6x + 12} $.
3. $ \frac{x}{x^2 + 3x + 2} $.
4. $ \frac{x^2}{(x+2)^2 (x+1)} $.
5. $ \frac{1}{x(x^2 + 1)} $.
6. $ \frac{2x+1}{x^2(x+1)} $.
7. $ \frac{1}{x^2(x+1)^2} $.
8. $ \frac{3}{x^3+1} $.
9. $ \frac{x^2 + 13}{x(x^2 + 6x + 13)} $.



## Exercice 4 : Autres fractions rationnelles

Calculer toutes les primitives des fonctions suivantes :

1. $ f(x) = \frac{1}{x^3 - x^2} $.
2. $ g(x) = \frac{1}{x^3 - x^2 + x + 1} $.
3. $ h(x) = \frac{x^3 - 3x^2 + x + 1}{x - 3} $.
4. $ f(x) = \frac{x^3 + 2x + 1}{x^2 - 5x + 6} $.


## Exercice 5 : Dérivées successives d'une fraction rationnelle

Pour tout $ x $ dans $ ]-1,1[ $, on pose :
$$ f(x) = \frac{4x+6}{(x-1)^2 (x+1)}. $$

1. Déterminer la décomposition en éléments simples de $ f(x) $.
2. Déterminer, pour tout $ n \in \mathbb{N} $, la dérivée $ n^{\text{ième}} $ de $ f $.


## Exercice 6 : Intégrales se ramenant à des fractions rationnelles

Déterminer une primitive des fonctions suivantes :

1. $ \frac{x^3}{\sqrt{x-1}} $
2. $ \frac{x+1}{x\sqrt{x-2}} $
3. $ \frac{1}{\sqrt{x+1} + \sqrt[3]{x+1}} $
4. $ \sqrt{\frac{1-x}{1+x}} $
5. $ \frac{1}{\sqrt{-x^2+2x+5}} $
6. $ \sqrt{x^2 + 2x + 5} $
7. $ \frac{1}{\sqrt{x^2 + k^2}}, \quad k \in \mathbb{N}, k > 0. $
8. $ \sqrt{x^2 + k^2}, \quad k \in \mathbb{N}, k > 0. $
9. $ \sqrt{k^2 - x^2}, \quad k \in \mathbb{N}, k > 0. $
10. $ \frac{1}{3x^2 + x + 5} $
11. $ \frac{1}{\sin(x)} $
12. $ \frac{1}{a \cos(x) + b}, \quad a, b \neq 0. $
13. $ \frac{1}{a \cos^2(x) + b \sin^2(x)} \quad a, b \neq 0. $


## Exercice 7 : Autres intégrales

Déterminer une primitive de chacune des fonctions suivantes :

1. $ \cos^3(x) \sin^2(x) $. (On pourra poser $ t = \sin(x) $.)
2. $ \cos^3(x) \sin^4(x) $. (On pourra poser $ t = \sin(x) $.)
3. $ \cos^2(x) \sin(x) $. (On pourra poser $ t = \cos(x) $.)
4. $ \cos^2(x) \sin^3(x) $. (On pourra poser $ t = \cos(x) $.)
5. $ \cos^2(x) \sin^2(x) $. (On pourra poser $ t = \tan(x/2) $, ou bien linéariser l’expression.)
6. $ e^x \sin(x) $.
7. $ x^2 e^x $. (On pourra procéder par intégrations par parties successives.)
8. $ (t^2 + t + 1) \cos(t) $. (On pourra procéder par intégrations par parties successives.)
9. $ (t^2 - t + 2) \cos(t) e^t $. (On pourra procéder par intégrations par parties successives.)
10. $ (ax + b)^n $, pour $ a \neq 0 $ et $ b \neq -1 $.
11. $ a^{\alpha x} $, pour $ \alpha \neq 0, a > 0, a \neq 1 $.
12. $ \log(t) $.
13. $ \arctan(t) $.
14. $ \arcsin(x) $.


## Exercice 8 : Formule de Wallis

Soit  
$$
I_n = \int_0^{\pi/2} \sin^n(t) \, dt, \quad n \in \mathbb{N}.
$$
Montrer que pour $ n \geq 2 $ :
$$
I_n = \frac{n - 1}{n} I_{n-2}.
$$

2. En déduire que pour tout $ n \in \mathbb{N} $ :
   $$
   I_{2n} = \frac{1 \cdot 3 \cdot 5 \cdots (2n - 1)}{2 \cdot 4 \cdot 6 \cdots (2n)} \cdot \frac{\pi}{2},
   $$
   $$
   I_{2n-1} = \frac{2 \cdot 4 \cdot 6 \cdots (2n)}{1 \cdot 3 \cdot 5 \cdots (2n + 1)} \cdot \frac{\pi}{2}.
   $$

3. Montrer que: $$ \lim_{n \to \infty} \frac{I_{2n}}{I_{2n+1}} = 1 $$

4. En déduire que :
   $$
   \lim_{n \to \infty} n \left( \frac{1 \cdot 3 \cdot 5 \cdots (2n - 1)}{2 \cdot 4 \cdot 6 \cdots (2n)} \right)^2 = \frac{1}{\pi}.
   $$


## Exercice 9 : Lemme de Lebesgue

Soit une fonction $ f : [a, b] \to \mathbb{R} $, on définit $ u : \mathbb{R}_+ \to \mathbb{R} $ par :
$$
u(\lambda) = \int_a^b f(t) \sin(\lambda t) dt.
$$
Montrer que $ \lim_{\lambda \to \infty} u(\lambda) = 0 $ lorsque :

1. $ f $ est $ \mathcal{C}^1 $.
2. $ f $ est en escalier.
3. $ f $ est continue par morceaux.



## Exercice 10 : Limite d’une famille d’intégrales

Soient $ f, g : [a, b] \to \mathbb{R} $ deux fonctions continues strictement positives. Pour $ n \in \mathbb{N} $, on définit :

$$
u_n := \left( \int_a^b f^n(x) g(x) dx \right)^{1/n}.
$$

1. Montrer que la suite $ (u_n)_{n \in \mathbb{N}} $ est convergente.
2. Calculer sa limite (commencer avec $ g = 1 $).



## Exercice 11 : Irrationalité de $ \pi $

Soit $ n \in \mathbb{N} $, $ a, b \in \mathbb{Z} $ avec $ b \neq 0 $. Pour $ x \in \mathbb{R} $, on définit :

$$
P_n(x) = \frac{x^n (a - bx)^n}{n!}.
$$

Supposons que $ \pi = \frac{a}{b} $ et définissons :

$$
I_n = \int_0^\pi P_n(t) \sin t \, dt.
$$

1. Montrer que, pour tout $ k \in \mathbb{N} $, $ P_n^{(k)}(0) \in \mathbb{Z} $ et $ P_n^{(k)}\left( \frac{a}{b} \right) \in \mathbb{Z} $.
2. Montrer que, pour tout $ n \in \mathbb{N} $, $ I_n \in \mathbb{Z} $.
3. Montrer que $ \lim_{n \to \infty} I_n = 0 $.
4. Conclure.
