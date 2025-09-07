---
title: "Convergence et calcul d'intégrales impropres"
date: 2025-09-07T07:18:16+02:00
# weight: 1
# aliases: ["/first"]
tags: ["Analyse", "Convergence" , "Intérgales"]
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

# Convergence et calcul d'intégrales impropres

## Exercice 1 : Convergence et calcul d'intégrales impropres

Étudier la convergence des intégrales impropres suivantes et, lorsqu'elles sont convergentes, calculer leurs valeurs.

1. $$
   \int_1^3 \frac{dt}{\sqrt{(t-1)(3-t)}}
   $$
2. Pour $ b > 0 $.
   $$
   \int_0^b \ln(t) dt
   $$
3. $$
   \int_1^{+\infty} \frac{e^{1/t}}{t^2} dt
   $$
4. $$
   \int_0^x \frac{t \ln(t)}{(t^2+1)^2} dt
   $$

## Exercice 2 : Convergences sans calcul

Étudier la convergence des intégrales impropres suivantes :

1. $$
   \int_1^{+\infty} e^{-t^2} dt
   $$
2. $$
   \int_0^\infty \frac{\sin t}{1+t^2} dt
   $$
3. $$
   \int_0^1 \frac{dt}{\ln t}
   $$
4. En fonction de $ \alpha \in \mathbb{R} $
   $$
   \int_0^\infty \frac{\sqrt{t+1}}{t^\alpha} dt
   $$
5. Pour $ \alpha > 0 $
    $$
   \int_0^1 \frac{\ln(1+t^\alpha)}{1-\cos t} dt
   $$

6. $$
   \int_0^\infty \frac{\sin t}{t} dt
   $$
   Idée : remarquer que  
   $$
   \int_x^y \frac{\sin t}{t} dt = \frac{1-\cos y}{y} - \frac{1-\cos x}{x} + \int_x^y \frac{1-\cos t}{t^2} dt.
   $$
7. Pour $ \alpha > 0 $ 
   $$
   \int_0^1 \frac{\ln(1+t^\alpha)}{1-\cos t} dt
   $$
8. $$
   \int_0^\infty \frac{dt}{\sqrt{e^t -1}}
   $$

   Idée : remarquer que  
   $$
   \int_x^y \frac{\sin t}{t} dt = \frac{1-\cos y}{y} - \frac{1-\cos x}{x} + \int_x^y \frac{1-\cos t}{t^2} dt.
   $$


## Exercice 3 : Intégrales de fonctions particulières

1. $$
   \int_0^{\pi/2} \ln(\sin x) dx
   $$
   converge.
2. $$
   \int_0^{\pi/2} \ln(\sin x) dx = \int_0^{\pi/2} \ln(\cos x) dx
   $$
3. $$
   \int_0^{\pi/2} \ln(\sin x) dx = 2 \int_0^{\pi/2}  \ln(\sin x) dx
   $$
4. $$
   \int_0^{\pi/2} \ln(\sin x) dx = -\frac{\pi}{2} \ln 2
   $$
5. $$
   \int_0^1 \frac{\ln x}{\sqrt{1-x^2}} dx = -\frac{\pi}{2} \ln 2
   $$

## Exercice 4 : Equivalences de fonctions non positives

Construire deux fonctions continues $ f,g : [0, \infty[ \to \mathbb{R} $ telles que $ f \simeq g $ en $ \infty $, que $ \int_0^\infty f(t) dt $ converge, mais que $ \int_0^\infty g(t) dt $ diverge.


## Exercice 5 : Convergence et Calcul d’une Intégrale

1. En étudiant la fonction $ f $ définie sur $ \mathbb{R}_+ $ par  
   $$
   f(x) = \frac{\ln x}{\sqrt{x}}
   $$
   montrer que $ \ln x < \sqrt{x} $.

2. Montrer que  
   $$
   \int_{0}^{+\infty} \frac{\ln x}{1 + x^2}dx
   $$
   est convergente.

3. Calculer  
   $$
   \int_{0}^{+\infty} \frac{\ln x}{1 + x^2}dx.
   $$


## Exercice 6 : Une Famille d’Intégrales

Soit  
$$
I_n = \int_{0}^{1} \frac{x^n}{\sqrt{1 - x^2}} dx, \quad \forall n \in \mathbb{Z}.
$$

1. Étudier la convergence de $ I_n $.
2. Calculer $ I_0 $ et $ I_1 $.
3. Pour $ n > 1 $, établir une relation entre $ I_n $ et $ I_{n-2} $, puis calculer $ I_n $.


## Exercice 7 : La Fonction Gamma

Pour tout $ x > 0 $, on pose  
$$
\Gamma(x) = \int_{0}^{\infty} t^{x-1} e^{-t} dt.
$$

1. Montrer que cette intégrale impropre est convergente pour tout $ x > 0 $.
2. Montrer que pour tout $ x > 1 $, on a  
   $$
   \Gamma(x) = (x - 1) \Gamma(x - 1).
   $$
   En déduire la valeur de $ \Gamma(n) $ pour tout $ n \in \mathbb{N}, n > 0 $.

3. Montrer que  
   $$
   \lim_{x \to 0^+} \Gamma(x) = \infty.
   $$

4. Montrer que $ \Gamma(1/2) = \sqrt{\pi} $.  
   On pourra admettre que  
   $$
   \int_{0}^{\infty} e^{-x^2} dx = \frac{\sqrt{\pi}}{2}.
   $$
   

5. Montrer que pour tout $ p > 0 $,  
   $$
   \int_{0}^{\infty} t^{x-1} e^{-pt} dt = \frac{\Gamma(x)}{p^x}.
   $$

6. Montrer que pour tout $ x > 0 $,  
   $$
   \Gamma(x) = \int_{0}^{1} (\log(1/t))^{x-1} dt.
   $$



## Exercice 8 : La Fonction Béta

Soient $ x, y \in \mathbb{R}_+^* $. On définit :  
$$
\beta(x,y) = \int_{0}^{1} t^{x-1} (1 - t)^{y-1} dt.
$$

1. Montrer que l’intégrale impropre est convergente si et seulement si $ x > 0 $ et $ y > 0 $.
2. Montrer que $ \beta $ est symétrique, c’est-à-dire que $ \beta(x,y) = \beta(y,x) $.
3. Donner une relation entre $ \beta(x+1, y) $ et $ \beta(x, y+1) $.
4. Calculer $ \beta(x,1) $ et en déduire une formule pour $ \beta(x,y) $ lorsque $ x,y \in \mathbb{N}^* $.
5. Montrer que  
   $$
   \beta(x,y) = 2 \int_{0}^{\pi/2} \sin^{2x-1}(\theta) \cos^{2y-1}(\theta) d\theta.
   $$
