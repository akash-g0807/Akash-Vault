# Holders Inequality
---

```ad-Theorem
Title: **Holders Inequality**

Let $x_{i} \geq 0$ and $y_{i}\geq 0$ for $1,2,\ldots , n$ and suppose that $p > 1$ and $q > 1$ are such that $\frac{1}{p}$ and $\frac{1}{q} = 1$. Then:


$$\sum\limits^{n}_{i=1}x_{i} \ y_{i} \ \leq \ \Big(\sum\limits_{i=1}^{n}x_{i}^{p}\Big)^{\frac{1}{p}} \ \Big(\sum\limits_{i=1}^{n}y_{i}^{q}\Big)^{\frac{1}{q}} \tag{$*$}$$
```

^1abf8b

 `\begin{proof}`
 We need consider only the case when $\sum\limits_{i=1}^{n}x_{i}^{p} \neq 0 \neq \sum\limits_{i=1}^{n}y_{i}^{p}$.  In this proof we use [[Young's Inequality]]. 
 Using different notation, let

$$\mid \mid x \mid \mid_{p}=  \Big(\sum\limits_{i=1}^{n}x_{i}^{p}\Big)^{\frac{1}{p}} \ \ \ \ \ \ \ \ \mid \mid y \mid \mid_{p}=  \Big(\sum\limits_{i=1}^{n}y_{i}^{q}\Big)^{\frac{1}{q}}$$

 First we start by rearranging [[#^1abf8b|$(*)$]] into an equivalent form below:

$$\frac{1}{\mid\mid x \mid \mid_{p}\cdot \mid\mid y \mid \mid_{q}}\sum\limits_{i = 1}^{n}x_iy_i \  \
\leq 1  \tag{1}$$

^f157e4
And proving [[#^f157e4|$(1)$]] is equivalent to proving [[#^1abf8b|$(*)$]].  Therefore

$$\begin{aligned}\frac{1}{\mid\mid x \mid \mid_{p}\cdot \mid\mid y \mid \mid_{q}}\sum\limits_{i = 1}^{n}x_iy_{i} \   &= \ \sum\limits_{i = 1}^{n}\frac{x_{i}}{\mid\mid x \mid\mid_p}\frac{y_{i}}{\mid\mid y \mid\mid_{q}}\\ \\ 
& \leq \sum\limits_{i = 1}^{n}\frac{1}{p}\frac{x_{i}^{p}}{\mid\mid x \mid\mid_{p}^{p}} \  + \  \sum\limits_{i = 1}^{n}\frac{1}{q}\frac{y_{i}^q}{\mid\mid y \mid\mid_{q}^{q}} \ \ \ \ \ \ \ \ \ \ \text{by Youngs Inequality} \\ \\ 
&= \frac{1}{p}\Big(\sum\limits_{i = 1}^{n}{x_{i}^{p}}\Big){\mid\mid x \mid\mid_{p}^{p}} \ \ + \ \ \frac{1}{q}\Big(\sum\limits_{i = 1}^{n}{y_{i}^{q}}\Big){\mid\mid y \mid\mid_{q}^{q}}  \\ \\ &= \frac{1}{p} + \frac{1}{q} \\ \\ &= 1\end{aligned}$$

Which proves the theorem.
 `\end{proof}`

---
### Cauchy-Schwartz Inequality

^ef2d0d

In the special case $p = q = 2$, in equation [[#^1abf8b|$(*)$]] we get the **Cauchy Schwartz Inequality**.

```ad-Lemma
Title: **Cauchy-Schwarts Inequality**

$$\sum\limits^{n}_{i=1}x_{i} \ y_{i} \ \leq \ \Big(\sum\limits_{i=1}^{n}x_{i}^{2}\Big)^{\frac{1}{2}} \ \Big(\sum\limits_{i=1}^{n}y_{i}^{2}\Big)^{\frac{1}{2}}$$
```

