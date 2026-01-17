---
title: "Conditional and Biconditional Connectives"
date: 2026-01-16T19:01:09+01:00
# weight: 1
# aliases: ["/first"]
tags: ["Logic", "Conditionals"]
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

# Conditional and Biconditional Connectives  

## Exercise 1 : Translating English to Propositional Logic  

Express each statement in symbolic logic, defining your atomic propositions clearly.

1. If this gas either has an unpleasant smell or is not explosive, then it isn't hydrogen.  
   *Let \( S \): The gas has an unpleasant smell, \( E \): The gas is explosive, \( H \): The gas is hydrogen.*  
2. Having both a fever and a headache is a **sufficient condition** for George to go to the doctor.  
   *Let \( F \): George has a fever, \( H \): George has a headache, \( D \): George goes to the doctor.*  
3. **Both** having a fever and having a headache are sufficient conditions for George to go to the doctor.  
   *(Note the subtle difference from #2. Write two separate conditional statements.)*  
4. If \( x \neq 2 \), then a necessary condition for \( x \) to be prime is that \( x \) be odd.  
   *Let \( P_x \): \( x \) is prime, \( O_x \): \( x \) is odd. Assume universe of integers > 1.*  

## Exercise 2 : “Only if,” “Unless,” and Necessary Conditions
Translate into symbolic logic.

1. Mary will sell her house only if she can get a good price and find a nice apartment.  
   Let \( S \): Mary sells her house, \( P \): Mary gets a good price, \( A \): Mary finds a nice apartment.
2. Having both a good credit history and an adequate down payment is a **necessary condition** for getting a mortgage.  
3. John will drop out of school, unless someone stops him.  
4. If \( x \) is divisible by either \( 4 \) or \( 6 \), then it isn't prime.  

## Exercise 3 : Equivalences and Variations of a Given Statement 

Given statement: \( R \to (W \land \neg S) \). Where \( R \): It is raining, \( W \): It is windy, \( S \): The sun is shining.  

For each statement below:  

- Translate to symbolic logic.  
- Determine if it is equivalent to \( R \to (W \land \neg S) \), to its converse \( (W \land \neg S) \to R \), or to neither.

1. It is windy and not sunny only if it is raining.  
2. Rain is a sufficient condition for wind with no sunshine.  
3. Rain is a necessary condition for wind with no sunshine.  
4. It's not raining, if either the sun is shining or it's not windy.  
5. Wind is a necessary condition for it to be rainy, and so is a lack of sunshine.  
6. Either it is windy only if it is raining, or it is not sunny only if it is raining.

## Exercise 4 : Truth Tables and Validity of Arguments I  

Use truth tables to determine whether each argument is valid.

1. Either sales or expenses will go up. If sales go up, then the boss will be happy. Therefore, sales and expenses will not both go up.  
2. If the tax rate and the unemployment rate both go up, then there will be a recession. If the GDP goes up, then there will not be a recession. The GDP and taxes are both going up. Therefore, the unemployment rate is not going up.  
3. The warning light will come on if and only if the pressure is too high and the relief valve is clogged. The relief valve is clogged. Therefore, the warning light will come on if and only if the pressure is too high.  

## Exercise 5 : Truth Tables and Validity of Arguments II 

Determine validity using truth tables.

1. If Jones is convicted then he will go to prison. Jones will be convicted only if Smith testifies against him. Therefore, Jones won't go to prison unless Smith testifies against him.  
   *(Translate “unless” carefully.)*
2. Either the Democrats or the Republicans will have a majority in the Senate, but not both. Having a Democratic majority is a necessary condition for the bill to pass. Therefore, if the Republicans have a majority in the Senate then the bill won't pass.  

## Exercise 6 : Equivalences with Biconditionals and Conditionals  

Prove using truth tables or logical equivalences.

1. Show \( P \leftrightarrow Q \equiv (P \land Q) \lor (\neg P \land \neg Q) \).  
2. Show \( (P \to Q) \lor (P \to R) \equiv P \to (Q \lor R) \).  
3. **Additional:** Is \( (P \to Q) \land (P \to R) \) equivalent to \( P \to (Q \land R) \)? Prove your answer.

## Exercise 7 : Combining Antecedents or Consequents
Prove the following equivalences.

1. Show \( (P \to R) \land (Q \to R) \equiv (P \lor Q) \to R \).  
2. Formulate and verify a similar equivalence involving \( (P \to R) \lor (Q \to R) \).  
   *(Hint: Compare with \( (P \land Q) \to R \).)*

## Exercise 8 : Tautologies and Chain of Conditionals

1. Show that \( (P \to Q) \land (Q \to R) \) is **not** equivalent to \( (P \lor Q) \to R \).  
2. Show that \( (P \to Q) \lor (Q \to R) \) is a tautology.  

## Exercise 9 : Expressiveness of Connectives

Find formulas using only \( \neg \) and \( \to \) equivalent to:

1. \( P \land Q \)  
2. \( P \lor Q \)  
3. \( P \leftrightarrow Q \)  

## Exercise 10 : More on Biconditional Reductions  

Prove the following equivalences.

1. Show \( (P \lor Q) \leftrightarrow Q \equiv P \to Q \).  
2. Show \( (P \land Q) \leftrightarrow Q \equiv Q \to P \).  
3. **Explore:** Is \( (P \to Q) \leftrightarrow Q \) equivalent to \( P \lor Q \)? Check.

## Exercise 11 : Interdefinability of Connectives  

Show each of the following:

1. \( P \to Q \equiv \neg P \lor Q \)  
2. \( P \land Q \equiv \neg (P \to \neg Q) \)  
3. \( P \lor Q \equiv \neg P \to Q \)  
4. \( P \leftrightarrow Q \equiv (P \to Q) \land (Q \to P) \)  

## Exercise 12 : Comparing Conditional Forms

Which of these formulas are equivalent? Use truth tables or laws of logic.

1. \( P \to (Q \to R) \)  
2. \( Q \to (P \to R) \)  
3. \( (P \to Q) \land (P \to R) \)  
4. \( (P \land Q) \to R \)  
5. \( P \to (Q \land R) \)  
6. **Add:** \( (P \lor Q) \to R \)  

## Exercise 13 : Sufficient vs. Necessary in Mathematical Statements  

Translate each mathematical statement, identifying sufficient and necessary conditions.

1. For an integer \( n > 1 \) to be prime, it is sufficient that \( n \) not be divisible by any prime \( \leq \sqrt{n} \).  
2. A function \( f \) is continuous at \( a \) only if \( \lim_{x \to a} f(x) \) exists.  
3. A square matrix is invertible if and only if its determinant is nonzero.  
4. If a sequence converges, then it is bounded.

## Exercise 14 : Validity and Common Fallacies

Use truth tables to check if these common argument forms are valid.

1. Affirming the consequent: \( P \to Q, Q \vDash P \)  
2. Denying the antecedent: \( P \to Q, \neg P \vDash \neg Q \)  
3. Hypothetical syllogism: \( P \to Q, Q \to R \vDash P \to R \)  
4. Constructive dilemma: \( (P \to Q) \land (R \to S), P \lor R \vDash Q \lor S \)  


## Exercise 15 : Circuit and Programming Applications

Represent the following as logical expressions.

1. A light is on if (\( switch\ A \) is ON AND \( switch\ B \) is ON) OR (\( switch\ C \) is ON) but NOT if the override switch \( D \) is ON.  
2. A program loop continues while \( (x > 0 \land \text{not error}) \lor \text{debugMode} \).  
3. Express XOR (exclusive OR) using only \( \land, \lor, \neg \), then using only \( \to \) and \( \neg \).  

## Exercise 16 : Challenge – Logical Simplification

Simplify the following expressions as much as possible.

1. \( (P \to Q) \to P \)  
2. \( (P \to (Q \to R)) \to ((P \to Q) \to (P \to R)) \)  
3. \( \big( (P \land Q) \to R \big) \leftrightarrow \big( P \to (Q \to R) \big) \)  
