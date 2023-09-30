# Triple Vector Product
---

Taking three vectors $\underline{a}, \underline{b} \text{ and } \underline{c}$, we *calculate* the **pth component** first:

$$\begin{split}
[\underline{a} \times (\underline{b} \times \underline{c})]_{p} &= \epsilon_{pqr}\ a_{q}(\underline{b} \times \underline{c})_{r} \\ \\
&= \epsilon_{pqr}\ a_{q} \ \epsilon_{ruv}\ b_{u}\ e_{v} \\ \\  
\end{split}$$
Here we use the [[Properties of Kronecker-Delta and Levi-Civita| identity]]:
$$\epsilon_{pqr}\epsilon_{ruv} = (\delta_{pu}\delta_{qv} - \delta_{pv}\delta_{qu})$$We get the following:
$$\begin{split}
[\underline{a} \times (\underline{b} \times \underline{c})]_{p} &= (\delta_{pu}\delta_{qv} - \delta_{pv}\delta_{qu})a_{q}b_{u}c_{v} \end{split}$$

Please refer to the handwritten note below for detailed simplification.

![[Triple Vector Product proof.svg]]

# Backlinks
---
- [[Vector Algebra]]