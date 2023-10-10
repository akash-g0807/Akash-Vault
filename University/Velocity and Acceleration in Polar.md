# Velocity and Acceleration in Polar
---
Remember [[Polar Orthonormal Basis for Vectors|polar orthonormal basis vectors]] $e_{r}$ and $\underline{e_{\theta}}$ are **NOT constant**. Hence we need to use their [[Derivative of Polar Basis Vectors|derivatve]].
### Velocity
---
Computing **velocity** in [[The Polar Co-Ordinate System|polar co-ordinates]]:
$$\begin{aligned} \dot{\underline{r}} &= \frac{d}{dt}\Big(r \ \underline{e_{r}}\Big) \\ \\ 
&= \dot{r}\ \underline{e_{r}} + r\ \dot{\theta}\ \underline{e_{\theta}} \ \ \ \ \ \ \ \ \text{product rule} \end{aligned}$$

```ad-Definition
$$\underline{\dot{r}} = \dot{r}\ \underline{e_{r}} + r\ \dot{\theta}\ \underline{e_{\theta}}$$
```

### Acceleration
---
Computing the **acceleration** in [[The Polar Co-Ordinate System|polar co-ordinates]]:
$$\begin{aligned} \underline{\ddot{r}} &= \frac{d}{dt}\Big(\dot{r}(t)\Big) \\ \\
&= \frac{d}{dt}\Big(\dot{r}\underline{e_{r}} + r\dot{\theta}\underline{e_{\theta}} \Big) \\ \\
&= \ddot{r}\underline{e_{r}}+ \dot{r}\dot{e_{r}}+ \dot{r}\dot{\theta}\underline{e_{\theta}} + r\ddot{\theta}\underline{e_{\theta}} + r\dot{\theta}\underline{\dot{e_{\theta}}} \\ \\
&= \ddot{r}\underline{e_{r}} + \dot{r}\dot{\theta}\underline{e_{\theta}} + \dot{r}\dot{\theta}\underline{e_{\theta}} + r\ddot{\theta}\underline{e_{\theta}} - r\dot{\theta}^{2}\underline{e_{r}}  \\ \\ 
&= (\ddot{r} - r\dot{\theta}^{2})\underline{e_{r}} + (r\ddot{\theta} + 2\dot{r}\dot{\theta})\underline{e_{\theta}}\end{aligned}$$
```ad-Definition
$$\ddot{r} = (\ddot{r} - r\dot{\theta}^{2})\underline{e_{r}} + (r\ddot{\theta} + 2\dot{r}\dot{\theta})\underline{e_{\theta}}$$
```

### Cross Product
---
We can compute the [[Vector Product|cross product]] between $\underline{r}$ and $\underline{\dot{r}}$ 
$$\begin{aligned} \underline{r} \times \underline{\dot{r}} &= \underline{r} \times (\dot{r} \underline{e_{r}}+ r\dot{\theta}\underline{e_{\theta}}) \\ \\ 
&= (\underline{r} \times \dot{r}\underline{{e_{r}}}) + (\underline{r} \times r\dot{\theta}\underline{e_{\theta}}) \\ \\
&=  (r\underline{e_{r}} \times \dot{r}\underline{{e_{r}}}) + (r\underline{e_{}r} \times r\dot{\theta}\underline{e_{\theta}}) \\ \\ 
&=  r\dot{r}(\underline{e_{r}}\times \underline{e_{r}}) + r^{2}\dot{\theta}(\underline{e_{r}}+ \underline{e_{\theta}}) \\ \\
&= r^{2}\dot{\theta}\underline{k}\end{aligned}$$
*Note*: We have used the [[Properties of Vector Product|properties of cross product]] of [[Orthonormal Basis for Vectors|orthonormal basis vectors]] including [[Polar Orthonormal Basis for Vectors|properties for polar basis vectors]] 

```ad-Definition
 $$\underline{r} \times \underline{\dot{r}} =  r^{2}\dot{\theta}\underline{k}$$
```
## Further Notes
---
- [[Some Notes on Derivatives in Polar Co-Ordinates]]

# Backlinks
---
- [[Motion in Plane Polar Co-ordinates]]
- [[Newtonian Mechanics]]