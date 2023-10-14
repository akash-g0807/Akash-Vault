# Work Done
---

Consider the rate of change if [[Kinetic Energy]]

$$\begin{aligned} \dot{K} = \frac{d}{dt}\Big(K \Big) =  \underline{F} \cdot \underline{\dot{r}} = m\dot{r} \cdot\underline{{\ddot{r}}} \end{aligned}$$
And [[Definite Integral|integrating]] both sides from $t_{1}$ to $t_{2}$, we get:
$$\begin{aligned}  \int_{t_{1}}^{t_{2}} m\underline{r} \cdot \underline{\ddot{r}} dt &= \int_{t_1}^{t_2}\frac{dK}{dt}dt =K(t_{2}) - K(t_{1}) \\ \\
&= \int_{t_{1}}^{t_{2}}\underline{F} \cdot \underline{\dot{r}} \\ \\
&= \int^{P_{2}}_{P_{1}}\underline{F} \cdot d\underline{r}\end{aligned}$$
Where $P_{1}$ is the position of of particle on trajectory at $t_{1}$ and $P_{2}$ is the position of particle on $t_{2}$.
The last integral is called the [[General Definition of Line Integrals|Line Integral]] and is integrated along the trajectory.  Therefore we can define **Work Done** in the following way:
```ad-Definition

Title: **Work Done**

**Work Done** along the trajecory is defined as the *change* in Kinetic Energy $K$:
$$\int_{P_{1}}^{P_{2}}\underline{F}\cdot\underline{r} = K(t_{2}) - K(t_{1})$$

```

# Backlinks
---
- [[Energy]]
- [[Newtonian Mechanics]]