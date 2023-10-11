# Derivative of Polar Basis Vectors
---
We assume that the **angle** $\theta$ **changes with time** and therefore these basis vectors are **NOT** **constant**. We need to be careful in this co-ordinate system when doing calculus with them

### First Derivative
---
First we will compute the first derivatives $\underline{\dot{e_{r}}}$ and $\underline{\dot{e_{\theta}}}$. 
1. Computing $\underline{\dot{e_r}}$
$$\begin{aligned} \underline{\dot{e_{r}}} &= \frac{d}{dt}\Big(\underline{i}\cos\theta  + \underline{j}\sin\theta\Big) \\ \\
&= - \dot{\theta}\sin(\theta) \underline{i} + \dot{\theta}\cos(\theta)\underline{j} \\ \\
&= \dot{\theta}(-\sin(\theta)\underline{i} + \cos(\theta)\underline{j}) \\ \\
&= \dot{\theta}\ \underline{e_{\theta}} \end{aligned}$$
Therefore we get
> [!Definition] 
> $$\begin{aligned} \underline{\dot{e_{r}}} &= \dot{\theta}\ \underline{e_{\theta}}\\ \\ &= - \dot{\theta}\sin(\theta) \underline{i} + \dot{\theta}\cos(\theta)\underline{j} \end{aligned}$$

2. Computing $\underline{\dot{e_{\theta}}}$
$$\begin{aligned} \underline{\dot{e_{r}}} &= \frac{d}{dt}\Big(-\sin(\theta)\underline{i}  + \cos(\theta)\underline{j}\Big) \\ \\
&= - \dot{\theta}\cos(\theta) \underline{i} - \dot{\theta}\sin(\theta)\underline{j} \\ \\
&= -\dot{\theta}(\cos(\theta)\underline{i} + \sin(\theta)\underline{j}) \\ \\
&= \dot{\theta}\ \underline{e_{r}} \end{aligned}$$
Therefore we get
> [!Definition] 
> $$\begin{aligned} \underline{\dot{e_{\theta}}} &= -\dot{\theta}\ \underline{e_{r}}\\ \\ &= - \dot{\theta}\cos(\theta) \underline{i} - \dot{\theta}\sin(\theta)\underline{j} \end{aligned}$$

# Backlinks
---
- [[Polar Orthonormal Basis for Vectors]]
- [[Motion in Plane Polar Co-ordinates]]
- [[Newtonian Mechanics]]