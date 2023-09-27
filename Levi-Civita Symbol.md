# Levi-Civita Symbol
---

We can represent cross product using a new symbol called **Levi-Civita symbol**

```ad-Definition
Title: **Levi-Civita Symbol**


Let $a, b, c \in {1,2,3}$. Then we write:

$$\epsilon_{abc} = 
\begin{cases} 
0 & \text{if} \space a = b = c  \space \space \text{or more generally} \space a,b,c \space \text{is {\bf not} permutation of} \space 1,2,3  \\ \\
+1  & \text{if} \space a,b,c \space \text{is an {\bf even} permuation of} \space 1,2,3 \\ \\
-1  & \text{if} \space a,b,c \space \text{is an {\bf odd} permuation of} \space 1,2,3
\end{cases}$$

```

*Note*: The value of $\epsilon_{abc}$ depends on the **parity** of the [[Permuation|permutation]]

### Cross product of [[Orthonormal Basis for Vectors|Orthonormal Basis Vectors]]

Then we can write the cross product of orthonormal Basis Vectors: $\underline{e_1},\underline{e_{2}}, \underline{e_3}$ in the following way:
$$\underline{e_{a}} \times \underline{e_b} \ = \ \sum_{c = 1}^{3}\epsilon_{abc} \space\underline{e_k}$$
