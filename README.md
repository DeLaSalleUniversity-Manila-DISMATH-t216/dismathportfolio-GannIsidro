# dismathportfolio-GannIsidro
dismathportfolio-GannIsidro created by Classroom for GitHub

#Week 1

#####Logical Operations
| Logical Symbol  |  Logical Connective | Usage |
| :-----: |:-------:|:-----:|
| ¬ |Negation | not |
| ∧ | Conjunction | and |
| ∨ | Disjunction | or |
| ⊕ | Exclusive disjunction | xor | 
| → | Conditional | if, then & only if|
| ⇔| Biconditional | iff |

#####Truth Table

- Truth table using T (True) and F (False)

| p | q | p ∧ q | p v q | p ⊕ q | p → q | p ↔ q |    
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| F | F | F | F | F | T | T |
| F | T | F | T | T | T | F |
| T | F | F | T | T | F | F |
| T | T | T | T | F | T | T |

#Week 2

#####Logical Equivalence

| Logical Equivalence  |  |  |
| :-----: |:-------:|:-----:|
| Commutative | p ∧ q ⇐⇒ q ∧ p |  p ∨ q ⇐⇒ q ∨ p |
| Associative | (p ∧ q) ∧ r ⇐⇒ p ∧ (q ∧ r) | (p ∨ q) ∨ r ⇐⇒ p ∨ (q ∨ r) |
| Distributive | p ∧ (q ∨ r) ⇐⇒ (p ∧ q) ∨ (p ∧ r) | p ∨ (q ∧ r) ⇐⇒ (p ∨ q) ∧ (p ∨ r) |
| Identity | p ∧ T ⇐⇒ p | p ∨ F ⇐⇒ p |
| Negation | p∨ ∼ p ⇐⇒ T | p∧ ∼ p ⇐⇒ F |
| Double Negative | ∼ (∼ p) ⇐⇒ p |
| Idempotent | p ∧ p ⇐⇒ p | p ∨ p ⇐⇒ p |
| Universal Bound | p ∨ T ⇐⇒ T | p ∧ F ⇐⇒ F |
| De Morgan’s | ∼ (p ∧ q) ⇐⇒ (∼ p) ∨ (∼ q)  | ∼ (p ∨ q) ⇐⇒ (∼ p) ∧ (∼ q) |
| Absorption | p ∨ (p ∧ q) ⇐⇒ p | p ∧ (p ∨ q) ⇐⇒ p |
| Conditional | (p ⇒ q) ⇐⇒ (∼ p ∨ q) | ∼ (p ⇒ q) ⇐⇒ (p∧ ∼ q) |

#Week 3

- So far, there are 3 tools in proving 
  - truth table
  - logical equivalences
  - quantifiers
- In this week's lesson, we were taught about another tool, which is the rules of inference.

|   **Rule of Inference**  |            **Tautology**           |          **Name**          |
|:--------------------|:------------------------------:|:----------------------:|
|       p<br>p→q<br>∴ q      |        (p ∧ (p → q)) → q       |      Modus Ponens      |
|     ¬q<br>p→q<br>∴ ¬p     |       (¬q ∧ (p → q)) → ¬p      |      Modus Tollens     |
|     p→q<br>q→r<br>∴ p→r    |  ((p → q) ∧ (q → r)) → (p → r) | Hypothetical Syllogism |
|      p∨q<br>¬p<br>∴ q      |       ((p ∨ q) ∧ ¬p) → q       |  Disjunctive Syllogism |
|       p<br>∴p ∨ q       |           p → (p ∨ q)          |        Addition        |
|       p ∧ q<br>∴ p       |           (p ∧ q) → p          |      Simplification      |
|      p<br>q<br>∴ p ∧ q     |      ((p) ∧ (q)) → (p ∧ q)     |       Conjunction      |
| p ∨ q<br>¬p ∨ r<br>∴ q ∨ r | ((p ∨ q) ∧ (¬p ∨ r)) → (q ∨ r) |       Resolution       | 

- In our assignment, using the rules of inference, we conluded that superman does not exist.

#Week 4

- Proof by Contraposition: 
  - Steps in constructing Contrapositive Proof:
    1. Assume that ¬Q is true.
    2. Show that ¬P is also true.
- Vacuous & Trivial Proofs: 
  - Vacuous Proof: It is a proof that P → Q is true based on the fact that P is false.
    - ¬P → (P → Q)
  - Trivial Proof: It is a proof that P → Q is true based on the fact that Q is true.
    - Q → (P → Q)
- Proof by Contradiction:
  - Steps in constructing Proof by Contradiction:
    1. Assume P is true.
    2. Assume ¬Q is true.
    3. Demonstrate a contradiction.

#Week 5

- I learned Summation, Recursive/Induction definition, Recursive algorithm and Program correctness.

- I learned the importance of Geometric Series and Power Series.

- I also learned Sets, Set Identities and the Venn Diagram.

- I also knew the function of Hoare Triple in which there are 3 main parts. Theinitial assertion then the program segment and lastly the final assertion.

#Week 6

- I learned Counterexample where in it is a proof that allows us to prove that an argument is not true by providing an example where it does not hold.

- Mathematical Induction was introduced as well.

#Week 7 (No classes)

#Week 8

- I learned about sets and its definition

- Functions are also introduced in this week

- I also knew the meaning of Domain, Co-domain and Range

#Week 9
-I learned Introduction to Algorithm. Finding the maximum and minimum, Pseudocodes, Precondition and Postcondition, Linear Search and Binary Search Algorithms.

-I also learned Growth of Functions often described using Big-O Notation  ,Big-Omega and Big-Theta ,Notation Algorithm ,Time Complexity.

|         Complexity        |                           Termninology                         |	
|:-------------------:|:--------------------------------------------------------------:|
|    Big Theta of 1      |                     Constant Complexity                          |
|    Big Theta of log(n)   |                   Logarithmic Complexity                     |
|    Big Theta of n      |                     Linear Complexity                             |
|    Big Theta of n log(n) |                   Linearithmic Complexity                             |
|    Big Theta of 1       |                    Polynomial Complexity                      |
|    Big Theta of b^n     |                    Exponential Complexity                         |
|    Big Theta of n!       |                   Factorial Complexity                           |


#Week 10

-I learned Binary Search and Linear Search

-I learned Bubble Sort ,Insertion Sort and Greedy Algorithm.

#Week 11 (No classes)

#Week 12

-We discussed about Graph Theory.

-I learned graphs, degree, vertex, subgraph, Euler Circuit, Euler Path, Handshaking Theorem, Matrices of Graphs, Hamilton Circuit, Hamilton Path and Kuratowski's Theorem.

-Euler's Formula : r = e - v + 2

#Week 13

- I learned Graph Coloring and Trees, which is a graph with no simple circuits.
