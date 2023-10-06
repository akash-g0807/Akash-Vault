# Infimum and Supremum
---

```ad-Theorem

Suppose $S$ is a non-empty subset of $\mathbb{R}$, i.e. $S \neq \emptyset$ and $S \subseteq \mathbb{R}$. Then:
1. **(SUPREMUM)**: If $S$ is bounded above, then it has a **minimal/least upperbound** called **supremum** of S written $\sup(S)$
2. **(INFIMUM)**: If $S$ is bounded below, then it has a **maximal/greatest lowerbound** called **infimum** of S written $\inf(S)$
```

^6ee25d

`\begin{proof}`
1. Suppose S is bounded above. 
Let $B$ be the set of all [[Boundedness of Sets#^49715c|upperbounds]] and since S is bounded above, $B \neq \emptyset$.

$$\begin{aligned} x \in S \ \ \ \text{and} \ \ \ b \in B \ \ \ \  & \Rightarrow \ \ \ x \leq b \\  \\ & \text{(by definition of upperbound)} \end{aligned}$$
By the [[Axiom of Completeness]],

$$\begin{aligned} \exists  \ c \in \mathbb{R} \ \ \text{such that} \ \ \forall \ x \in S  \ \ \text{and} \ \ b \in B , \ \ \ & x \leq c \leq b \\ \\ 
& \Rightarrow x \leq c \ \ \text{and} \ \ c \leq b\end{aligned}$$
We can draw the following conclusions:
1. $x \leq c, \  \forall x \in S \Rightarrow$ **c is an upperbound for $S$** ^5363d0
2. $c \leq b, \forall b \in B \Rightarrow$ **c is the least of all upperbounds**. ^ee2b5c

From [[#^5363d0|$(1)$]] and [[#^ee2b5c|$(2)$]] we can say that **$c$ is the least upperbound** and hence it is the **supremum**

2. Proof is similar.
`\end{proof}`
## Further Notes
---
- [[Remarks About Supremum and Infimum]]
- [[Equivalent Formulation of Infimum and Supremum]]

# Backlinks
---
- [[Review of Real Analysis]]