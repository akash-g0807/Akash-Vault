# Describing Open Sets using Interior Points
---
>[!fact] **Fact**: Open Sets using Interior Points
> Let $(X,d)$ be a [[General Definition of Metric Spaces|metric space]] and $A \subseteq X$.
> If $A$ is [[Open and Closed Sets|open]], then **every point** of $A$ is an [[Interior and Exterior and Boundary Points|interior point]].

We can formulate this into a theorem

---
```ad-Theorem

Title: **Open sets using Interior Points**

Let $(X,d)$ be a [[General Definition of Metric Spaces|metric space]] and $A \subseteq X$. Then

$A$ is [[Open and Closed Sets|open]] $\iff \forall x \in A, \exists \epsilon = \epsilon(x)$ such that $B(x,\epsilon) \subseteq A$ 

where $B(x,\epsilon)$ is an [[Open and Closed Balls|open ball]] centered at $x$, with radius $\epsilon$
```

`\begin{proof}`
The set $A = \emptyset$ or $A \neq \emptyset$
**($\Rightarrow$)**
1. ¬ **CASE 1** $A = \emptyset$:
Since the empty set $\emptyset$ is [[Examples of Open and Closed Sets|clopen]], it is open and we are done
2.  ¬ **CASE 2** $A \neq \emptyset$: Since $A$ is an [[Open and Closed Sets|open]], it will have **no boundary** point and therefore it will *satisfy* the [[Contrapositive]]([[Negation]]) of the definition of [[Interior and Exterior and Boundary Points|boundary]]:
There must be *at-least one* $\epsilon >0$ such that
$$B(x,\epsilon) \subseteq A \ \ \ \ \ \ \ \text{OR} \ \ \ \ \ \ \ B(x,\epsilon)  \subseteq A^{c} \ \ \ \ \forall x \ \in A $$
for [[Open and Closed Balls|open ball]] centered at $x$ of radius $\epsilon$
Since $x \in A$, $B(x, \epsilon) \subseteq A^{c}$ **cannot** be true since it implies $x \in A^{c}$ which is a **contradiction**. 
Thus
$$B(x,\epsilon) \subseteq A$$

**($\Leftarrow$)**
Assume that $\forall x \in A$, $\exists \epsilon = \epsilon(x) > 0$ such that

$$B(x,\epsilon) \subseteq A \tag{1}$$ ^d6bbef

As a *consequence*, $$x \not\in \partial A \ \ \ \ \ \ \ \ \ \ \forall x$$
since if $x \in \partial A$, then we can *find* an $\epsilon > 0$ such that $B(x, \epsilon) \cap A^{c} \neq \emptyset$ and thus is a **contradiction** to [[#^d6bbef|(1)]] 
`\end{proof}`
# Backlinks
---
- [[The (basic) Geometry of Metric Spaces]]
- [[Metric Spaces - MAT00037H Outline]]