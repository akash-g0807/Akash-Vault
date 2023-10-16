# Examples of Open and Closed Sets
---
Let $(X,d)$ be a [[General Definition of Metric Spaces|metric space]]

> [!example] 
> Consider the sets
> $$(0,1), \ \ [0,1], \ \ (0,1] $$ 

Here,
- The set $(0,1)$ is an [[Open and Closed Sets|open set]].
- The set $[0,1]$ is a [[Open and Closed Sets|closed set]]
- The set $(0,1]$ is neither [[Open and Closed Sets|open]] nor [[Open and Closed Sets|closed]]. 

> [!example] 
> $$(0,1 )\cup (1,2)$$

$\partial A = \{0,1,2\}$, we see that $A \cap \partial A = \emptyset \Rightarrow$ $A$ is open. Furthermore $\partial A \not\subseteq A \Rightarrow A$ is not closed.   
#### Example of a clopen set
---
> [!example] 
> The sets 
> $$X, \emptyset$$
> are both **open AND closed**, i,e. they are [[Open and Closed Sets#^6a7cd3|clopen]]

That is the **empty set** $\emptyset$ and the **entire space** $X$ are [[Open and Closed Sets#^6a7cd3|clopen]]. The following argument proves this fact:

> [!math|{"type":"claim","number":"auto","setAsNoteMathLink":false,"_index":0}] Claim 1.
> $\emptyset$ is **clopen**

`\begin{proof}`
The boundary of an empty set is empty, i.e.
$$\partial \ \emptyset = \emptyset$$
And therefore by the definition of [[Open and Closed Sets#^638716|open sets]],
$$\emptyset \cap \partial\emptyset = \emptyset \cap \emptyset = \emptyset$$
which shows $\emptyset$ is **open**. Further, by the definition of [[Open and Closed Sets#^5a4f54|closed sets]], 
$$\partial \emptyset = \emptyset \subseteq \emptyset$$
since the empty set $\emptyset$ is the **subset of ALL sets**, *including itself*, and is therefore **closed**. Therefore $\emptyset$ is **clopen**
`\end{proof}`

> [!math|{"type":"claim","number":"auto","setAsNoteMathLink":false,"_index":1}] Claim 2.
> $X$ is **clopen**

`\begin{proof}`
From [[Interior and Exterior and Boundary Points#^d456f3|boundary of an the whole space]] $X$ is the empty set i.e. 
$$\partial X = \emptyset$$
And therefore by the definition of [[Open and Closed Sets#^638716|open sets]]:
$$\partial X \cap X = \emptyset \cap X = \emptyset$$
which shows $X$ is open. Further, by the definition [[Open and Closed Sets#^5a4f54|closed sets]], 
$$\partial X = \emptyset \subseteq X$$
`\end{proof}`
since the empty set $\emptyset$ is the subset of ALL sets, and therefore **open**. Therefore $X$ is **clopen**. 



# Backlinks
---
- [[Open and Closed Sets]]
- [[The (basic) Geometry of Metric Spaces]]
- [[Metric Spaces - MAT00037H Outline]]