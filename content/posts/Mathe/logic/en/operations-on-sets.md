---
title: "Operations on Sets"
date: 2026-01-17T18:30:38+01:00
# weight: 1
# aliases: ["/first"]
tags: ["Logic", "Sets"]
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

# Operations on Sets

## Exercise 1 : Basic set operations with numbers

Let \( A = \{1, 3, 12, 35\} \), \( B = \{3, 7, 12, 20\} \), and \( C = \{x \mid x \text{ is a prime number}\} \).  
List the elements of the following sets:

1. \( A \cap B \)
2. \( (A \cup B) \setminus C \)
3. \( A \cup (B \setminus C) \)

Then answer: Are any of the sets above disjoint from any of the others? Are any of the sets above subsets of any others?

## Exercise 2 : Basic set operations

Let \( A = \{\text{United States, Germany, China, Australia}\} \), \( B = \{\text{Germany, France, India, Brazil}\} \), and \( C = \{x \mid x \text{ is a country in Europe}\} \).  
List the elements of the following sets:

1. \( A \cup B \)
2. \( A \cap B \)
3. \( (A \cap B) \setminus C \)

Then answer: Are any of the sets above disjoint from any of the others? Are any of the sets above subsets of any others?

## Exercise 3 : Venn diagram verification

Verify that the Venn diagrams for \( (A \cup B) \setminus (A \cap B) \) and \( (A \setminus B) \cup (B \setminus A) \) are identical. Explain why they both represent the symmetric difference \( A \Delta B \).

## Exercise 4 : Venn diagram proofs of basic identities

Use Venn diagrams to verify the following identities:

1. \( A \setminus (A \cap B) = A \setminus B \)
2. \( A \cup (B \cap C) = (A \cup B) \cap (A \cup C) \)

## Exercise 5 : Logical proof of basic identities

Verify the identities using logical symbols. Write out what it means for an object \( x \) to be an element of each set, then show the logical equivalences.

1. \( A \setminus (A \cap B) = A \setminus B \)
2. \( A \cup (B \cap C) = (A \cup B) \cap (A \cup C) \)

## Exercise 6 : Venn diagram proofs of set differences

Use Venn diagrams to verify the following identities:

1. \( (A \cup B) \setminus C = (A \setminus C) \cup (B \setminus C) \)
2. \( A \cup (B \setminus C) = (A \cup B) \setminus (C \setminus A) \)

## Exercise 7 : Logical proof of set difference identities

Verify the identities using logical symbols. Write out what it means for an object \( x \) to be an element of each set, then show the logical equivalences.

1. \( (A \cup B) \setminus C = (A \setminus C) \cup (B \setminus C) \)
2. \( A \cup (B \setminus C) = (A \cup B) \setminus (C \setminus A) \)

## Exercise 8 : Exploring set difference identities

Use any method you wish to verify the following identities:

1. \( (A \setminus B) \setminus C = A \setminus (B \cup C) \)
2. \( A \setminus (B \setminus C) = (A \setminus B) \cup (A \cap C) \)
3. \( (A \setminus B) \cup (A \cap C) = A \setminus (B \setminus C) \)
4. \( (A \setminus B) \cap (A \setminus C) = A \setminus (B \cup C) \)
5. \( A \setminus (B \cup C) = (A \setminus B) \cap (A \setminus C) \)

## Exercise 9 : Properties of \( (A \cup B) \setminus B \)

It was shown that \( (A \cup B) \setminus B \subseteq A \) for any sets \( A \) and \( B \).

1. Give an example of two sets \( A \) and \( B \) for which \( (A \cup B) \setminus B \neq A \).
2. Prove that for all sets \( A \) and \( B \), \( (A \cup B) \setminus B = A \setminus B \).
3. Is \( (A \setminus B) \cup B \) always equal to \( A \setminus B \), \( A \cup B \), or neither? Investigate.

## Exercise 10 : When does \( (A \setminus B) \cup B = A \) hold?

Suppose \( A \) and \( B \) are sets.

1. Is it necessarily true that \( (A \setminus B) \cup B = A \)? Prove or provide a counterexample.
2. Is one of these sets necessarily a subset of the other? Prove your claim.

## Exercise 11 : Venn diagrams for four sets

It is claimed that you cannot make a Venn diagram for four sets using overlapping circles.

1. What is wrong with a diagram using four overlapping circles? Explain why such a diagram cannot represent all possible intersections.
2. Can you make a valid Venn diagram for four sets using shapes other than circles? Describe or sketch an approach.

