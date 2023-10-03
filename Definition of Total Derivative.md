# Definition of Total Derivative
---

```ad-Definition
Title: **Total Derivative**

The (**total**) **derivatve** or **Jacobian Matrix** of
$$f: \mathbb{R}^{\ n} \rightarrow {R}^{\ m}$$
is the $m \times n$ matrix made up of the partial derivatives of the components:

$$D\underline{f}(\underline{x}) := \begin{pmatrix}\frac{\partial f_{1}}{\partial x_{1}} &  \cdots  & \frac{\partial f_{1}}{\partial x_{n}} \\ 
\vdots  & \ddots  & \vdots  \\ 
\frac{\partial f_{m}}{\partial x_{1}} & \ldots  & \frac{\partial f_{m}}{\partial x_{n}}\end{pmatrix}$$

$\text{D}\underline{f}(\underline{x}) := \frac{\partial f}{\partial x_{a}}$ will *denote* the **ath column** of $D\underline{f}\underline{x}$
```

^273066

*Remark*: The jacobian matrix *may* not exist.  When talking about the derivative of the function, it is implicitly assumed to exist. If it *does* exist, then this is a function:
$$D\underline{f}: \mathbb{R}^{n}\rightarrow \mathbb{R}^{mn}$$
#### Extra properties of Jacobian Matrix
- This also **describes** how $\underline{f}$ changes when it's argument changes slightly:
$$x \approx a \Rightarrow \underline{f}(\underline{x}) -\underline{f}(\underline{a}) \approx D\underline{f}(\underline{a})(\underline{x} - \underline{a})$$
where we are using matrix multiplication

-  We can take **derivatives of the derivative**, For example $D^{2}\underline{f}$ contains all second order partial derivatives of $\underline{f}$.

# Backlinks
---
- [[Derivatives]]