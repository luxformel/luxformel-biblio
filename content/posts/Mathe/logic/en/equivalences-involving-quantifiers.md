---
title: "Equivalences Involving Quantifiers"
date: 2026-01-17T18:23:24+01:00
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

# Equivalences Involving Quantifiers

## Exercise 1 : Negations and Positive Equivalents

Negate each of the following statements. Then rewrite the negation as an equivalent positive statement (avoiding negation symbols in front of quantifiers or compound expressions where possible).

1. Everyone who is majoring in math has a friend who needs help with his or her homework.  
   *Hint: First write it formally with quantifiers and predicates.*
2. Everyone has a roommate who dislikes everyone.  
   *Hint: Introduce predicates for “has as roommate” and “dislikes.”*
3. \( A \cup B \subseteq C \setminus D \)  
   *Hint: Rewrite the subset condition in logical form before negating.*
4. \( \exists x \, \forall y > x \; \exists z \, (z^2 + 5z = y) \)  
   *Clarification: Read as “There exists an \(x\) such that for every \(y > x\), there exists a \(z\) satisfying \(z^2 + 5z = y\).”*

## Exercise 2 : More Negations and Positive Reformulations

Negate each statement, then express the negation in a positive form.

1. There is someone in the freshman class who doesn’t have a roommate.  
   *Hint: Use predicates for “is in the freshman class” and “has as roommate.”*
2. Everyone likes someone, but no one likes everyone.  
   *Hint: This is a conjunction; negate both parts carefully.*
3. \( \forall a \in A \; \exists b \in B \; (a \in C \leftrightarrow b \in C) \)  
   *Hint: Negate the biconditional inside the quantifiers.*
4. \( \forall y > 0 \; \exists x \; (ax^2 + bx + c = y) \)  
   *Interpretation: \(a, b, c\) are fixed constants.*

## Exercise 3 : Truth Evaluation in \(\mathbb{N}\)

Determine whether each statement is true or false. The universe of discourse is the set of natural numbers \(\mathbb{N} = \{0, 1, 2, \dots\}\).

1. \( \forall x \; (x < 7 \to \exists a \, \exists b \, \exists c \, (a^2 + b^2 + c^2 = x)) \)  
   *Interpretation: Every natural number less than 7 is the sum of three squares (of natural numbers).*
2. \( \exists! \, x \; (x^2 + 3 = 4x) \)  
   *Interpretation: “There exists a unique \(x\) such that …”*
3. \( \exists! \, x \; (x^2 = 4x + 5) \)
4. \( \exists x \, \exists y \; (x^2 = 4x + 5 \land y^2 = 4y + 5) \)

## Exercise 4 : Deriving One Quantifier Negation Law from the Other

The first quantifier negation law states:
\[
\neg \exists x P(x) \; \equiv \; \forall x \neg P(x).
\]
Using only this law (and basic logical equivalences such as double negation), derive the second quantifier negation law:
\[
\neg \forall x P(x) \; \equiv \; \exists x \neg P(x).
\]

## Exercise 5 : Bounded Quantifier Negation

Prove the equivalence:
\[
\neg \exists x \in A \, P(x) \;\equiv\; \forall x \in A \, \neg P(x).
\]
*Hint: Start by recalling that “\(x \in A\)” is part of the bounded quantifier notation.*

## Exercise 6 : Existential Quantifier Distributes over Disjunction

Show that:
\[
\exists x \, (P(x) \vee Q(x)) \;\equiv\; \exists x P(x) \;\vee\; \exists x Q(x).
\]
*Hint: Use the known fact that the universal quantifier distributes over conjunction, i.e., \(\forall x (P(x) \wedge Q(x)) \equiv \forall x P(x) \wedge \forall x Q(x)\), together with quantifier negation laws.*

## Exercise 7 : Implication Inside an Existential Quantifier

Prove the equivalence:
\[
\exists x (P(x) \to Q(x)) \;\equiv\; \forall x P(x) \to \exists x Q(x).
\]
*Hint: Rewrite \(P(x) \to Q(x)\) as \(\neg P(x) \vee Q(x)\) and use previous distribution laws.*

## Exercise 8 : Universal Quantifier over Union

Show that:

\[
(\forall x \in A \; P(x)) \;\wedge\; (\forall x \in B \; P(x)) \;\equiv\; \forall x \in (A \cup B) \; P(x).
\]
*Hint: Write the bounded quantifiers in terms of unrestricted quantifiers and implications, then reason logically.*

## Exercise 9 : Universal Quantifier over Disjunction

Is the following equivalence valid?  
\[
\forall x (P(x) \vee Q(x)) \;\equiv\; \forall x P(x) \;\vee\; \forall x Q(x)?
\]
If yes, prove it; if no, provide a counterexample (by describing possible truth values of \(P(x)\) and \(Q(x)\) for different \(x\)).

## Exercise 10 : Existential Quantifier with Bounded Domains

1. Show that:
   \[
   \exists x \in A \, P(x) \;\vee\; \exists x \in B \, P(x) \;\equiv\; \exists x \in (A \cup B) \, P(x).
   \]
2. Is the following true?
   \[
   \exists x \in A \, P(x) \;\wedge\; \exists x \in B \, P(x) \;\equiv\; \exists x \in (A \cap B) \, P(x)
   \]
   Prove it or give a counterexample.

## Exercise 11 : Subset and Set Difference

Prove that the statements \(A \subseteq B\) and \(A \setminus B = \emptyset\) are equivalent:

1. Write each statement in logical symbols (using quantifiers and set membership).
2. Show the two resulting formulas are logically equivalent.

## Exercise 12 : Two Forms of Subset Relations

Prove the equivalence:

\[
C \subseteq A \cup B \;\equiv\; C \setminus A \subseteq B.
\]
*Hint: Write both sides in logical form and compare.*

## Exercise 13 : Subset Expressed with Union and Intersection

1. Show \(A \subseteq B \;\equiv\; A \cup B = B\) by:
   - Translating both sides into logical statements,
   - Using the definition of set equality (two inclusions),
2. Show \(A \subseteq B \;\equiv\; A \cap B = A\) in a similar way.

## Exercise 14 : Disjointness and Set Difference

Prove:
\[
A \cap B = \emptyset \;\equiv\; A \setminus B = A.
\]
*Hint: Translate “\(A \cap B = \emptyset\)” as “no element is in both \(A\) and \(B\).”*

## Exercise 15 : Uniqueness Quantifiers in a Relation

Let \(T(x, y)\) mean “\(x\) is a teacher of \(y\).”

1. Explain in English what each formula asserts.  
   - \(\exists! \, y \, T(x, y)\)  
   - \(\exists x \, \exists! \, y \, T(x, y)\)  
   - \(\exists! \, x \, \exists y \, T(x, y)\)  
   - \(\exists y \, \exists! \, x \, T(x, y)\)   
   - \(\exists x \, \exists y \, [T(x, y) \land \neg \exists u \, \exists v \, (T(u, v) \land (u = x \lor v = y))]\)
2. Under what real-world circumstances would each be true?
3. Are any pairs of these statements logically equivalent? Explain briefly.