## Exercise 12 : Comparing \( (A \cup B) \setminus C \) and \( A \cup (B \setminus C) \)

1. Make Venn diagrams for \( (A \cup B) \setminus C \) and \( A \cup (B \setminus C) \). What can you conclude about whether one of these sets is necessarily a subset of the other?
2. Give an example of sets \( A \), \( B \), and \( C \) for which \( (A \cup B) \setminus C \neq A \cup (B \setminus C) \).

## Exercise 13 : Associativity of symmetric difference

Use Venn diagrams to show that the associative law holds for symmetric difference; that is, for any sets \( A \), \( B \), and \( C \), \( A \Delta (B \Delta C) = (A \Delta B) \Delta C \).

## Exercise 14 : Symmetric difference identities I

Verify the following identities:

1. \( (A \Delta B) \cup C = (A \cup C) \Delta (B \setminus C) \)
2. \( (A \Delta B) \cap C = (A \cap C) \Delta (B \cap C) \)
3. \( (A \Delta B) \setminus C = (A \setminus C) \Delta (B \setminus C) \)

## Exercise 15 : Symmetric difference identities II

Verify the following identities:

1. \( (A \cup B) \Delta C = (A \Delta C) \Delta (B \setminus A) \)
2. \( (A \cap B) \Delta C = (A \Delta C) \Delta (A \setminus B) \)
3. \( (A \setminus B) \Delta C = (A \Delta C) \Delta (A \cap B) \)

## Exercise 16 : Completing symmetric difference identities

Fill in the blanks to make true identities:

1. \( (A \Delta B) \cap C = (C \setminus A) \Delta \underline{\hspace{1cm}} \)
2. \( (B \setminus A) \Delta C = (A \Delta C) \Delta \underline{\hspace{1cm}} \)

## Exercise 17 : Subset relationships

Determine whether each statement is true or false. Prove or give a counterexample.

1. \( \mathcal{F} \subseteq \mathcal{P}(A) \)
2. \( A \subseteq \{2n+1 \mid n \in \mathbb{N}\} \)
3. \( \{n^2 + n \mid n \in \mathbb{N}\} \subseteq \{2n \mid n \in \mathbb{N}\} \)
4. \( \mathcal{P}(\bigcup_{i \in I} A_i) \not\subseteq \bigcup_{i \in I} \mathcal{P}(A_i) \)

## Exercise 18 : Translating set-builder notation

Rewrite in simpler set notation if possible and determine truth:

1. \( x \in \mathcal{F} \cup \mathcal{G} \)
2. \( \{x \in B \mid x \notin C\} \in \mathcal{P}(A) \)
3. \( x \in \bigcap_{i \in I} (A_i \cup B_i) \)
4. \( x \in (\bigcap_{i \in I} A_i) \cup (\bigcap_{i \in I} B_i) \)

## Exercise 19 : Power set of a singleton

We know \( \mathcal{P}(\emptyset) = \{\emptyset\} \), and \( \{\emptyset\} \neq \emptyset \).

1. Find \( \mathcal{P}(\{\emptyset\}) \).
2. Find \( \mathcal{P}(\mathcal{P}(\emptyset)) \).
3. How many elements does \( \mathcal{P}^n(\emptyset) \) have, where \( \mathcal{P}^n \) means applying \( \mathcal{P} \) \( n \) times?

## Exercise 20 : Intersection and union of a family

Let \( \mathcal{F} = \{\{\text{red, green, blue}\}, \{\text{orange, red, blue}\}, \{\text{purple, red, green, blue}\}\} \).

1. Find \( \bigcap \mathcal{F} \) and \( \bigcup \mathcal{F} \).
2. If we add \( \{\text{yellow, purple}\} \) to \( \mathcal{F} \), how do the answers change?

## Exercise 21 : Indexed family with numerical sets

Let \( I = \{2, 3, 4, 5\} \), and for each \( i \in I \) let \( A_i = \{i+1, i-1\} \).

1. List all \( A_i \).
2. Find \( \bigcap_{i \in I} A_i \) and \( \bigcup_{i \in I} A_i \).
3. What is \( \bigcap_{i \in I} A_i \) if \( I = \mathbb{N} \)?

## Exercise 22 : Historical indexed family

Let \( P = \{\text{Bach, Napoleon, Goethe, Hume, Newton, Washington}\} \) and \( Y = \{1750, 1751, \dots, 1759\} \). For \( y \in Y \), let \( A_y = \{p \in P \mid p \text{ was alive in year } y\} \).

