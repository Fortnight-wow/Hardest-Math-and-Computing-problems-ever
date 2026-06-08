# P versus NP

## The Question

Suppose someone hands you a solution to a problem. If you can verify that solution quickly, can you also find the solution quickly?

This simple question is the heart of the P versus NP problem.

- **P** is the class of problems that can be solved efficiently by an algorithm.
- **NP** is the class of problems whose solutions can be verified efficiently.

The central question is:

> Does P = NP?

If the answer is yes, many problems currently believed to be extremely difficult would suddenly become efficiently solvable.

## Why It Matters

P versus NP is arguably the most important open problem in theoretical computer science.

A positive solution would transform:

- Cryptography
- Logistics
- Scheduling
- Optimization
- Artificial Intelligence
- Computational Biology

Modern internet security relies heavily on the belief that P ≠ NP.

## Examples

Problems believed to be difficult include:

- Traveling Salesman Problem
- Boolean Satisfiability (SAT)
- Graph Coloring
- Knapsack Problem

For these problems, checking a proposed solution is easy, but finding one appears difficult.

## Current State of Research

Most computer scientists believe:

> P ≠ NP

However, no proof exists.

Several important barriers have been discovered:

- Relativization (Baker-Gill-Solovay, 1975)
- Natural Proofs (Razborov-Rudich, 1994)
- Algebrization (Aaronson-Wigderson, 2008)

These results explain why many previous proof techniques cannot settle the problem.

## Prize

The Clay Mathematics Institute offers a $1,000,000 prize for a correct solution.

## Important References

Cook (1971):
https://www.cs.toronto.edu/~sacook/homepage/cook71.pdf

Karp (1972):
https://cgi.di.uoa.gr/~sgk/teaching/grad/handouts/karp.pdf

Aaronson's survey:
https://www.scottaaronson.com/papers/pnp.pdf

## Status

Open.