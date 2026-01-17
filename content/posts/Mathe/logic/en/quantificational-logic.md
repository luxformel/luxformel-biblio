---
title: "Quantificational Logic"
date: 2026-01-17T18:53:41+01:00
# weight: 1
# aliases: ["/first"]
tags: ["Logic"]
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

# Quantificational Logic

## Exercise 1 : Translating into quantificational logic I

Let the domain be “all people.” Symbolize each sentence using quantifiers. Use the following predicates:

- \( S(x) \): \( x \) is a saint.
- \( F(x, y) \): \( x \) has forgiven \( y \).
- \( C(x) \): \( x \) is in the calculus class.
- \( D(x) \): \( x \) is in the discrete math class.
- \( Sm(x, y) \): \( x \) is smarter than \( y \).
- \( L(x, y) \): \( x \) likes \( y \).
- \( P(x) \): \( x \) is a police officer.
- \( S_a(x, y) \): \( x \) saw \( y \).

1. Anyone who has forgiven at least one person is a saint.
2. Nobody in the calculus class is smarter than everybody in the discrete math class.
3. Everyone likes Mary, except Mary herself.
4. Jane saw a police officer, and Roger saw one too.
5. Jane saw a police officer, and Roger saw him too.

## Exercise 2 : Translating into quantificational logic II

Use the following predicates:

- \( B(x, y) \): \( x \) has bought \( y \).
- \( RR(x) \): \( x \) is a Rolls Royce.
- \( Cash(x) \): \( x \) was paid in cash.
- \( R(x) \): \( x \) is rich.
- \( U(x, y) \): \( x \) is the uncle of \( y \).
- \( D(x) \): \( x \) lives in the dorm.
- \( M(x) \): \( x \) has the measles.
- \( F(x, y) \): \( x \) is a friend of \( y \).
- \( Q(x) \): \( x \) will be quarantined.
- \( Test(x) \): \( x \) failed the test.
- \( A(x) \): \( x \) got an A.
- \( D_g(x) \): \( x \) got a D.
- \( T(x, y) \): \( x \) will tutor \( y \).
- \( Can(x) \): \( x \) can do it.

1. Anyone who has bought a Rolls Royce with cash must have a rich uncle.
2. If anyone in the dorm has the measles, then everyone who has a friend in the dorm will have to be quarantined.
3. If nobody failed the test, then everybody who got an A will tutor someone who got a D.
4. If anyone can do it, Jones can.
5. If Jones can do it, anyone can.

## Exercise 3 : Quantifiers with mathematical statements

Domain: real numbers. Use \( >, <, \ge, \le, = \) as needed.

1. Every number that is larger than \( x \) is larger than \( y \).
2. For every number \( a \), the equation \( ax^2 + 4x - 2 = 0 \) has at least one solution **iff** \( a \ge -2 \).
3. All solutions of the inequality \( x^3 - 3x < 3 \) are smaller than \( 10 \).
4. If there is a number \( x \) such that \( x^2 + 5x = w \) and there is a number \( y \) such that \( 4 - y^2 = w \), then \( w \) is strictly between \( -10 \) and \( 10 \).

## Exercise 4 : Translating from logic to English I

Translate each formula into an English sentence, using the given interpretation.

1. \( \forall x \,[H(x) \land \neg \exists y \, M(x, y)] \to U(x) \),  
   where \( H(x) \): “\( x \) is a man,”  
   \( M(x, y) \): “\( x \) is married to \( y \),”  
   \( U(x) \): “\( x \) is unhappy.”
2. \( \exists z \,[P(z, x) \land S(z, y) \land W(y)] \),  
   where \( P(z, x) \): “\( z \) is a parent of \( x \),”  
   \( S(z, y) \): “\( z \) and \( y \) are siblings,”  
   \( W(y) \): “\( y \) is a woman.”

## Exercise 5 : Translating from logic to English II

Domain: natural numbers.

1. \( \forall x \,[P(x) \land \neg (x = 2)] \to O(x) \),  
   where \( P(x) \): “\( x \) is a prime number,”  
   \( O(x) \): “\( x \) is odd.”
2. \( \exists x \,[P(x) \land \forall y \,(P(y) \to y \le x)] \),  
   where \( P(x) \): “\( x \) is a perfect number.”

## Exercise 6 : Scope and negation

Domain: real numbers. Explain in English what each statement says and determine its truth value.

1. \( \neg \exists x \,(x^2 + 2x + 3 = 0 \land x^2 + 2x - 3 = 0) \)
2. \( \neg [\exists x \,(x^2 + 2x + 3 = 0) \land \exists x \,(x^2 + 2x - 3 = 0)] \)
3. \( \neg \exists x \,(x^2 + 2x + 3 = 0) \land \neg \exists x \,(x^2 + 2x - 3 = 0) \)

## Exercise 7 : Quantifier order and meaning

Domain: all people. \( P(x, y) \): “\( x \) is a parent of \( y \).”

1. \( \exists x \forall y \, P(x, y) \)
2. \( \forall x \exists y \, P(x, y) \)
3. \( \neg \exists x \exists y \, P(x, y) \)
4. \( \exists x \neg \exists y \, P(x, y) \)
5. \( \exists x \exists y \neg P(x, y) \)

## Exercise 8 : Quantifiers over \(\mathbb{N}\)

Domain: natural numbers \( \mathbb{N} = \{0,1,2,\dots\} \). Determine the truth value of each statement.

1. \( \forall x \exists y \,(2x - y = 0) \)
2. \( \exists y \forall x \,(2x - y = 0) \)
3. \( \forall x \exists y \,(x - 2y = 0) \)
4. \( \forall x \,(x < 10 \to \forall y \,(y < x \to y < 9)) \)
5. \( \exists y \forall z \,(y + z = 100) \)
6. \( \forall x \exists y \,(y > x \land y + z = 100) \)

## Exercise 9 : Quantifiers over \(\mathbb{R}\)

Domain: natural numbers \( \mathbb{R} \). Determine the truth value of each statement.

1. \( \forall x \exists y \,(2x - y = 0) \)
2. \( \exists y \forall x \,(2x - y = 0) \)
3. \( \forall x \exists y \,(x - 2y = 0) \)
4. \( \forall x \,(x < 10 \to \forall y \,(y < x \to y < 9)) \)
5. \( \exists y \forall z \,(y + z = 100) \)
6. \( \forall x \exists y \,(y > x \land y + z = 100) \)

## Exercise 10 : Quantifiers over \(\mathbb{Z}\)

Domain: natural numbers \( \mathbb{Z} = \{ \dots, -2, -1,0,1,2,\dots\} \). Determine the truth value of each statement.

1. \( \forall x \exists y \,(2x - y = 0) \)
2. \( \exists y \forall x \,(2x - y = 0) \)
3. \( \forall x \exists y \,(x - 2y = 0) \)
4. \( \forall x \,(x < 10 \to \forall y \,(y < x \to y < 9)) \)
5. \( \exists y \forall z \,(y + z = 100) \)
6. \( \forall x \exists y \,(y > x \land y + z = 100) \)
