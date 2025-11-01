# Subset-Sum-algorithms
# Subset Sum Algorithm Comparison (Brute Force vs. Dynamic Programming)

This repository provides an educational comparison of two fundamental approaches to solving the **Subset Sum Problem**: Brute Force (Exhaustive Search) and Dynamic Programming (DP).

## The Problem

Given a set of non-negative integers (e.g., $S = \{3, 5, 9, 4, 8\}$) and a target sum ($M = 16$), the goal is to determine if a subset of $S$ exists that adds up exactly to $M$.

The subset sum problem is a classic example of an NP-complete problem. This means it is both in the complexity class NP (a potential solution can be verified in polynomial time) and NP-hard (every other problem in NP can be reduced to it in polynomial time). 

The brute force approach is an exact approach to solve the problem, but inefficient for a large number of list items, n. 
## 🚀 Algorithms and Complexity

| Approach | Description | Time Complexity | Notes |
| :--- | :--- | :--- | :--- |
| **Brute Force** | Tries every possible subset ($2^n$ total) to find the solution. | $\mathbf{O(2^n)}$ (Exponential) | Highly inefficient for large input sets. |
| **Dynamic Programming** | Builds a table of solutions to smaller subproblems ($DP[i][j]$). | $\mathbf{O(n \cdot M)}$ (Pseudo-polynomial) | Faster than Brute Force, but performance depends on the magnitude of the target sum ($M$). |
