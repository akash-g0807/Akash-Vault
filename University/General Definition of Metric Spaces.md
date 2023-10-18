# Metric Spaces
---

```ad-Definition
Title: **Metric and Metric Space**

Suppose $X$ is a set and $d$ is a *real* function defined on the [[Cartesian Product]] $X \times X$. Then $d$ is called a *Metric* on $X$ if, and only if, for each $a,b,c \in X$, the function:
$$ d: X \times X \rightarrow [0,\infty)$$
has the following properties:
1. **(POSITIVE PROPERTY)**: $d(a,b) \geq 0$ 
2. $d(a,b) = 0$ if, and only if, $a=b$
3. **(SYMMETRIC PROPERTY)**: $d(a,b) = d(b,a)$
4. **(TRIANGLE INEQUALITY)**: $d(a,b) \leq d(a,c) + d(c,b)$

The pair of objects $(X,d)$ is called the **Metric Space**
```

^eb87d4


*Note*: Property 4 may be thought of as asserting the "transitivity" of closeness of two points, that is if $x$ is close to $y$ and $y$ is close to $z$ then $x$ is close to $z$

### Rearrangement of the Triangle Inequality

```ad-Theorem
Theorem 1: **Rearrangement of the Triangle Inequality**

Suppose $X$ is a metric space and $a,b,c \in X$. Then $$\mid d(a,b) - d(b,c) \mid \leq d(a,c)$$
```

`\begin{proof}`
The triangle inequality for $d(a,b)$ yields:
$$d(a,b) \leq d(a,c) + d(c,b)$$
Similarly the triangle inequality for $d(b,c)$ yields:
$$d(c,b) \leq d(c,a) + d(a,b)$$
`\end{proof}`

#### Useful tip
---
*Note:* For [[#^eb87d4|property 2]], we can split the biconditionals to two if statements:
$$\begin{aligned}a = b \Rightarrow d(a,b) = 0 
\\ \\ d(a,b) = 0 \Rightarrow a = b\end{aligned}$$
And we can prove each individually or take **contrapositives**.

# Backlinks
---
- [[Metrics]]
- [[Metric Spaces - MAT00037H Outline]]


