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

- [2/6] **Proof by Contraposition** (¬Q → ¬P): 
  - Steps in constructing Contrapositive Proof:
    1. Assume that ¬Q is true.
    2. Show that ¬P is also true.
- [3/6] **Vacuous & Trivial Proofs**: 
  - Vacuous Proof: It is a proof that P → Q is true based on the fact that P is false.
    - ¬P → (P → Q)
  - Trivial Proof: It is a proof that P → Q is true based on the fact that Q is true.
    - Q → (P → Q)
- [4/6] **Proof by Contradiction**:
  - Steps in constructing Proof by Contradiction:
    1. Assume P is true.
    2. Assume ¬Q is true.
    3. Demonstrate a contradiction.
- Our instructor provided a clear definition of a rational number. 
  - The real number *r* is *rational* if there exist integers p and q with q≠0 such that **r = p/q**. Otherwise, it is an *irrational number*.
  - Q = {a/b | a, b ∈ ℤ} where b≠0, a & b have no common factor other than ±1
