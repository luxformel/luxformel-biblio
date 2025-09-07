---
title: "Axiom Of Completeness"
date: 2025-09-07T08:43:44+02:00
# weight: 1
# aliases: ["/first"]
tags: ["Analysis"]
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

# Axiom Of Completeness

## Exercise 1

Let $ \mathbb{Z}_5 = \{0, 1, 2, 3, 4\} $ and define addition and multiplication modulo 5. In other words, compute the integer remainder when $ a + b $ and $ ab $ are divided by 5, and use this as the value for the sum and product, respectively.

1. Show that, given any element $ z \in \mathbb{Z}_5 $, there exists an element $ y $ such that $ z + y = 0 $. The element $ y $ is called the *additive inverse* of $ z $.
2. Show that, given any $ z \neq 0 $ in $ \mathbb{Z}_5 $, there exists an element $ x $ such that $ zx = 1 $. The element $ x $ is called the *multiplicative inverse* of $ z $.
3. The existence of additive and multiplicative inverses is part of the definition of a *field*. Investigate the set $ \mathbb{Z}_4 = \{0, 1, 2, 3\} $ (where addition and multiplication are defined modulo 4) for the existence of additive and multiplicative inverses.  
   Make a conjecture about the values of $ n $ for which additive inverses exist in $ \mathbb{Z}_n $, and then form another conjecture about the existence of multiplicative inverses.

## Exercise 2

1. Write a formal definition in the style of Definition 1.3.2 for the *infimum* or *greatest lower bound* of a set.
2. Now, state and prove a version of Lemma 1.3.7 for greatest lower bounds.

## Exercise 3

1. Let $ A $ be bounded below, and define  
   $$
   B = \{ b \in \mathbb{R} : b \text{ is a lower bound for } A \}.
   $$  
   Show that $ \sup B = \inf A $.
2. Use (1) to explain why there is no need to assert that greatest lower bounds exist as part of the Axiom of Completeness.
3. Propose another way to use the Axiom of Completeness to prove that sets bounded below have greatest lower bounds.

## Exercise 4

Assume that $A$ and $B$ are nonempty, bounded above, and satisfy $B \subseteq A$. Show that $ \sup(B) \leq \sup(A) $.
.

## Exercise 5

Let $A \subseteq \mathbb{R}$ be bounded above, and let $c \in \mathbb{R}$. Define the sets $c + A$ and $cA$ by $c + A = \{c + a : a \in A \}$ and $cA = \{ca : a  \in A\}$.

1. Show that $\sup(c+A) = c + \sup(A)$
2. If $c \geq 0$, show that $\sup(cA) = c \sup(A)$

## Exercise 6

Compute, without proofs, the suprema and infima of the following sets:

1. $\{ n \in \mathbb{N} : n^2 < 10 \}$
2. $\{ \frac{n}{m+n} : n,m \in \mathbb{N} \}$
3. $\{ \frac{n}{2n+1} : n \in \mathbb{N} \}$
4. $\{ \frac{n}{m} : n,m \in \mathbb{N} \text{with} m+n \leq 10 \}$

## Exercise 7

Prove that if $a$ is an upper bound for $A$, and if $a$ is also an element of $A$, then it must be that $a = \sup A$.

## Exercise 8

If $\sup A < \sup B$, then show that there exists an element $b \in B$ that is an upper bound for $A$.

## Exercise 9

Without formal proofs for the moment, decide if the following statements about suprema and infima are true or false. For any that are false, supply an example where the claim in question does not appear to hold.

1. A finite, nonempty set always contains its supremum.
2. If $a < L$ for every element $a$ in the set $A$, then $\sup A < L$.
3. If $A$ and $B$ are sets with the property that $a < b$ for every $a \in A$ and every $b \in B$, then it follows that $\sup A < \inf B$.
4. If $\sup A = s$ and $\sup B = t$, then $\sup(A + B) = s + t$. The set $A + B$ is defined as $A + B = \{a + b : a \in A \text{ and } b \in B\}$.
5. If $\sup A \leq \sup B$, then there exists an element $b \in B$ that is an upper bound for $A$.

## Exercise 10

Let $ A \subseteq \mathbb{R} $ be nonempty and bounded above. Let $ B = \{ \sup A_n : A_n \subseteq A, \text{ and } A_n \text{ is finite} \} $. Show that $ \sup B = \sup A $.  
(*Hint:* Use the density of finite subsets in a bounded set.)

## Exercise 11

Let $ A_n = \left\{ \frac{k}{n} : k \in \mathbb{N}, \; 0 \leq k \leq n \right\} \subseteq \mathbb{R} $. 

1. Determine $ \sup A_n $ and $ \inf A_n $ for a given $ n \in \mathbb{N} $.
2. Define $ A = \bigcup_{n=1}^\infty A_n $. Compute $ \sup A $ and $ \inf A $.
3. Is $ A $ dense in $ [0, 1] $? Justify your answer.

## Exercise 12

Let $ A, B \subseteq \mathbb{R} $ be nonempty and bounded above. Prove or disprove the following statements:

1. $ \sup(A \cup B) = \max(\sup A, \sup B) $
2. $ \inf(A \cup B) = \min(\inf A, \inf B) $
3. $ \sup(A \cap B) \leq \min(\sup A, \sup B) $

Give counterexamples where a statement does not hold.

## Exercise 13

Let $ A \subseteq \mathbb{R} $ be a nonempty set that is bounded above. Assume $ (a_n) $ is a sequence in $ A $ such that $ a_n \to \sup A $. Prove that:

1. $ \sup A $ is the least upper bound of $ A $.
2. No sequence in $ A $ can converge to a limit greater than $ \sup A $.
3. Construct such a sequence $ (a_n) $ explicitly for the set $ A = \left\{ 1 - \frac{1}{n} : n \in \mathbb{N} \right\} $.

