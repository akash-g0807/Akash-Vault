# Properties of Total Derivative
---

The [[Definition of Total Derivative|total derivative]] has under addition and multiplication by a scalar.

For $\underline{f}, \underline{g}: \mathbb{R}^{n} \rightarrow \mathbb{R}^m$:

1. **(ADDITION PROPERTY):**
$$D(\underline{f} + \underline{g})(\underline{x}) = D\underline{f}(\underline{x}) \ + \ D\underline{g}(\underline{x})$$
2. **(SCALAR MILTIPLICATION PROPERTY):** For $\lambda \in \mathbb{R}$:
$$D(\lambda\underline{f})(\underline{x}) = \lambda\underline{f}(\underline{x})$$
3. **(PRODUCT RULE):** For a scalar function $f: \mathbb{R}^{n} \rightarrow \mathbb{R}$ and a vector function $\underline{g}: \mathbb{R}^{n} \rightarrow \mathbb{R}^m$:
$$D(f\underline{g})(\underline{x}) = f(\underline{x})D(\underline{g}(\underline{x}))\  +\ \underline{g}(\underline{x})D(f(\underline{x}))$$
4. **(CHAIN RULE):** If $\underline{f}: \mathbb{R}^{n} \rightarrow \mathbb{R}^{m}$ and $\underline{g}: \rightarrow \mathbb{R}^{m} \rightarrow \mathbb{R}^p$ are functions then the **composition** of functions $\underline{g} \circ \underline{f}: \mathbb{R}^{n} \rightarrow \mathbb{R}^{p}$ has derivative 
$$D(\underline{g}\  \circ \underline{f})(\underline{x}) = D\underline{g}(\underline{f}(\underline{x}))D\underline{f}(\underline{x})$$
(Done using matrix multiplication) ^7226d1

## Further Notes
---
- [[Examples of Calculating Total Derivative]]

# Backlinks
---
- [[Derivatives of Vector Functions]]