---
title: "Truth Tables and Logical Equivalences"
date: 2026-01-16T18:54:11+01:00
# weight: 1
# aliases: ["/first"]
tags: ["Logic", "Truth Tables"]
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

# Truth Tables and Logical Equivalences

## Exercise 1 : Basic Truth Tables

Construct complete truth tables for the following formulas. Show all intermediate columns.

1. $\neg P \vee Q$  
2. $(S \vee G) \wedge (\neg S \vee \neg G)$  
3. **Bonus:** $\neg(P \rightarrow Q) \wedge (P \vee Q)$

## Exercise 2 : Complex Truth Tables with Intermediate Steps

Construct truth tables for these formulas, showing columns for each subexpression:

1. $\neg [P \wedge (Q \vee \neg P)]$  
2. $(P \vee Q) \wedge (\neg P \vee R)$  
3. **Bonus:** $P \rightarrow (Q \rightarrow R)$ and $(P \rightarrow Q) \rightarrow R$ (Are they equivalent?)

## Exercise 3 : Exclusive OR

The symbol $+$ represents exclusive OR (XOR), where $P + Q$ is true when exactly one of $P$ or $Q$ is true.

1. Construct a truth table for $P + Q$.
2. Find *two different* formulas using only $\wedge$, $\vee$, and $\neg$ that are equivalent to $P + Q$. Verify each with a truth table.
3. Show that $P + Q$ is equivalent to $\neg(P \leftrightarrow Q)$.

## Exercise 4 : Functional Completeness of $\{\wedge, \neg\}$

Prove that the set $\{\wedge, \neg\}$ is functionally complete by finding equivalents:

1. Find a formula using only $\wedge$ and $\neg$ equivalent to $P \vee Q$.
2. Find a formula using only $\wedge$ and $\neg$ equivalent to $P \rightarrow Q$.
3. **Challenge:** Explain why being able to express $\vee$ and $\neg$ (or $\rightarrow$ and $\neg$) means you can express any truth function.

## Exercise 5 : NOR (Peirce Arrow / $\downarrow$)

$P \downarrow Q$ means "neither P nor Q" (NOR). Its truth table matches $\neg(P \vee Q)$.

1. Construct the truth table for $P \downarrow Q$.
2. Find a formula using only $\downarrow$ equivalent to:
   - $\neg P$
   - $P \vee Q$
   - $P \wedge Q$
   - $P \rightarrow Q$
3. **Discovery:** Show that $\downarrow$ alone is functionally complete.

## Exercise 6 : NAND (Sheffer Stroke / $\mid$)

$P \mid Q$ means "not both P and Q" (NAND). Its truth table matches $\neg(P \wedge Q)$.

1. Construct the truth table for $P \mid Q$.
2. Express using $\wedge$, $\vee$, $\neg$:
   - $P \mid Q$
   - Show $P \mid Q \equiv \neg P \vee \neg Q$
3. Find formulas using only $\mid$ equivalent to:
   - $\neg P$
   - $P \vee Q$
   - $P \wedge Q$
4. **Discovery:** Show that $\mid$ alone is functionally complete.

## Exercise 7 : Identifying Equivalent Forms

Use truth tables to determine which pairs among these formulas are equivalent:

1. $(P \wedge Q) \vee (\neg P \wedge \neg Q)$  (XNOR / biconditional)
2. $\neg P \vee Q$  (implication)
3. $(P \vee \neg Q) \wedge (Q \vee \neg P)$
4. $\neg (P \vee Q)$  (NOR)
5. $(Q \wedge P) \vee \neg P$
6. $P \rightarrow Q$
7. $\neg(P \oplus Q)$  (where $\oplus$ is XOR)

**Follow-up:** Group the equivalent formulas and name the logical operation each represents.

## Exercise 8 : Tautologies, Contradictions, Contingencies

Classify each formula as a tautology (always true), contradiction (always false), or contingency (sometimes true, sometimes false):

1. $(P \vee Q) \wedge (\neg P \wedge \neg Q)$
2. $(P \wedge Q) \vee (\neg P \vee \neg Q)$
3. $(P \vee Q) \vee (\neg P \vee \neg Q)$
4. $[P \wedge (Q \vee \neg R)] \vee (\neg P \vee R)$
5. $(P \rightarrow Q) \vee (Q \rightarrow P)$
6. $(P \wedge \neg P) \rightarrow Q$

## Exercise 9 : Verifying Fundamental Laws

