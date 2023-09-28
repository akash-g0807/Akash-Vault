# Vector Product using Levi-Civita
---

### Cross product of [[Orthonormal Basis for Vectors|Orthonormal Basis Vectors]]

Using the [[Levi-Civita Symbol]] we can write the cross product of orthonormal basis vectors: $\underline{e_1},\underline{e_{2}}, \underline{e_3}$ in the following way:

$$\underline{e_{a}} \times \underline{e_b} \ = \ \sum_{c = 1}^{3}\epsilon_{abc} \space\underline{e_{k}}\tag{1} = \epsilon_{abc} \ \underline{e_{c}}$$ ^f5c033

---
### Cross Product for Vectors in Levi-Civita Notation

Let:
$$
\underline{a} = a_{k}\underline{e_{k}} = \sum_{k=1}^{3}a_{k}\ \underline{e_{k}} \hspace{100px} \underline{b} = b_{l}\underline{e_{l}}= \sum\limits_{l=1}^{3} b_{l}\ \underline{e_{l}}
$$
*Note:* Observe the use of [[Einstein's Notation]] in this and [[#^f5c033|(1)]]

Observe that:

$$\begin{equation*}
\begin{aligned}
\underline{a} \times \underline{b} & = \Big( \sum\limits_{k = 1}^{3}a_k\underline{e_{k}} \Big)\ \times \ \Big( \sum\limits_{l = 1}^{3}b_l\underline{e_{l}} \Big)\\ \\
&= \sum\limits_{k, \ l}a_{k} \ b_{k} \ \underline{e_{k}} \times \underline{e_{l}}

\end{aligned}
\end{equation*}$$

As seen by equation [[#^f5c033|(1)]]:  we can rewrite the above in the following way:
$$\hspace{-80px} = \sum\limits_{k,\ l,\ m} a_{k} \ b_{l} \ \epsilon_{klm} \ \underline{e_m}$$

Define the **mth component** as:

$$(\underline{a} \times \underline{b})_{m}= \sum\limits_{k, \ l} \epsilon_{klm} \ a_{k}\ b_l $$
And then we get the following expression:

```ad-Definition

$$\underline{a} \times \underline{b} = \sum\limits_{m=1}^{3} (\underline{a} \times \underline{b})_{m} \underline{e_{m}}  \tag{2}$$

```

^c2a28d

### Einstein Notation for Levi- Civita Cross Product

Using [[Einstein's Notation]] we can supress the sum:

$$(\underline{a} \times \underline{b})_{m}= \sum\limits_{k, \ l} \epsilon_{klm} \ a_{k}\ b_{l }= \epsilon_{klm}a_kb_k$$
And using this expression, we can rewrite [[#^c2a28d|(2)]]:
$$(\underline{a} \times\underline{b}) = \sum\limits_{m=1}^{3} (\underline{a} \times \underline{b})_{m} \underline{e_{m}} = \sum\limits_{m=1}^{3}\epsilon_{klm} \ a_kb_{k} \ \underline{e_{m}}= \epsilon_{klm} \ a_kb_{k} \ \underline{e_{m}}$$

(*Note:* he last equality supressed the **sum over m** using [[Einstein's Notation]])