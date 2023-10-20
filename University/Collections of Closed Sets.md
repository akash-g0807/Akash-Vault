# Collections of Closed Sets
---
Lets see what happens to the [[Properties of Topology on Metric Spaces]] when we replace [[Open and Closed Sets|open sets]] with [[Open and Closed Sets#^5a4f54|closed sets]]

---
> [!Definition]+ Collection of closed sets:  $\boldsymbol{\mathcal{F}_e}$
> Take an arbitrary collection of [[Open and Closed Sets|closed sets]] and let it be denoted by
> $$\mathcal{F}_e$$

### Properties of $\boldsymbol{\mathcal{F}_e}$ 
---
> [!note] F2) Arbitrary **intersections** of **closed sets**
> Take *any collections* of [[Open and Closed Sets|closed sets]], say
> $$\Lambda \subseteq \mathcal{F}_{e}$$
> Then the **intersection** of **closed sets** in $\Lambda$ is **closed**, i,e.
> $$\bigcap_{F \in \Lambda}F$$
> is **closed**

`\begin{proof}`
From the [[Relation between Open and Closed Sets]], that if $A$ is open $\Rightarrow A^{c}$ is closed:

$$\begin{aligned} \forall \ F \in \mathcal{F}_{e}\  &\Rightarrow F^{c} \in T_{d}\\ \\ 
&\Rightarrow \bigcup_{F \in \Lambda}F^{c} \in T_{d} \ \ \ \ \ \ \text{by property T2} \end{aligned}$$
Now by [[De Morgan's Law]],
$$\bigcup_{F \in \Lambda}F^{c} = \Bigg( \bigcap_{F\in\Lambda}F\Bigg)^{c}$$
and therefore we get by the [[Relation between Open and Closed Sets]]:
$$\bigcup_{F \in \Lambda}F^{c} \in T_{d} \Rightarrow \Bigg( \bigcap_{F\in\Lambda}F\Bigg)^{c} \in \mathcal{F}_{e}$$ where $T_{d}$ is the [[Topology on Metric Spaces]]. And hence $\bigcap F$ is [[Open and Closed Sets|closed]] 
`\end{proof}`

> [!note] F3) The **union** of **finite collection** of **closed sets**
> Take **any finite** collection of [[Open and Closed Sets|closed sets]]
> $$F_{1}, \ldots F_{N}$$
> Then,
> $$\bigcap_{i=1}^{N}F_{i}$$
> is [[Open and Closed Sets|closed]]

# Baclinks
---
- [[Topology on Metric Spaces]]
- [[Metric Spaces - MAT00037H Outline]]