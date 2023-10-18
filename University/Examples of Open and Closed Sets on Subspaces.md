# Examples of Open and Closed Sets on Subspaces
---
> [!example] 
> Consider the [[General Definition of Metric Spaces|metric space]] $(\mathbb{R}, d)$ consider the [[Subspaces|subspace]]
> $$(A,d\mid_A)$$
> and define the set $A$ to be
> $$A = (0,1) \cup (1,2) \subset \mathbb{R}$$

*Note*: Since $A$ is a subspace, it can only *see* what ***points lie in A*** and **cannot** see points outside of $A$.

1. Therefore the [[Interior and Exterior and Boundary Points|boundary points]] of $A$ are:
$$\partial A = \emptyset$$
as $1,2,0 \not\in A$ as subspace **cannot see $\mathbb{R}$**

2. Here the [[Interior and Exterior and Boundary Points#^263809|interior points]] is are entire set, i.e.
$$A^{o} = A$$
3. Since the subspace **cannot see** *beyond* $A$, there are **NO EXTERIOR** points.
$$A^{e} = \emptyset$$
---
>[!example]
>Now consider the subset of a [[Subspaces|subspace]]
>$$(0,1) \subseteq (0,1) \cup (1,2)$$

*Note:* The subset is **only contained** in $A = (0,1) \cup (1,2)$ and **not in** $\mathbb{R}$ since $A$ is a subspace.

> [!math|{"type":"claim","number":"","setAsNoteMathLink":false}] Claim.
> The subset  $(0,1)$ is **[[Open and Closed Sets|clopen]]**

`\begin{proof}`
Since the subspace $A$ has **no** [[Interior and Exterior and Boundary Points#^72c666|boundary points]]
$$\partial(0,1) = \emptyset$$ and hence we can deduce that
$$\partial(0,1) \cap (0,1) = \emptyset \Rightarrow \text{open} \tag{1}$$
and hence by definition, [[Open and Closed Sets|open]] ^a8bb22

Now since the empty set is the **subset of all sets**
$$\partial(0,1) = \emptyset \subseteq (0,1)  \Rightarrow \text{closed} \tag{2}$$
and hence by definition [[Open and Closed Sets|closed]] ^698e4e

Therefore by [[#^a8bb22|(1)]] and [[#^698e4e|(2)]], it is [[Open and Closed Sets|clopen]]
`\end{proof}`
# Backlinks
---
- [[Open and Closed Sets]]
- [[Metric Spaces - MAT00037H Outline]]