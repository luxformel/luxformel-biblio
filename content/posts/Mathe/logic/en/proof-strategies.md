---
title: "Proof Strategies"
date: 2026-01-17T18:50:40+01:00
# weight: 1
# aliases: ["/first"]
tags: ["Logic", "Proofs"]
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

# Proof Strategies

## Exercise 1 : Identifying Hypotheses and Conclusions

**Theorem**  
Suppose \(n\) is an integer larger than 1 and \(n\) is not prime. Then \(2^n - 1\) is not prime.

1. Identify the hypothesis and conclusion of the theorem. Are the hypotheses true when \(n = 6\)? If so, what does the theorem conclude for \(n=6\)? Check whether this conclusion is correct.
2. What does the theorem conclude when \(n = 15\)? Verify this conclusion directly.
3. What does the theorem conclude when \(n = 11\)? Does the theorem apply in this case? Why or why not?

## Exercise 2 : Understanding a Quadratic Theorem

**Theorem**  
Suppose that \(b^2 > 4ac\). Then the quadratic equation \(ax^2 + bx + c = 0\) has exactly two real solutions.

1. Identify the hypothesis and conclusion of the theorem.
2. In giving an instance of the theorem, why do you specify values for \(a\), \(b\), and \(c\), but not for \(x\)?
3. Let \(a = 2\), \(b = -5\), \(c = 3\).  
   - Does the hypothesis hold?  
   - What does the theorem conclude?  
   - Solve \(2x^2 - 5x + 3 = 0\) directly to verify.
4. Let \(a = 2\), \(b = 4\), \(c = 3\).  
   - Does the hypothesis hold?  
   - What can you conclude from the theorem?

## Exercise 3 : Finding a Counterexample

**Incorrect Theorem**  
Suppose \(n\) is a natural number larger than 2, and \(n\) is not prime. Then \(2n + 13\) is not prime.

1. Identify the hypothesis and conclusion.
2. Show the theorem is false by finding a counterexample.

## Exercise 4 : Completing a Direct Proof

Complete the following proof of the theorem:  
**Theorem**  
If \(0 < a < b\), then \(a^2 < b^2\).

**Proof**  
Suppose \(0 < a < b\). Then \(b - a > 0\) and \(b + a > 0\).  
Multiplying the inequalities, \((b - a)(b + a) > 0 \cdot (b + a)\) ⇒ \(b^2 - a^2 > 0\).  
Therefore, \(a^2 < b^2\). ∎

1. Justify the step that \(b + a > 0\).
2. Explain why multiplying the inequalities is valid here.
3. Rewrite the proof concisely in your own words.

## Exercise 5 : Proving an Inequality

Suppose \(a\) and \(b\) are real numbers. Prove that if \(a < b < 0\), then \(a^2 > b^2\).

## Exercise 6 : Reciprocal Inequality

Suppose \(a\) and \(b\) are real numbers. Prove that if \(0 < a < b\), then \(\frac{1}{b} < \frac{1}{a}\).

## Exercise 7 : Inequality Implication

Suppose \(a\) is a real number. Prove that if \(a^3 > a\), then \(a^5 > a\).  
*Hint:* One approach: \(a^5 - a = (a^3 - a)(a^2 + 1)\).

## Exercise 8 : Set Logic Proof

Suppose \(A \setminus B \subseteq C \cap D\) and \(x \in A\). Prove that if \(x \notin D\), then \(x \in B\).

## Exercise 9 : Nested Conditional Proof

Suppose \(A \cap B \subseteq C \setminus D\). Prove that if \(x \in A\), then if \(x \in D\), then \(x \notin B\).

## Exercise 10 : Average Inequality

Suppose \(a\) and \(b\) are real numbers. Prove that if \(a < b\), then \(\frac{a + b}{2} < b\).

## Exercise 11 : Rational Equation Constraint

Suppose \(x\) is a real number and \(x \neq 0\). Prove that if  
\[
\frac{\sqrt[3]{x + 5}}{x^2 + 6} = \frac{1}{x},
\]  
then \(x \neq 8\).

## Exercise 12 : Inequality Chain Proof

Suppose \(a, b, c, d\) are real numbers, \(0 < a < b\), and \(d > 0\). Prove that if \(ac \geq bd\), then \(c > d\).

## Exercise 13 : Linear Inequality Implication

Suppose \(x\) and \(y\) are real numbers, and \(3x + 2y \leq 5\). Prove that if \(x > 1\), then \(y < 1\).

## Exercise 14 : System of Equations Conclusion

Suppose that \(x\) and \(y\) are real numbers. Prove that if  
\(x^2 + y = -3\) and \(2x - y = 2\),  
then \(x = -1\).

## Exercise 15 : Diagnosing and Correcting a Proof

**Theorem**  
Suppose \(x\) is a real number and \(x \neq 4\). If \(\frac{2x - 5}{x - 4} = 3\), then \(x = 7\).

1. The following proof is incorrect. Why?  
   **Proof** Suppose \(x = 7\). Then \(\frac{2(7)-5}{7-4} = \frac{9}{3} = 3\). Therefore if \(\frac{2x-5}{x-4} = 3\), then \(x = 7\).  
2. Provide a correct proof of the theorem.

## Exercise 16 : Another Incorrect Theorem

**Incorrect Theorem**  
Suppose \(x\) and \(y\) are real numbers and \(x \neq 3\). If \(x^2 y = 9y\), then \(y = 0\).

1. Why is the following proof invalid?  
   **Proof** Suppose \(x^2 y = 9y\). Then \((x^2 - 9)y = 0\). Since \(x \neq 3\), \(x^2 \neq 9\), so \(x^2 - 9 \neq 0\). Dividing both sides by \(x^2 - 9\) gives \(y = 0\).  
2. Find a counterexample to the theorem.
