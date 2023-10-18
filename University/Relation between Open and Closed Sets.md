# Relation between Open and Closed Sets
---
```ad-Theorem
Let $(X,d)$ be a [[General Definition of Metric Spaces|metric space]] and let $A \subseteq X$ be an [[Open and Closed Sets|open set]]. Then
$$A  \subseteq X \text{ is open} \iff A^{c} \text{\ is closed}$$
```

`\begin{proof}`
**($\Rightarrow$):**
Lets assume that $A \subseteq X$ is open. Then $A = \emptyset$ or $A \neq \emptyset$. 
1. **CASE 1:** If $A = \emptyset$ then by definition of [[Complement of a Set]], $A^{c} = X$ and [[Examples of Open and Closed Sets|$X$ is both open and closed]] and therefore
$$A^{c}= X \text{ is closed}$$
2. **CASE 2:** If $A \neq \emptyset$, by definition of [[Open and Closed Sets|open]], 
$$\partial A \cap A = \emptyset \Rightarrow \partial A \subseteq A^{c}$$
*Note*: [[Boundary of a set and its complement|$\partial A = \partial A^{c}$]]  and hence
$$\partial A \subseteq A^{c} \Rightarrow \partial A^{c} \subseteq A^{c}$$ which by definition means $A^{c}$ is [[Open and Closed Sets|closed]]

**($\Leftarrow$):** 
Suppose that $A^{c}$ is closed. the  by the definition of [[Open and Closed Sets|closed sets]],
$$\partial A ^{c}\subseteq A^{c} \Rightarrow \partial A^{c} \cap A = \emptyset$$
As by $A^{c}$ is [[Open and Closed Sets|closed set]], the entirety of the boundary is **contained in** $A^{c}$, i.e.  $\partial A^{c} \subseteq A^{c}$ , and therefore $\partial A^{c}$ has **no common element** with $A$, i.e. $\partial A^{c} \cap A = \emptyset.$

*Note:*  [[Boundary of a set and its complement|$\partial A = \partial A^{c}$]]  and hence
$$\partial A^{c} \cap A = \emptyset \Rightarrow \partial A \cap  A = \emptyset$$
and hence $A$ is open by the definiiton of [[Open and Closed Sets|open sets]]
`\end{proof}`

# Backlinks
---
- [[The (basic) Geometry of Metric Spaces]]
- [[Metric Spaces - MAT00037H Outline]]