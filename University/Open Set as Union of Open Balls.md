# Open Set as Union of Open Balls
---
```ad-Theorem

Title: **Open Sets as Union of Open Balls**

Suppose $(X,d)$ is a [[General Definition of Metric Spaces|metric space]] and that $A \subseteq X$.

If $A \in T_{d}$ where $T_{d}$ is the [[Definition of Topology on Metric Spaces|Topology on Metric Spaces]], then **A is the union of [[Open Set as Union of Open Balls|open balls]]**
$$A = \bigcup_{x \in A}B(x, \varepsilon)$$
```

`\begin{proof}`
Take $x \in A$ and therefore by the [[Describing Open Sets using Interior Points|definition of open sets using interior points]], 
$$\text{For any } x \in A, \exists \varepsilon = \varepsilon(x) \text{ such that } B(x, \varepsilon) \subseteq A$$
where $B(x, \varepsilon)$ is an [[Open and Closed Balls|open ball]]
Now, since $x \in B(x,  \varepsilon(x))$, therefore if we go through all points $x \in A$,

$$A \subseteq \bigcup_{x \in A} B(x, \varepsilon(x)) \tag{$*1$}$$ ^c23d28

Further we can see that since $B(x, \varepsilon(x)) \subseteq A$ *for any* $x$,

$$\bigcup_{x \in A}B(x, \varepsilon(x)) \subseteq A \tag{$*2$}$$ ^04393a

Therefore by the combing [[#^c23d28|$(*1)$]] and [[#^04393a|$(*2)$]] using the [[Principle of Mutual Containment]], 
$$A = \bigcup_{x \in A}B(x , \varepsilon)$$
`\end{proof}`

# Backlinks
---
- [[The (basic) Geometry of Metric Spaces]]
- [[Metric Spaces - MAT00037H Outline]]