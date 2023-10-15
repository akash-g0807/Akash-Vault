# Gravitational Potential Near Earth
---
As shown before, the [[Gravitational Force|gravitational force near the earth]] is:
$$\underline{F} = -mg\underline{k}$$
And therefore we can derive the following:
$$\begin{aligned} -mg\underline{k} &= \Big(\underline{i}\frac{\partial}{\partial x} + \underline{j}\frac{\partial}{\partial y} + \underline{k}\frac{\partial}{\partial z} \Big)(-mgz) \\ \\
&= -\underline{\nabla}(mgz)\end{aligned}$$
Therefore we can define the following:

```ad-Definition

Title: **Gravitational Potential Near Earth**

The gravitational [[Potential|potential]] near the earth can be defined as:
$$\Phi = mgz$$
```

### Calculating Velocity
---
> [!question] 
> A particle is dropped from rest at a height $z=h$. 
> Calculate the velocity

*Solution*: Note at height $z=h$, body at **rest** so
$$E = K + \Phi = \frac{1}{2}m\mid\underline{0} \mid^{2} + mgh = mgh$$
At height $z = 0$, height is 0 so
$$E = K + \Phi = \frac{1}{2}m\mid\underline{\dot{r}}\mid^{2} + mg0 = \frac{1}{2}m\mid\underline{\dot{r}}\mid^{2}$$
Since [[Potential and Conservation|Energy is a constant]], we get that:
$$\begin{aligned} mgh = \frac{1}{2}m\mid\underline{\dot{r}}\mid^{2} &\Rightarrow 2gh = \mid \underline{\dot{r}}\mid^{2} \\ \\
&\Rightarrow \mid \underline{\dot{r}} \mid = \sqrt{2gh} \end{aligned}$$

# Backlinks
---
- [[Examples of Force in a potential]]
- [[Potential and Conservation]]
- [[Energy]]