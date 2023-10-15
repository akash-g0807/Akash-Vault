# Potential and Conservation
---
Some forces have a very special property that they can be written as:
$$\underline{F} = - \underline{\nabla} \Phi$$
where $\nabla$ is the [[Gradient Operator]]. Therefore we can define the following:

```ad-Definition

Title: **Force in a potential**

Some forces are the [[Gradient Operator|gradient]] of a potential:
$$\underline{F} = - \underline{\nabla}\Phi = - \Big(\frac{\partial}{\partial x} \underline{i} + \frac{\partial}{\partial y} \underline{j} + \frac{\partial}{\partial z} \underline{k}\Big)\Phi = - \Big(\frac{\partial \Phi}{\partial x} \underline{i} + \frac{\partial \Phi}{\partial y} \underline{j} + \frac{\partial \Phi}{\partial z} \underline{k}\Big)$$
or using [[Einstein's Notation]] 
$$\underline{F} = \underline{\nabla}\Phi = \frac{\partial \Phi}{\partial x_{a}}\underline{e_{a}}$$
```

*Note*: Such forces are known as **conservative forces**

---
Now consider the following calculations:
$$\begin{aligned} \underline{F} = - \underline{\nabla}\Phi &\Rightarrow \underline{F} \cdot \underline{r} = - \underline{r} \cdot \underline{\nabla}\Phi \end{aligned}$$
Now by the definition of [[Kinetic Energy]], $\underline{F} \cdot \underline{r} = dK/dt = \dot{K}$, we get the following:
$$\begin{aligned} \frac{dK}{dt} = -\underline{\dot{r}} \cdot \underline{\nabla}\Phi &\Rightarrow  \frac{dK}{dt} = -\underline{\dot{r}}\cdot\underline{\nabla}\Phi(\underline{r}) \\ \\
&\Rightarrow \frac{dK}{dt} = -\frac{d\Phi}{dt} \ \ \ \ \ \ \ \ \ \ \ \ \ \ \text{chain rule} \\ \\
&\Rightarrow \frac{d}{dt}\Big(K + \Phi\Big) = 0\end{aligned}$$
> [!note]+ Energy
> Energy is a **constant of motion**
> $$\dot{E} = \frac{d}{dt}\Big(K + \Phi\Big) = 0$$
> Therefore
> $$E = K + \Phi = \text{CONSTANT}$$  

*Note*: $\Phi$ is known as **Potential Energy**

## Further Notes
---
- [[Examples of Force in a potential]]
- [[Inverse Square Law]]
# Backlinks
---
- [[Energy]]
- [[Newtonian Mechanics]]