1. Find \( \bigcup_{y \in Y} A_y \) and \( \bigcap_{y \in Y} A_y \).
2. What do these represent in historical terms?

## Exercise 23 : Comparing \( \bigcap_{i \in I} (A_i \cup B_i) \)

Let \( I = \{2,3\} \), \( A_i = \{i, 2i\} \), \( B_i = \{i, i+1\} \).

1. List \( A_i \) and \( B_i \) for \( i \in I \).
2. Find \( \bigcap_{i \in I} (A_i \cup B_i) \) and \( (\bigcap_{i \in I} A_i) \cup (\bigcap_{i \in I} B_i) \). Are they equal?
3. Based on your answer, are the logical forms \( x \in \bigcap_{i \in I} (A_i \cup B_i) \) and \( x \in (\bigcap_{i \in I} A_i) \cup (\bigcap_{i \in I} B_i) \) equivalent?

## Exercise 24 : Distributive laws for indexed families

1. Analyze the logical forms of:
   \( x \in \bigcup_{i \in I} (A_i \setminus B_i) \)
   \( x \in (\bigcup_{i \in I} A_i) \setminus (\bigcup_{i \in I} B_i) \)
   \( x \in (\bigcup_{i \in I} A_i) \setminus (\bigcap_{i \in I} B_i) \)
   Which pairs are equivalent?
2. Let \( I = \{2,3\} \), \( A_i = \{i, 2i\} \), \( B_i = \{i, i+1\} \) compute the three sets above. Does this match your logical analysis?

## Exercise 25 : Counterexample for union distributing over intersection

Give an example of an index set \( I \) and indexed families of sets \( \{A_i \mid i \in I\} \) and \( \{B_i \mid i \in I\} \) such that \( \bigcup_{i \in I} (A_i \cap B_i) \neq (\bigcup_{i \in I} A_i) \cap (\bigcup_{i \in I} B_i) \).

## Exercise 26 : Power set and intersection

Show that for any sets \( A \) and \( B \), the statements \( x \in \mathcal{P}(A \cap B) \) and \( x \in \mathcal{P}(A) \cap \mathcal{P}(B) \) are equivalent.

## Exercise 27 : Power set and union

Give examples of sets \( A \) and \( B \) for which \( \mathcal{P}(A \cup B) \neq \mathcal{P}(A) \cup \mathcal{P}(B) \).

## Exercise 28 : Generalized distributive and De Morgan laws

Verify the following identities by writing out what it means for an object \( x \) to be an element of each set and then using logical equivalences:

1. \( \bigcup_{i \in I} (A_i \cup B_i) = (\bigcup_{i \in I} A_i) \cup (\bigcup_{i \in I} B_i) \)
2. \( \bigcap_{i \in I} (A_i \cap B_i) = (\bigcap_{i \in I} A_i) \cap (\bigcap_{i \in I} B_i) \)
3. \( \bigcap_{i \in I} (A_i \setminus B_i) = (\bigcap_{i \in I} A_i) \setminus (\bigcup_{i \in I} B_i) \)

## Exercise 29 : Double-indexed families

Use the following definitions: \( I = \{1, 2\} \), \( J = \{3, 4\} \). For each \( i \in I \) and \( j \in J \), let \( A_{i,j} = \{i, j, i+j\} \).

1. For each \( j \in J \), let \( B_j = \bigcup_{i \in I} A_{i,j} \). Find \( B_3 \) and \( B_4 \).
2. Find \( \bigcap_{j \in J} B_j \).
3. Find \( \bigcup_{i \in I} (\bigcap_{j \in J} A_{i,j}) \).
4. Analyze the logical forms of \( x \in \bigcap_{j \in J} (\bigcup_{i \in I} A_{i,j}) \) and \( x \in \bigcup_{i \in I} (\bigcap_{j \in J} A_{i,j}) \). Are they equivalent?

## Exercise 30 : Empty family of sets

1. Show that if \( \mathcal{F} = \emptyset \), then the statement \( x \in \bigcup \mathcal{F} \) will be false no matter what \( x \) is.
2. Show that if \( \mathcal{F} = \emptyset \), then the statement \( x \in \bigcap \mathcal{F} \) will be true for all \( x \) in the universe of discourse. Discuss why mathematicians often avoid the notation \( \bigcap \emptyset \).

## Exercise 31 : Russell’s paradox

Suppose \( U \) were the set of all sets. Let \( R = \{A \in U \mid A \notin A\} \).

1. Show that applying this definition to \( R \) itself leads to a contradiction (Russell's paradox).
2. What does this paradox tell us about the concept of a "set of all sets"?
