# Boundary of  a set and its complement $(\partial A = \partial A^c)$
---
```ad-Theorem
Suppose $(X,d)$ is a [[General Definition of Metric Spaces|metric space]] and $A \subseteq X$, then
$$\partial A = \partial A^{c}$$
i.e. the [[Interior and Exterior and Boundary Points|boundary]] of a set and the complement are the **same**.
```

`\begin{proof}`
By the definition of [[Interior and Exterior and Boundary Points#^72c666|boundary points]], any $y \in \partial A$ *if and only if* for any [[Open and Closed Balls|open ball]] $B$ *centered* at $y,$

$$B(y,\epsilon) \cap A^{c} \neq \emptyset \ \ \ \ \ \ \text{ and} \ \ \ \ \ \ \ \ B(y,\epsilon) \cap A \neq \emptyset \tag{1}$$ ^7db042

But by the definition of [[Complement of a Set]], 
$$(A^{c})^{c} = A$$
And therefore for any [[Open and Closed Balls|open balls]] centered at $y$, [[#^7db042|(1)]], becomes:

$$B(y,\epsilon) \cap A^{c} \neq \emptyset \ \ \ \ \ \ \  \text{and} \ \ \ \ \ \ \ \  B(y,\epsilon) \cap (A^{c})^{c} \neq \emptyset$$
and this is the [[Interior and Exterior and Boundary Points|definition of boundary points]] of $A^c$ that is $\partial A^c$.

Therefore **ALL** points *in* $\partial A$ are points *in* $\partial A^{c}$ and vice-verca and hence
$$\partial A = \partial A^{c}$$

`\end{proof}`
# Backlinks
---
- [[Relation between Open and Closed Sets]]