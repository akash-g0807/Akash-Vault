# Isometric Equivalence
---

```ad-Definition
Title: **Isometry** (ver 1)

Let $(X, d)$ and $(Y, d^{'})$ be [[General Definition of Metric Spaces|metric spaces]]. An **isometry** onto $A \subseteq Y$ is a function $\psi: X \rightarrow Y$ such that $\psi(X) = A$ (**surjective** onto A) and 
$$d(x,y) = d^{'}(\psi(x), \psi(y))$$
for all $x, y \in X$. We then say metric space $X$ is isometric to the [[Subspaces|subspace]] $A$ 

If $\psi(X) = Y$, that is $A = Y$, then we say metric spaces $X$ and $Y$ are isometric
```

---

```ad-Definition

Title: **Isometry** (ver 2)

Let $(X, d)$ and $(Y, d^{'})$ be [[General Definition of Metric Spaces|metric spaces]]. They are said to be **metrically equivalent** or **isometric** if there are **inverse functions**
$$f: X \rightarrow Y \ \ \ \text{and} \ \ \ g:Y \rightarrow X$$
such that for each $x, y \in X$, 
$$d(x,y) = d^{'}(f(x), f(y))$$
and for each $u,v \in Y$,
$$d^{'}(u,v) = d(g(u), g(v))$$

In this event we shall say that the **metric equivalence** or **isometry** is defined by $f$ and $g$
```

^650dd5

---

Here we will show that the isometry $\psi$ is **injective** hence a **bijection**.

## Further Notes
---
- [[Examples of Isometric Equivalence]]

