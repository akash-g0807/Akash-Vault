# Interior and Exterior & Boundary Points
---
Suppose that $(X,d)$ is a [[General Definition of Metric Spaces|metric space]] and suppose $A \subset X$.
### Interior Points
---
```ad-Definition

TItle: **Interior Points**

An **interior point** $y \in X$ of $A$ is an element for which the [[Open and Closed Balls|open ball]] $B(y,\epsilon)$ contained entirely within $A$ *for some* $\epsilon > 0$ i.e.
$$B(y,\epsilon) \subset A$$

```

> [!note]+ Notation
> We call the set of all such **interior points** the of $A$, *the interior of $A$* and we denote it by:
> $$A^{O}$$

### Boundary Points
---
```ad-Definition

TItle: **Boundary Points**

The element $y \in X$ is a **boundary point** of $A$
$$\iff$$
*for any* $\epsilon > 0$, the [[Open and Closed Balls|open ball]] centered at $y$, $B(y,\epsilon)$, it hits the set but also has points outside the set:
$$B(y,\epsilon) \cup A \neq \emptyset$$
```
