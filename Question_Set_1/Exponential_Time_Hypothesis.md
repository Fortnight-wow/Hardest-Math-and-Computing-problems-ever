# Exponential Time Hypothesis (ETH)

## The Question

The Exponential Time Hypothesis was proposed by Impagliazzo and Paturi in 1999.

It is a stronger assumption than simply believing that P ≠ NP.

ETH states that 3-SAT cannot be solved in subexponential time.

More precisely, there exists a constant c > 0 such that no algorithm can solve every instance of 3-SAT in time:

2^(cn)

or faster.

## Why It Matters

ETH has become one of the most important assumptions in theoretical computer science.

Instead of proving that a problem is NP-hard, researchers often use ETH to obtain precise lower bounds.

It has applications in:

- Graph Algorithms
- Parameterized Complexity
- Approximation Algorithms
- Computational Geometry

## Current State of Research

Thousands of complexity results are now conditional on ETH.

If ETH were disproved, many established lower-bound results would collapse.

If ETH were proved, it would significantly strengthen our understanding of computational hardness.

## References

Impagliazzo and Paturi (1999):
https://doi.org/10.1007/3-540-48686-0_16

Survey by Cygan et al.:
https://link.springer.com/book/10.1007/978-3-319-21275-3

## Status

Open.