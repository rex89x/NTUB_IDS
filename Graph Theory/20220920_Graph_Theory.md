# 20220920 NTUB IDS 資訊理論基礎與應用 Class

數學名詞定義
---

- Definition `定義`
- Theorem `定理`
- Lemma `引理`
- Corollary `推論`

### Books 1.0

`The following are all mathematical statements`
- There are 168 primes less than 1000 (primes 質數)
- Seventeen is an (odd/even) number (even 偶數/odd 奇數)
- rational number (有理數)
- irrational number (無理數)
- Zero is not (negative 負數/positive 正數)

### Books 1.1 Compound Statements

- "And" and "Or"

        "p and q is true if both p and q are true; it is false if either p is false or q is false"

----

        "p or q is true if p is true or q is true or both p and q are true; it is false only when both p and q are false."

----

Thus, 

    "7 + 5 = 12 or 571 is the 125th prime" and "25 is less than or equal to 25" are both true sentences, while "5 is an even number or √8 > 3"

----

#### Implication

**the hypothesis and conclusion. The symbol -> is read "implies"**

`"2 is an even number -> 4 is an even number"`
is read "2 is an even number implies 4 is an even number"

----

p <-> q

    p if and only if q (若且唯若)
    
----

`->p` equals `not p`

    The negation of "p and q" is the assertion "not p or not q"
    The negation of "p or q" is the assertion "not p and not q"

----

3 | 6

    6 divide 3 
    
----

(p ∩ q) = ∪

----

| p | q | p -> q | not p | not q | (not q) -> (not p)
| -------- | -------- | -------- |-------- |-------- |-------- |
| T     | T     | T     | F  | F  | T |
| T     | F     | F     | F  | T  | F |
| F     | T     | T     | T  | F  | T |
| F     | F     | T     | T  | T  | T |

----

### Quantifiers (量詞)

`∀` (for all) (for every) (for any) (for each)
`∃` (there is, there are) (exists)

    "x^2 + x + 1" > 0 for all real numbers x."
    "x^2 + x + 1" > 0 ∀ real numbers x."
    
    "All polynomials are continuous functions."
    "∀ polynomials are continuous functions."
    
    "For any positive integer n, 2(1 + 2 + 3 + ... + n) = n x (n + 1)"
    "∀ positive integer n, 2(1 + 2 + 3 + ... + n) = n x (n + 1)"
    
    "(AB)C = A(BC) for all square matrices A, B, and C."
    "(AB)C = A(BC) ∀ square matrices A, B, and C."

----

    "There exists a smallest positive integer."
    "∃ a smallest positive integer."
    
    "Two sets may have no element in common."
    "There is no common element in two sets"
    "Two sets may ∃ no element in common."
    
    "Some polynomials have no real zeros."
    "Some polynomials ∃ no real zeros."
    
----

    "Every positive integer is the product of primes."
    "For every positive integer n, 
    there exists two primes a and b such that n = a x b"
    
    "Every nonempty set of positive integers has a smallest element"
    "For any nonempty set of positive integer A,
    there is a smallest element in A"
    
----

    "There exist a and b for which ab != ba"
    "There exist a and b such that ab != ba"

----

Rex Tsou 2022/09/20

###### tags: `IDS` `Deep Learning` `Class` `Program`