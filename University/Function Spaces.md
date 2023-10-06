# Function Spaces
---

Be able to apply all our theory so far to 
$$\mathcal{F}(X,Y)$$
where $\mathcal{F}(X,Y)$ is the **set of all functions from $X$ to $Y$**

---
## Examples of Function Spaces

Lets consider 2 examples:

> [!math|{"type":"example","number":"auto","setAsNoteMathLink":false,"_index":0}] Example 1.
> Taking a look at function space  $$C([0,1])$$
> where $C([0,1])$ is the set of all continuous functions $f:[0,1] \rightarrow \mathbb{R}$ 

^2e09da


> [!math|{"type":"example","number":"auto","setAsNoteMathLink":false,"_index":1}] Example 2.
> Taking a look at function space $$B([0,1])$$
> where $B([0,1])$ is the set of all [[Bounded Function| bounded functions]]  $f:[0,1] \rightarrow \mathbb{R}$

---
## Metric on $C([0,1])$ and $B([0,1])$

 1. Trying to put a metric on $B([0,1])$, define a distance function $d:B([0,1]) \times B([0,1]) \rightarrow [0,\infty)$:
 $$d_{\infty}(f,g) = \sup\{\mid f(t) - g(t) \mid : t \in [0,1]\}$$
	 where $f$ and $g$ are functions.

 *Examples:* Lets take $f,g:[0,1] \rightarrow \mathbb{R}$ such that 
 $$\begin{split}f(t) = 1\end{split}\ \ \ \ \ \ \ \ \ \ \ \ \ \begin{split}g(t) = t\end{split}$$
 Therefore:
 $$\begin{aligned} d_{\infty}(f,g) &= \sup\{\mid f(t) - g(t) \mid\} \\ \\
 &= \sup\{\mid 1 - g(t) \mid \} \\ \\
 &= \sup\{\mid 1 - t \mid\} = 1.\end{aligned}$$
The pair $(B([0,1]), d_{\infty})$ is a particular type of [[General Definition of Metric Spaces| metric space]]. This is a particular type of a function space.

Verifying [[General Definition of Metric Spaces#^eb87d4|axioms]] for $B([0,1])$:

1. **(POSITIVE PROPERTY)**: $f$ and $g$ are **bounded functions** with domain $[0,1]$, and co-domain $\mathbb{R}$. So $f - g$ is the function:
$$f - g: [0,1] \rightarrow \mathbb{R}\  ; \  t \mapsto f(t) - g(t)$$
is bounded. Hence
$$d_{\infty}(f,g) = \sup(\underbrace{\mid  f(t) - g(t) \mid}_{\geq 0}) \leq M  \  \ \  \Rightarrow \ \ \ d_{\infty}(f,g) \geq 0 $$
2. If $f = g$, then $$\begin{aligned}f(t) = g(t) \ \forall t \in [0,1] \Rightarrow f(t) - g(t) = 0 \ \forall t \in [0,1] \ &\iff \mid f(t) - g(t) \mid = 0 \ \forall t \in [0,1]\\ \\
&\iff \sup(0) = 0\\ \\ &\iff d_{\infty}(f,g) = 0\end{aligned}$$
3. 