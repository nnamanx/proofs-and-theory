# Complete Graph Edge Count Proof

**Category:** Graph Theory 
**Dare:** 11/11/2025 

A short mathematical proof showing why a **complete graph** with n vertices has  `n(n - 1) / 2` edges.

---

## Definition

A **complete graph** is a simple undirected graph where **every pair of distinct vertices** is connected by a unique edge.

---

## Proof: Handshake Lemma

In `Kₙ`:
- Every vertex connects to `n - 1` others.
- Thus, each vertex has **degree = n - 1**.

Sum of all degrees = `n × (n - 1)`

By the **Handshake Lemma**:

`
∑deg(v) = 2|E|
`

Hence,
```
2|E| = n(n − 1)

|E| = n(n − 1) / 2
```

---

## Example Table

| n | Edges Formula | Edge Count | Description |
|:-:|:-:|:-:|:-|
| 1 | n(n−1)/2 | 0 | single vertex, no edge |
| 2 | n(n−1)/2 | 1 | single edge |
| 3 | n(n−1)/2 | 3 | triangle |
| 4 | n(n−1)/2 | 6 | square with diagonals |
