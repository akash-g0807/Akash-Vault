# Examples of Metric Spaces
---

### Standard Metric on $\mathbb{R}$

```ad-Theorem
Title: **Standard Metric on $\mathbb{R}$**

$(\mathbb{R}, d)$ is a metric space where d is the function:
$$d: \mathbb{R} \times \mathbb{R} \rightarrow \mathbb{R}^{+}$$
defined by 
$$d(x,y) = \mid x - y \mid$$
```

`\begin{proof}`
To prove $d$ is a metric space, we need to verify properties $1-4$ from the [[General Definition of Metric Spaces|definition of metric spaces]].

1. $d(x,y) \geq 0$ by the definition of **absolute value**.
2. $d(x,y) = 0 \iff \mid x -y \mid = 0 \iff \sqrt{(x-y)^{2}}= 0 \iff (x-y)^{2}= 0 \iff x = y$
3. $d(x,y) = \mid x - y \mid = \mid y - x \mid = d(y,x)$
4. For any $x,y,z \in \mathbb{R}$
$$d(x,z) = \mid x - z \mid = \mid (x - y) + (y-z) \mid \  \leq \  \mid  (x - y) \mid + \mid  (y - z) \mid \  = \ d(x,y) + d(y,z)$$
`\end{proof}`

---
## More examples on $\mathbb{R}^n$
We can generalize metric spaces to $\mathbb{R}^n$ 
### Euclidean Metric on $\mathbb{R}^n$

```ad-Theorem

Title: **Euclidean Metric on $\mathbb{R}^n$**

Let $\mathbb{R}^{n} = \{x = (x_{1}, x_{2}, \ldots x_{n}) \mid x_{i}\in \mathbb{R}, 1 \leq i \leq n \}$ be the set of $n$ real tuples.

For $x = (x_1, x_2, \ldots x_n)$ and $y = (y_{1}, y_{2}, \ldots y_{n}) \in \mathbb{R}^n$, define the following distance function:

$$d(x,y) = \Big(\sum\limits_{i=1}^{n}(x_{i} - y_{i})^{2} \Big)^{1/2}$$

Then $(\mathbb{R}^{n},d)$ is a metric space
```

`\begin{proof}`
It is easy to verify properties 1-3. So we need only to check the [[General Definition of Metric Spaces#^eb87d4|triangle inequality]] i.e. if $z = (z_{1}, \ldots \ z_{n})$, we must show that $d(x,z) = d(x,y) + d(y,z)$. 

For $k = 1 , \ldots , n$, set 
$$a_{k}= x_{k}- z_{k,}\ \ \ \ \ \ \ \ \ \ \ \ \ b_{k}= z_{k}- y_k$$
Then
$$d(x,z) = \Big(\sum\limits_{k=1}^{n}a_{k}^{2}\Big)^{\frac{1}{2}} \ \ \ \ \ \ \ \ \ \ \ d(y,z) = \Big(\sum\limits_{k=1}^{n} b_k^2 \Big)^{1/2}$$
We must show that

$$\Big(\sum\limits_{k=1}^{n}(a_{k}+ b_k)^{2 \Big)^{\frac{1}{2}}}\leq \Big(\sum\limits_{k=1}^{3}a_k^2 \Big)^{1/2} + \Big(\sum\limits_{k=1}^{3}b_k^2\Big)^\frac{1}{2}\tag{$*$}$$ ^ef04fd

Squaring both sides of the [[#^ef04fd|$(*)$]] and using the equality

$$(a + b)^{2}= a^{2}+ b^{2} + 2ab $$
We see that [[#^ef04fd|$(*)$]] is equivalent to 
$$\sum\limits_{k=1}^{n}a_kb_{k} \leq \Big(\sum\limits_{k=1}^{n}a_k^{2} \Big)^{\frac{1}{2}} \ \Big(\sum\limits_{k=1}^{n}b_k^{2} \Big)^{\frac{1}{2}} $$
which is just the [[Holders Inequality#^ef2d0d| Caunchy-Schwartz Inequality]]. This metric is known as the **Euclidean Metric** on $\mathbb{R}^n$
`\end{proof}`
# Backlinks
---
- [[General Definition of Metric Spaces]]