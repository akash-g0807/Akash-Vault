# Reparameterization in Line Integrals
---

Seeing what happens when we [[Parametric Curves|reparametrize]] the $\underline{p}$ to compute the [[General Definition of Line Integrals|line integral]]:

Let $t = h(\tau)$. $h$ is a function:
$$h:[a^{'},b^{'}] \rightarrow [a , b]$$
such that $\dot{h} > 0$, i,e, $h$ is an **increasing function**. Furthermore, define the [[Parametric Curves#^2f90b6|reparametrization]] $\underline{q}$ by
$$\underline{q}(\tau) = \underline{p}\circ h = \underline{p}(h(\tau))$$
Therefore using the [[Reparameterization in Line Integrals|parametric formula]] for line integrals:
$$\begin{aligned}\int_{C} \underline{g}(\underline{x})\cdot d\underline{x} &= \int_{a}^{b}\underline{g}(\underline{p}(t))\cdot \underline{\dot{p}}(t) \ dt  \\ \\
&= \int_{a^{'}}^{b^{'}}\underline{g}(\underbrace{\underline{p}[h(\tau)]}_{\underline{q}(\tau)}) \cdot \underbrace{\underline{\dot{p}}(h(\tau))\ \dot{h}(\tau)}_{\underline{\dot{q}}(\tau)} \ d\tau \\ \\
&= \int_{a^{'}}^{b^{'}}\underline{g}(\underline{q}(\tau)) \cdot \underline{\dot{q}}(\tau) \ d\tau\end{aligned}$$
This shows that even if you reparametrize the curve, the **line integral remains the same**.

# Backlinks
---
- [[Line Integral using Parametrization]]
- [[Line Integrals]]
- [[Vector & Complex Calculus - MAT00047I Outline]]