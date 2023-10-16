# Total Force in a Collection of Particles
---

In a discrete system of $N$ [[Newtonian Mechanics|particles]], of mass $m_{i}$ and positions $\underline{r_{i}}(t)$,  *relative* to a chosen origin $O$. The [[Newtonian Mechanics#^36eaf6|particle]] $i$ experiences *two* types of forces:
1. **External Forces**: $\displaystyle \underline{F_{i}}^{\text{ext}}$  such that $i \in \{1, \ldots N\}$
2. **Inter-particle Forces**: That is the force due to each other.  $\displaystyle \underline{F}_{ij}$

Hence from [[Newton's Laws of Motion|Newton's Second Law]], the [[Newton's Equation of Motion|equation of motion]]/force on **particle $i$** will be:
>[!ssummary]  Collection of Particles
>$$\underline{F}_{i} = m\underline{\ddot{r}_{i}} = \sum\limits_{j=1}^{N}\underline{F_{ij}} + \underline{F_{i}}^{\text{ext}} \tag{$*$} $$
>for particles $i \in \{i, \ldots N\}$
>

^96c323

*Note*: Note the particle '$i$ ' does **not** feel a *self-force* so $\underline{F_{ii}}$ = 0.

Due to [[Newton's Laws of Motion#^570cd9|Newton's Third Law]], 
$$F_{ij} = -F_{ji}$$
and hence summing on index $i$, Equation [[#^96c323|$(*)$]], 
$$\begin{aligned} \sum\limits_{i=1}^{N} m\underline{\ddot{r}_{i}} &= \underbrace{\sum\limits_{i,j = 1}^{N}\underline{F_{ij}}}_{0 \text{ because } F_{ij} = -F_{ji}} + \sum\limits_{i = 1}^{N}\underline{F_{i}}^{\text{ext}}  \\ \\
&= 0 + \sum\limits_{i=1}^{N}\underline{F_{i}}^{\text{ext}} \end{aligned}$$
And hence we get:
>[!note]  Total Force in a collection of particles
>In a discrete system of $N$ particles, **total** force is:
>$$\underline{F^{\text{ext}}_{\text{total} }} = \sum\limits_{i=1}^{N} m\underline{\ddot{r}_{i}} =\sum\limits_{i=1}^{N}\underline{F_{i}}^{\text{ext}} $$
>that is the **sum of all external forces**
 
# Backlinks
---
- [[Collection of Particles]]
- [[Newtonian Mechanics]]