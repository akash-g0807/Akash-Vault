# Metric Induced by the norm
---

We call the  [[Basics of Vector Spaces|vector space]] with a [[Norm in a Vector Space|norm]] a **normed space**, and all normed spaces have a natural metric called **metric induced by the norm** and 
$$d: V \times V \rightarrow [0,\infty):\  \mid\mid \underline{u} - \underline{v} \mid\mid = \mid\mid\underline{u} + (-1)\underline{v} \mid\mid$$
### Example of Vector Space $\rightarrow$ Normed Space $\rightarrow$ Metric Space chain.
---
Looking at: [[Function Spaces#^2e09da|$C([0,1])$]]: the set of all continuous functions on **closed** and **bounded** set:
$C([0,1])$ is a [[Basics of Vector Spaces|vector space]];
$$f:[0,1] \rightarrow \mathbb{R}\ \ \ \ \ \text{and} \ \ \ \ \ g:[0,1]\rightarrow\mathbb{R} $$
are vectors because 
$$f+g:[0,1] \rightarrow \mathbb{R}:t\mapsto f(t) + g(t)$$
is a **continuous function**. Further taking a scalar value $\lambda \in \mathbb{R}$,
$$\lambda f:[0,1] \rightarrow \mathbb{R}:t\mapsto \lambda f(t)$$
is continuous. Therefore **we can put norms** $\mid\mid\cdot\mid\mid$ on $C([0,1])$. 

*Note*: Going back to $\mathbb{R}^{2,}$ can define the [[Examples of Metric Spaces|metric spaces]] $d_1$, $d_2$ and $d_{\infty}$ as the following:

- $\displaystyle d_{1}(x,y)= \sum\limits_{i=1}^{n}\mid x_{i}-y_{i}\mid$
-  $d_{2}(x,y)= \sqrt{\sum\limits_{i=1}^{n}\mid x_{i}-y_{i} \mid^{2}}$
- $\displaystyle d_{\infty}(x,y) = \max\{\mid x_{i} - y_{i} \mid : i \in \{1, \ldots n\}\}$

In analogue to this, we construct 3 [[Norm in a Vector Space|norms]] $\mid\mid f\mid\mid_{1}$, $\mid\mid f\mid\mid_{2}$, $\mid\mid f \mid\mid_{\infty}$, which will induce a metric which will induce analogues to $d_{1}$, $d_2$ and $d_{\infty}$. 

Define the norms as the following:
- $\displaystyle \mid\mid f \mid\mid_{1}= \int_{0}^{1}\mid f(t) \mid dt$
- $\displaystyle \mid\mid f \mid\mid_{2} =\Bigg( \int_{0}^{1}\mid f(t) \mid^{2}  \Bigg)^{1/2}$ 
- $\displaystyle \mid\mid f \mid\mid_{\infty} = \sup\{\mid f(t) \mid : t \in [0,1]\}$

*Note:* (We need to use integrals as the inputs to the distance functions we are dealing with are functions hence are not discrete but continuous hence the sums get reduced to integrals)

Our **corresponding induced metrics** are:

- $\displaystyle d_{1}(f,g) = \mid\mid f-g \mid\mid_{1} = \int_{0}^{1}\mid f(t) - g(t) \mid dt$
- $\displaystyle d_{2}(f,g) = \mid\mid f-g \mid\mid_{2} = \Bigg( \int_{0}^{1}\mid f(t) - g(t) \mid^{2}  \Bigg)^{1/2}$
- $d_{\infty}(f,g) = \mid\mid f-g \mid\mid_{\infty} = \sup\{\mid f(t) - g(t) \mid : t \in [0,1]\}$

#### Example of using metric induced by norm: $d_{2}$

For example taking $f(t) = t$ and $g(t) = t^{2}$:

$$\begin{split} d^{2}_{2}(f,g) =& \int^{1}_{0}\mid t^{2} - t \mid^{2} dt \\ \\
=& \int_{0}^{1}(t - t^{2})^{2} \ dt \\ \\
=& \int^{1}_{0}(t^{2} - 2t^{3} + t^{4}) \ dt \\ \\
=& \bigg[\frac{t^{3}}{3} - \frac{t^{4}}{2}+ \frac{t^{5}}{5} \bigg] = \frac{1}{30} \end{split}$$
```desmos-graph 
left=-1; right = 3
top = 2; bottom = -1
---
 y=x 
 y=x^2
```

*Note:* From the graph, we can see that for $t \in [0,1]$, **$t > t^{2}$** and therefore we can have the following chain of equalities:
$$\mid t^{2}- t \mid = (t-t^{2})\geq 0$$
### Generalizing $C([0,1])$
---

We can generalize $C([0,1])$ by $a,b \in \mathbb{R}$ 
$$C([a,b])$$
as long as $-\infty < a < b <\infty$.

Furthermore, we can replace $\mathbb{R}$ in $C([0,1])$ with $\mathbb{C}$, $f:[0,1] \rightarrow \mathbb{C}$.