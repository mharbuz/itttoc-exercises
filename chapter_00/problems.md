# Chapter 0 - problems
## 0.10
Find the error in the following proof that $2 = 1$. 

Consider the equation $a = b$. Multiply both sides by a to obtain $`a^2 = ab`$. Subtract $b^2$ from both sides to get $`a^2 − b^2 = ab − b^2`$. Now factor each side, $`(a + b)(a − b) = b(a − b)`$, and divide each side by $`(a − b)`$ to get $`a + b = b`$. Finally, let a and $b$ equal $1$, which shows that $2 = 1$.

We cannot divide each side of equation $`(a + b)(a − b) = b(a − b)`$ by $`(a − b)`$ because $`a = b`$ implies $`a - b = 0`$ and division by zero is undefined.

## 0.11
Let $`S(n) = 1 + 2 + \ldots + n`$ be the sum of the first $n$ natural numbers, and let $`C(n) = 1^3 + 2^3 + \ldots + n^3`$ be the sum of the first n cubes. Prove the following equalities by induction on $n$, to arrive at the curious conclusion that $`C(n) = S^2(n)`$ for every $n$.

1. $`S(n) = \frac{1}{2} n(n+1)`$.
1. $`C(n) = \frac{1}{4}(n^4 + 2n^3 + n^2) = \frac{1}{4} n^2(n+1)^2`$.

## 0.12
Find the error in the following proof that all horses are the same color.

**CLAIM**: In any set of h horses, all horses are the same color.

**PROOF**: By induction on h.

*Basis*: For $h = 1$. In any set containing just one horse, all horses clearly are the same color.

*Induction step*: For $k ≥ 1$, assume that the claim is true for $h = k$ and prove that it is true for $h = k + 1$. Take any set $H$ of $k + 1$ horses. We show that all the horses in this set are the same color. Remove one horse from this set to obtain the set $H_1$ with just $k$ horses. By the induction hypothesis, all the horses in $H_1$ are the same color. Now replace the removed horse and remove a different one to obtain the set $H_2$. By the same argument, all the horses in $H_2$ are the same color. Therefore, all the horses in $H$ must be the same color, and the proof is complete.

## 0.13
Show that every graph with two or more nodes contains two nodes that have equal degrees.

## 0.14
Ramsey's theorem. 

Let $G$ be a graph. A clique in $G$ is a subgraph in which every two nodes are connected by an edge. An anti-clique, also called an independent set, is a subgraph in which every two nodes are not connected by an edge. Show that every graph with $n$ nodes contains either a clique or an anti-clique with at least $\frac{1}{2} log_2(n)$ nodes.

## 0.15
Use Theorem 0.25 to derive a formula for calculating the size of the monthly payment for a mortgage in terms of the principal P, the interest rate I, and the number of payments t. Assume that after t payments have been made, the loan amount is reduced to 0. Use the formula to calculate the dollar amount of each monthly payment for a 30-year mortgage with 360 monthly payments on an initial loan amount of $100,000 with a 5% annual interest rate.

**Theorem 0.25**

$`\forall t \geq 0`$

$`P_t=PM^t−Y\frac{M^t−1}{M−1}`$