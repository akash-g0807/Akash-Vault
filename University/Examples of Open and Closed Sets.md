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