# Properties of Closure
---
Here we discuss the properties of [[Closure of a set]] $A$

### $\boldsymbol{\bar{A}}$ is closed
---
```ad-Theorem

The **closure** of $A$ which is $\bar{A}$ is [[Open and Closed Sets|closed]], i.e.
$$\bar{A} = A \cup \partial A$$
is [[Open and Closed Sets|closed]]
```

`\begin{proof}`
Using the [[Relation between Open and Closed Sets]],
$$\bar{A}  \text{ is closed } \iff (\bar{A})^{c} \text{ is open }$$
Therefore it is *sufficient* to show that $(\bar{A})^{c}$ is [[Open and Closed Sets|open]].

1. **CASE 1:** If $(\bar{A})^{c} = \emptyset$, since [[Examples of Open and Closed Sets|$\emptyset$ is clopen]], so we are done
---
2.  **CASE 2:** If $(\bar{A})^{c} \neq \emptyset$, then we need to show that ([[Open and Closed Sets|defn of open]])
$$ \forall x \in (\bar{A}),\  \exists \varepsilon = \varepsilon(x) \ \ \ \text{such that} \ \ \ B(x, \varepsilon) \subseteq (\bar{A})^{c}$$
Take $x \in (\bar{A})^{c}$ and we get the following
$$\begin{aligned} x \in (\bar{A})^{c} &\Rightarrow x \not\in \bar{A} \\ \\
&\Rightarrow x \not\in (A \cup \partial A)  \\ \\
&\Rightarrow x \not\in A \ \ \text{ AND } \ \ x \not\in \partial A \end{aligned}$$
Since $x \not\in \partial A$, using the **negation** of [[Interior and Exterior and Boundary Points|defn of boundary]],
$$x \not\in \partial A \Rightarrow \exists \varepsilon > 0 \ \  \text{ such that }\ \  B(x, \varepsilon) \subseteq A \ \  \text{OR} \ \ B(x, \varepsilon) \subseteq A^{c}$$
Since $x \not\in A$, to prevent a *contradiction*, $B(x, \varepsilon) \not\subseteq A$, and therefore by **cancellation**,
$$B(x, \varepsilon) \subseteq A^{c}$$
But we also *need* to **stay away from** $\partial A$. 
Suppose 
$$\exists y \in B(x, \varepsilon) \ \ \text{such that} \ \ y \in \partial A$$
Then $y \in \partial A$, and by [[Interior and Exterior and Boundary Points|definition of boundary]],
$$B(y, \delta) \cap A \neq \emptyset \ \ \ \ \text{AND} \ \ \ \  $$


`\end{proof}`
