# Relation between Open and Closed Sets
---
```ad-Theorem
Let $(X,d)$ be a [[General Definition of Metric Spaces|metric space]] and let $A \subseteq X$ be an [[Open and Closed Sets|open set]]. Then
$$A  \subseteq X \text{ is open} \iff A^{c} \text{\ is closed}$$
```

`\begin{proof}`
Lets assume that $A \subseteq X$ is open. Then $A = \emptyset$ or $A \neq \emptyset$. 

1. **CASE 1:** If $A = \emptyset$ then by definition of [[Complement of a Set]], $A^{c} = X$ and [[Examples of Open and Closed Sets|$X$ is both open and closed]] and therefore
$$A^{c}= X \text{ is closed}$$
2. **CASE 2:** If $A \neq \emptyset$, by definition of [[Open and Closed Sets|open]], 
$$\partial A \cap A = \emptyset \Rightarrow \partial A \subseteq A^{c}$$
`\end{proof}`