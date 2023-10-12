# Interior and Exterior & Boundary Points
---
Suppose that $(X,d)$ is a [[General Definition of Metric Spaces|metric space]] and suppose $A \subset X$.
### Interior Points
---
```ad-Definition

TItle: **Interior Points**

An **INTERIOR POINT** $y \in X$ of $A$ is an element for which the [[Open and Closed Balls|open ball]] $B(y,\epsilon)$ contained entirely within $A$ *for some* $\epsilon > 0$ i.e.
$$B(y,\epsilon) \subset A$$

```

^263809

> [!note]+ Notation
> We call the set of all such **interior points** the of $A$, *the interior of $A$* and we denote it by:
> $$A^{O}$$

### Boundary Points
---
```ad-Definition

TItle: **Boundary Points**

The element $y \in X$ is a **BOUNDARY POINT** of $A$
$$\iff$$
*for any* $\epsilon > 0$, the [[Open and Closed Balls|open ball]] centered at $y$, $B(y,\epsilon)$, it hits the set but also has points outside the set:
$$B(y,\epsilon) \cup A \neq \emptyset \ \ \ \text{AND} \ \ \ B(y, \epsilon) \cup (A)^{c} \neq \emptyset$$
```

^72c666

>[! note]+ Notation
> The **boundary** of $A$ is the *set of all* boundary points of $A$ and is denoted by:
>$$\partial A$$ 

### Exterior Points
---
```ad-Definition

Title: **Exterior Points**

An element $y$ of $X$ is an **EXTERIOR POINT** of $A$
$$\iff$$
*there exists* $\epsilon > 0$ for which
$$B(y, \epsilon) \subseteq A^{c}$$
```

^9381fb

> [!note]+ Notation
> The **exterior** of $A$ is the *set of all* exterior points of $A$ denoted bt:
> $$A^{e}$$

*Note:* $A^{c}$ is the [[Complement of a Set]]. 
## Further Notes
---
- [[Disjoint Union Property for Interior, Exterior and Boundary Points]]
- [[Example Calculating Interior, Exterior and Boundary]]

# Backlinks
---
- [[The (basic) Geometry of Metric Spaces]]
- [[Metric Spaces - MAT00037H Outline]]