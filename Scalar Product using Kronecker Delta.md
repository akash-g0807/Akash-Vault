# Scalar Product using Kronecker Delta
---
Using the definition of [[Kronecker Delta]]:

$$\begin{equation*}
\begin{aligned}
\underline{a} \ \cdot \ \underline{b} & = \Big( \sum\limits_{k = 1}^{3}a_k\underline{e_{k}} \Big)\ \cdot \ \Big( \sum\limits_{l = 1}^{3}b_l\underline{e_{l}} \Big)\\ \\
& = \sum_{k, \ l} a_{k} \ b_{l} \ \underline{e_{k}}\ \cdot \ \underline{e_{l}} \\ \\
& = \sum_{k, \ l} a_{k} \ b_{l} \ \delta_{kl}

\end{aligned}
\end{equation*}$$
As shown before, the [[Kronecker Delta]] is 0 for all cases except when $k = l$. where it has a value of **1** So the summation becomes: 

$$\underline{a} \ \cdot \underline{b} =\sum_{k=1}^{3} a_{k} \ b_{k}$$
### Einstein Notation
Using [[Einstein's Notation]] we can supress the sum:

$$\underline{{a}} \cdot \underline{b} \ = \ \sum_{k = 1}^{3} \space{a_{k}} \ b_{k}= a_kb_k$$

# Backlinks
---
- [[Scalar Product]]