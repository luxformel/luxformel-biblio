---
title: "Preliminary Analysis"
date: 2025-09-07T08:45:14+02:00
# weight: 1
# aliases: ["/first"]
tags: ["Analysis"]
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

# Preliminary Analysis

## Exercise 1

 Prove that $\sqrt{3}$ is irrational. Does a similar argument work to show $\sqrt{6}$ is irrational?

## Exercise 2

Decide which of the following represent true statements about the nature of sets. For any that are false, provide a specific example where the statement in question does not hold.

1. If $ A_1 \supseteq A_2 \supseteq A_3 \supseteq A_4 \supseteq \cdots $ are all sets containing an infinite number of elements, then the intersection $  \bigcap_{n=1}^{\infty} A_n $ is infinite as well.
2. If $ A_1 \supseteq A_2 \supseteq A_3 \supseteq A_4 \supseteq \cdots $ are all finite, nonempty sets of real numbers, then the intersection $ \bigcap_{n=1}^{\infty} A_n $ is finite and nonempty.
3. $A \cap (B\cup C) = (A \cap B )\cup C$
4. $A \cap (B\cap C) = (A \cap B )\cap C$
5. $A \cap (B\cup C) = (A \cap B ) \cup (A \cap C)$

## Exercise 3: De Morgan's Law

Let $ A $ and $ B $ be subsets of $ \mathbb{R} $.

1. If $ x \in (A \cap B)^c $, explain why $ x \in A^c \cup B^c $. This shows that $ (A \cap B)^c \subseteq A^c \cup B^c $.
2. Prove the reverse inclusion $ (A \cap B)^c \supseteq A^c \cup B^c $, and conclude that  
   $ (A \cap B)^c = A^c \cup B^c $.
3. Show $ (A \cup B)^c = A^c \cap B^c $ by demonstrating inclusion both ways.

## Exercise 4

Verify the triangle inequality in the special cases where:

1. $ a $ and $ b $ have the same sign;
2. $ a \geq 0, \, b < 0, $ and $ a + b \geq 0 $.

## Exercise 5

Use the triangle inequality to establish the inequalities:

1. $ |a - b| \leq |a| + |b| $;
2. $ ||a| - |b|| \leq |a - b| $.

## Exercise 6

Given a function $ f $ and a subset $ A $ of its domain, let $ f(A) $ represent the range of $ f $ over the set $ A $; that is, $ f(A) = \{ f(x) : x \in A \} $.

1. Let $ f(x) = x^2 $. If $ A = [0,2] $ and $ B = [1,4] $, find $ f(A) $ and $ f(B) $. Does $ f(A \cap B) = f(A) \cap f(B) $ in this case? Does $ f(A \cup B) = f(A) \cup f(B) $?
2. Find two sets $ A $ and $ B $ for which $ f(A \cap B) \neq f(A) \cap f(B) $.
3. Show that, for an arbitrary function $ g : \mathbb{R} \to \mathbb{R} $, it is always true that  
   $ g(A \cap B) \subseteq g(A) \cap g(B) $ for all sets $ A, B \subseteq \mathbb{R} $.
4. Form and prove a conjecture about the relationship between $ g(A \cup B) $ and $ g(A) \cup g(B) $ for an arbitrary function $ g $.

## Exercise 7

Given a function $ f : D \to \mathbb{R} $ and a subset $ B \subseteq \mathbb{R} $, let  
$ f^{-1}(B) = \{ x \in D : f(x) \in B \} $. This set is called the *preimage* of $ B $.

1. Let $ f(x) = x^2 $. If $ A = [0,4] $ and $ B = [-1,1] $, find $ f^{-1}(A) $ and $ f^{-1}(B) $.  
   Does $ f^{-1}(A \cap B) = f^{-1}(A) \cap f^{-1}(B) $ in this case?  
   Does $ f^{-1}(A \cup B) = f^{-1}(A) \cup f^{-1}(B) $?
2. The good behavior of preimages demonstrated in (1) is completely general.  
   Show that for an arbitrary function $ g : \mathbb{R} \to \mathbb{R} $, it is always true that  
   $ g^{-1}(A \cap B) = g^{-1}(A) \cap g^{-1}(B) $ and  
   $ g^{-1}(A \cup B) = g^{-1}(A) \cup g^{-1}(B) $ for all sets $ A, B \subseteq \mathbb{R} $.

## Exercise 8

Form the logical negation of each claim. One way to do this is to add  
“It is not the case that...” in front of each assertion.

1. For all real numbers satisfying $ a < b $, there exists an $ n \in \mathbb{N} $ such that  
   $ a + \frac{1}{n} < b $.
2. Between every two distinct real numbers, there is a rational number.
3. For all natural numbers $ n \in \mathbb{N} $, $ \sqrt{n} $ is either a natural number or an irrational number.
4. Given any real number $ x \in \mathbb{R} $, there exists $ n \in \mathbb{N} $ satisfying $ n > x $.

## Exercise 9

Show that the sequence $ (x_1, x_2, x_3, \ldots) $ defined in Example 1.2.7 is bounded above by 2;  
that is, prove that $ x_n \leq 2 $ for every $ n \in \mathbb{N} $.

## Exercise 10

Let $ y_1 = 1 $, and for each $ n \in \mathbb{N} $ define  
$$ y_{n+1} = \frac{3y_n + 4}{4}. $$

1. Use induction to prove that the sequence satisfies $ y_n < 4 $ for all $ n \in \mathbb{N} $.
2. Use another induction argument to show the sequence $ (y_1, y_2, y_3, \ldots) $ is increasing.

## Exercise 11

If a set $ A $ contains $ n $ elements, prove that the number of different subsets of $ A $ is equal to $ 2^n $.  
(Keep in mind that the empty set $ \emptyset $ is considered to be a subset of every set.)

## Exercise 12

For this exercise, assume Exercise 3 has been successfully completed.

1. Show how induction can be used to conclude that  
   $$
   (A_1 \cup A_2 \cup \cdots \cup A_n)^c = A_1^c \cap A_2^c \cap \cdots \cap A_n^c
   $$
for any finite $n \in \mathbb{N} $
2. Explain why induction cannot be used to conclude
    $$ \left( \bigcup_{n=1}^{\infty} A_n \right)^c = \bigcap_{n=1}^{\infty} A_n^c $$
3. Is the statement in part (b) valid? If so, write a proof that does not use
induction.