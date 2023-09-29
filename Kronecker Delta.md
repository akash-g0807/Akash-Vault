# Kronecker Delta
---

Note that by properties of the [[Scalar Product|scalar product]], the [[Orthonormal Basis for Vectors|orthonormal basis vectors]]: have the following properties:
$$\underline{e_{1}} \cdot \underline{e_{2}}= 0 = \underline{e_{1}} \cdot \underline{e_{3}} = \underline{e_{2}} \cdot \underline{e_{3}}$$
and
$$\underline{e_{1}} \cdot \underline{e_{1}}= 1 = \underline{e_{2}} \cdot \underline{e_{2}} = \underline{e_{3}} \cdot \underline{e_{3}}$$
We can abbreviate it using the **Kronecker Delta**: (Note that is is a [[Scalar Product|scalar product]])

```ad-Definition
TItle: **Kronecker Delta**

Let $a,b \in {1,2,3}$. Then we can write:

$$\underline{e_{a}}\cdot \underline{e_{b}}
= \begin{cases}
1 & \text{if} \space \space a = b = 1,2,3\\ \\
0 & \text{if} \space \space a \neq b
\end{cases}\\$$
$\displaystyle \hspace{370px} = \boldsymbol{\delta_{ab}}$
```

*Note*: The Kronecker Delta can be thought of as a **unit matrix**. As the values where the value is $1$,  $a = b$ which are the diagonals of a matrix and it is 0 everywhere else
$$\delta_{ab} = \begin{pmatrix}1 & 0 & 0 \\ 0 & 1 & 0 \\ 0 & 0 & 1 \end{pmatrix}$$

## Further Notes on Kronecker Delta
---
- [[Properties of Kronecker-Delta and Levi-Civita]]