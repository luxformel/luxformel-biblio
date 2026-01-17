---
title: "Deductive Reasoning and Logical Connectives"
date: 2026-01-17T18:20:19+01:00
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

# Deductive Reasoning and Logical Connectives

## Exercise 1 : Disjunction, Conjunction, and Negation

Analyze the logical forms of the following statements. Define your atomic components clearly.

1. We’ll have either a reading assignment or homework problems, but we won’t have both homework problems and a test.  
   *(Identify three atomic statements and express the sentence using ∨, ∧, and ¬.)*
2. You won’t go skiing, or you will and there won’t be any snow.  
   *(Pay attention to how “or” and “and” group together; use parentheses to show the structure.)*
3. \(\sqrt{7} \leq 2\).  
   *(Treat this as a single mathematical assertion. Could you also think of it as a negation of \(\sqrt{7} > 2\)?)*

## Exercise 2 : Complex Combinations

Analyze the logical forms of the following statements. Clearly label each atomic component.

1. Either John and Bill are both telling the truth, or neither of them is.  
   *(Note: “neither of them is” means both are not telling the truth.)*
2. I’ll have either fish or chicken, but I won’t have both fish and mashed potatoes.  
   *(Three different atomic statements are involved.)*
3. 3 is a common divisor of 6, 9, and 15.  
   *(This can be expressed as a conjunction of three separate divisibility statements.)*

## Exercise 3 : “Both not,” “Not both,” “Neither,” and “Either not”

Let \(A\) = “Alice is in the room” and \(B\) = “Bob is in the room.” Translate each sentence into a formal logical expression using \(A\), \(B\), \(\wedge\), \(\vee\), and \(\neg\). Explain the difference in meaning between them.

1. Alice and Bob are not both in the room.
2. Alice and Bob are both not in the room.
3. Either Alice or Bob is not in the room.
4. Neither Alice nor Bob is in the room.

## Exercise 4 : Nested Conjunctions and Disjunctions

Let \(R\) = “Ralph is tall,” \(E\) = “Ed is tall,” \(H_r\) = “Ralph is handsome,” \(H_e\) = “Ed is handsome.” Translate the following statements into logical notation, paying careful attention to how the grouping of “either…or” and “both…and” changes the meaning.

1. Either both Ralph and Ed are tall, or both of them are handsome.
2. Both Ralph and Ed are either tall or handsome.
3. Both Ralph and Ed are neither tall nor handsome.
4. Neither Ralph nor Ed is both tall and handsome.

## Exercise 5 : Well‑Formed Formulas (WFFs)

Recall the rules for constructing well‑formed formulas in propositional logic: atomic statements are WFFs; if \(P\) and \(Q\) are WFFs, then \((\neg P)\), \((P \wedge Q)\), \((P \vee Q)\), \((P \to Q)\), and \((P \leftrightarrow Q)\) are WFFs. Determine which of the following expressions are well‑formed formulas. For those that are not, explain why they violate the syntax rules.

1. \(\neg(\neg P \vee \neg R)\)
2. \(\neg(P, Q, \wedge R)\)
3. \(P \wedge \neg P\)
4. \((P \wedge Q)(P \vee R)\)

## Exercise 6 : From Formulas to English I

Let \(P\) = “I will buy the pants” and \(S\) = “I will buy the shirt.” Translate each of the following formulas into a clear, idiomatic English sentence. Then explain, in words, the circumstances under which each statement would be true.

1. \(\neg(P \wedge \neg S)\)
2. \(\neg P \wedge \neg S\)
3. \(\neg P \vee \neg S\)

## Exercise 7 : From Formulas to English II

Let \(S\) = “Steve is happy” and \(G\) = “George is happy.” Translate each formula into an English sentence. Then, using truth tables or logical equivalences, determine whether any of these formulas are logically equivalent to one another.

1. \((S \vee G) \wedge (\neg S \vee \neg G)\)
2. \([S \vee (G \wedge \neg S)] \vee \neg G\)
3. \(S \vee [G \wedge (\neg S \vee \neg G)]\)

## Exercise 8 : Truth Conditions and Logical Equivalence

Let \(T\) = “Taxes will go up” and \(D\) = “The deficit will go up.” For each formula, do the following:

- Translate it into a natural English sentence.  
- Construct its truth table.  
- Describe in words the real‑world situation(s) in which the statement would be true.

1. \(T \vee D\)
2. \(\neg(T \wedge D) \wedge (\neg T \wedge \neg D)\)
3. \((T \wedge \neg D) \vee (D \wedge \neg T)\)

## Exercise 9 : Identifying Premises, Conclusions, and Validity

For each argument below:  

- Identify the premises and the conclusion.  
- Translate the premises and conclusion into symbolic form.  
- Using your intuition, decide whether the reasoning is **valid** (i.e., if the premises are true, must the conclusion be true?).  
- Briefly explain your reasoning.

1. Jane and Pete won’t both win the math prize. Pete will win either the math prize or the chemistry prize. Therefore, Pete will win the chemistry prize.
2. The main course will be either beef or fish. The vegetable will be either peas or corn. We will not have both fish as a main course and corn as a vegetable. Therefore, we will not have both beef as a main course and peas as a vegetable.
3. Either John or Bill is telling the truth. Either Sam or Bill is lying. Therefore, either John is telling the truth or Sam is lying.
4. Either sales will go up and the boss will be happy, or expenses will go up. Therefore, sales and expenses will not both go up.
