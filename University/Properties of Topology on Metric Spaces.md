# Properties of Topology on Metric Spaces $\boldsymbol{T_d}$
---
> [!note]+ T1) **Closed** under **Arbitrary** Unions 
> Take *any* collection of [[Open and Closed Sets|open sets]] say
> $$\Lambda\subseteq T_{d}$$
> where $T_{d}$ is the [[Topology on Metric Spaces]]. Then, **union** of **open sets** in $\Lambda$ is **open**, i.e.
> *For any* $\Lambda \in T_d$, 
> $$\bigcup_{\Omega \in \Lambda}\Omega \in T_d$$
>is **open**

`\begin{proof}`
Take any 
$$x \in \bigcup_{\Omega \in \Lambda} \Omega$$
Then
$$\exists \ \Omega(x) \ni x \ \ \ \ \ \ \ \ \text{AND }\ \ \ \ \ \ \ \ \ \Omega \ \text{ is an open set}$$

And therefore by definition of [[Open and Closed Sets|open]],
$$\exists \varepsilon(x) > 0 \ \text{ such that } \ B(x, \varepsilon) \in \Omega$$ and hence
$$\begin{aligned} B(x, \varepsilon) \subseteq \Omega \ \ \ \ \ \text{AND}  \ \ \ \ \  \Omega \subseteq 
\bigcup_{\Omega \in \Lambda}\end{aligned}$$
Then by **Transitivity of subsets**
$$B(x, \varepsilon) \subseteq \bigcup_{\Omega \in \Lambda}$$
and by definition [[Describing Open Sets using Interior Points]], it is true
`\end{proof}`

---
> [!Note] T2) **Closed** under **Finite** collections of open sets
> Take **any finite** collection of [[Open and Closed Sets|open sets]]
> $$\Omega_{1}, \ldots \Omega_{N}$$
> Then,
> $$\bigcap_{i=1}^{N}\Omega_{i}$$
> is [[Open and Closed Sets|open]]

`\begin{proof}`
1. **CASE 1:** If $\bigcup_{i=1}^{N}\Omega_{i} = \emptyset$, then as $\emptyset \in T_d$, it is **open**
2. **CASE 2:** If not empty:
Take any
$$x \in \bigcap_{i=1}^{N}\Omega_{i}$$
Then since $\Omega_i$ is [[Describing Open Sets using Interior Points|open]],
$$\exists \varepsilon_{i} > 0 \ \ \ \ \text{for which} \ \ \ \ B(x, \varepsilon) \subseteq \Omega_{i}$$
Take $\displaystyle \varepsilon = \min\{\varepsilon_{1} , \ldots ,\varepsilon_{n} \}$, then
$$\begin{aligned}  B(x, \varepsilon) &\subseteq B(x, \varepsilon_{i}) \ \ \ \ \forall i \in \{1, \ldots ,n\} \\ \\ \Rightarrow B(x,\varepsilon) \subseteq \bigcap_{i=1}^{N}\Omega \end{aligned}$$
`\end{proof}`
*Note*: This property **ONLY** works for **FINITE** collections of **intersections** of sets

# Backlinks
---
- [[Topology on Metric Spaces]]
- [[Metric Spaces - MAT00037H Outline]]