Verify these logical laws using truth tables:

1. **De Morgan's Laws:**
   - $\neg(P \wedge Q) \equiv \neg P \vee \neg Q$
   - $\neg(P \vee Q) \equiv \neg P \wedge \neg Q$
2. **Distributive Laws:**
   - $P \wedge (Q \vee R) \equiv (P \wedge Q) \vee (P \wedge R)$
   - $P \vee (Q \wedge R) \equiv (P \vee Q) \wedge (P \vee R)$
3. **Implication Law:** $P \rightarrow Q \equiv \neg P \vee Q$

## Exercise 10 : Simplification Using Logical Laws

Use logical equivalences (De Morgan's, distributive, absorption, implication, double negation, etc.) to simplify:

1. $\neg (\neg P \wedge \neg Q)$
2. $(P \wedge \neg Q) \vee (\neg P \wedge Q)$
3. $(P \wedge R) \vee [\neg R \wedge (P \vee Q)]$
4. $\neg(P \rightarrow Q) \vee (P \wedge \neg R)$

## Exercise 11 : Advanced Simplification

Simplify using laws:

1. $\neg (\neg P \vee Q) \vee (P \wedge \neg R)$
2. $(P \wedge Q) \vee (\neg P \wedge Q)$
3. $(P \wedge Q) \vee (\neg P \wedge \neg Q)$
4. $(P \rightarrow Q) \wedge (P \vee Q)$

## Exercise 12 : Deriving De Morgan's Second Law

Use the first De Morgan's law ($\neg(P \wedge Q) \equiv \neg P \vee \neg Q$) and double negation to derive the second De Morgan's law: $\neg(P \vee Q) \equiv \neg P \wedge \neg Q$.

*(Hint: Apply the first law to $\neg P$ and $\neg Q$.)*


## Exercise 13 : Generalized Associativity

Associative laws allow dropping parentheses for repeated $\wedge$ or $\vee$. Prove:

1. $[P \land (Q \land R)] \land S \equiv (P \land Q) \land (R \land S)$
2. $P \lor (Q \lor (R \lor S)) \equiv ((P \lor Q) \lor R) \lor S$
3. **Discussion:** Why don't we have associative laws for mixed connectives like $\wedge$ and $\vee$?


## Exercise 14 : Truth Table Size Analysis

1. How many rows are in a truth table with $n$ propositional variables?
2. How many possible truth functions exist for $n$ variables?
3. If a formula contains 5 variables, how many columns might you need if you show every subexpression?

## Exercise 15 : Constructing Formulas from Truth Tables

Find formulas (using $\wedge$, $\vee$, $\neg$) that match these truth tables:

1. **Table A:**
   $$
   \begin{array}{cc|c}
   P & Q & ? \\
   \hline
   F & F & T \\
   F & T & F \\
   T & F & T \\
   T & T & T \\
   \end{array}
   $$

2. **Table B:**
   $$
   \begin{array}{cc|c}
   P & Q & ? \\
   \hline
   F & F & F \\
   F & T & T \\
   T & F & T \\
   T & T & F \\
   \end{array}
   $$

3. **Table C:**
   $$
   \begin{array}{ccc|c}
   P & Q & R & ? \\
   \hline
   F & F & F & F \\
   F & F & T & T \\
   F & T & F & F \\
   F & T & T & F \\
   T & F & F & T \\
   T & F & T & T \\
   T & T & F & F \\
   T & T & T & F \\
   \end{array}
   $$

## Exercise 16 : Validity and Truth Conditions

Analyze argument validity in relation to tautologies/contradictions:

1. If an argument's conclusion is a tautology, what can you conclude about the argument's validity?
2. If an argument's conclusion is a contradiction, what can you conclude?
3. If a premise is a tautology, does it affect validity? What if a premise is a contradiction?
4. **Application:** Determine if this argument is valid:  
   Premises: $P \rightarrow Q$, $\neg Q$  
   Conclusion: $\neg P \vee Q$  
   (Use truth tables to check.)

## Exercise 17 : Comprehensive Review

Combine multiple concepts:

1. Show that $\{ \rightarrow, \neg \}$ is functionally complete.
2. Prove the absorption laws using truth tables and using logical equivalences.
3. Find the simplest equivalent of $\neg(P \oplus Q) \oplus (P \rightarrow Q)$.
4. How many of the 16 possible binary truth functions can be expressed using only $\wedge$ and $\vee$ (no $\neg$)?
