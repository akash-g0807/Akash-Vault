# Infinite Spaces
---
We are going to look at a space that has got **infinite dimensions**.

Take the set $\mathbb{R}^n$.  $\mathbb{R}^n$ is a **finite dimensional object**. 

> [!math|{"type":"remark","number":"a","setAsNoteMathLink":false,"title":"$\\mathbb{R}^{\\mathbb{N}}$","label":"mathbbrmathbbn"}] Remark a ($\mathbb{R}^{\mathbb{N}}$).
> What about set $\mathbb{R}^{\mathbb{N}}$

The set $\mathbb{R}^{\mathbb{N}}$ is the **set of all sequences with real numbers as their entries** i.e. the set of all sequences of real numbers. 

If $x \in \mathbb{R^{\mathbb{N}}}$ then $(x_{1}, x_{2}, \ldots x_{n} , \ldots )$ 

We will try and put a metric on this set using the distance function:
$$d_{1}(x,y) = \sum_{i=1}^{\infty}\mid x_{i} - y_{i}\mid$$
Using this function and trying to calculate the distance between $x$ and $0 \in \mathbb{\mathbb{N}}$ 
$$\begin{aligned} d_1(x,0) &= d_1((x_{1} , x_{2}, \ldots), (0,0,\ldots)) \\ \\
&= \sum\limits_{i=1}^{\infty}\mid x_{i} - 0 \mid \\ \\ 
&= \sum\limits_{i=1}^{\infty}\mid x_{i} \mid\end{aligned}$$
But this  series **may not** converge. Hence not a real number. The value of a metric **MUST BE A REAL POSITIVE NUMBER.** 
Therefore we define a set $\ell_1$ 

```ad-Definition

Title: **$\ell_{1}$**

$\ell_{1}$ is the set of all sequence of real numbers that satisfy

$$\sum\limits^{\infty}_{i=1}\mid x_{i} \mid < \infty \tag{$*$}$$
```

^62c158

Therefore $\ell_{1}$ , the set of all sequences satisfying [[#^62c158|$(*)$]] **AND**
$$d_{1}(x,y) = \sum\limits_{i=1}^{\infty}\mid x_{i} - y_{i} \mid $$
is a metric.

---

## Metric on $\ell_\infty$

```ad-Definition
Title: **$\ell_{\infty}$**

$\ell_{\infty}$ is the set of all bounded sequences of real numbers such that

$$\begin{aligned} x \in \ell_{\infty} \iff \exists M=M(X) > 0 \ \ \text{such that} \ \mid x_{i} \mid \leq M \ \ \forall i \in \mathbb{N} \end{aligned}$$

where $x = (x_{1}, x_{2}, \ldots , x_{n}, \ldots )$
```
 
Putting a metric on this, define the distance function $d_{\infty}$
$$d_{\infty}(x,y) = \sup\{\mid x_{i} - y_{i} \mid : i \in \mathbb{N}\}$$
*Note*: $x - y = (x_{1} - y_{1}, x_{2} - y_{2}, \ldots ) \in \ell_{\infty}$ 