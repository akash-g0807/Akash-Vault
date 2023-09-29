# Triple Scalar Product
---

We need to find the triple scalar product of vectors $\underline{a}, \underline{b}, \underline{c}$. 

$$\begin{aligned} \underline{a} \ \cdot \ (\underline{b} \times \underline{c}) &= a_{p}\ (\underline{b} \times \underline{c})_{p} \\ \\ &= a_{p}\ \epsilon_{pqr}\ b_{q}\ c_{r}\\ \\ 
&= \epsilon_{pqr}\ a_{p}\ b_{q}\ c_{r}\end{aligned}$$
*Note*: We have used [[Einstein's Notation]] for [[Scalar Product]] and [[Vector Product]] as well as [[Levi-Civita Symbol]] notation

> [!math|{"type":"definition","number":"","setAsNoteMathLink":false,"title":"Triple Scalar Product","label":"triple-scalar-product"}] Definition (Triple Scalar Product).
>  $$\underline{a} \ \cdot \ (\underline{b} \times \underline{c}) = \epsilon_{pqr}\ a_{p}\ b_{q}\ c_{r}$$

### Using determinant method

*Note:* This is **not** mathematically valid, this is just an abuse of notation.

We can also get the same formula as the above using **determinant** of matrices.

$$\underline{a} \cdot(\underline{b} \times \underline{c}) = 
\det\begin{pmatrix}a_1 & a_2 & a_3 \\ b_{1} & b_{2} & b_{3} \\ c_{1}  & c_{2} & c_{3}\end{pmatrix}$$