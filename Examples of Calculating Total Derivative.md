# Examples of Calculating Total Derivative
---

> [!math|{"type":"example","number":"auto","setAsNoteMathLink":false,"_index":0}] Example 1.
> For 
> $$\begin{aligned} \underline{f}(r, \theta) = (r\cos\theta, \ r\sin\theta) \\ \\
> \hspace{-1000px} g(x,y) = x^{2} + y^{3}\end{aligned}$$
> compute $D(g \circ \underline{f})$ using the [[Properties of  Total Derivative#^7226d1|chain rule]] and directly

*Solution:* Using the definition of [[Definition of Total Derivative#^273066|total derivative]]
$$\begin{aligned} D\underline{f}(r, \theta) = \begin{pmatrix}\cos\theta & -r\sin\theta  \\ \sin \theta & r\cos\theta\end{pmatrix} \\ \\
Dg(x,y) = (2x\ \ \  2y) \ \ \ \ \ \ \ \ \ \\ \\
\hspace{-100px} Dg(\underline{f}(r, \theta))\ D\underline{f}(r,\theta) &= Dg((r\cos\theta, \ r\sin\theta))\ D\underline{f}(r, \theta) \\ \\
&= (2r\cos\theta \ \ \ 2r\sin\theta)\begin{pmatrix}\cos\theta & -r\sin\theta \\ \sin\theta & r\cos\theta \end{pmatrix} \\ \\ 
&= (2r\ \ \ \  0)\end{aligned}$$
Calculating *directly* from the composition, the composition is
$$(g \circ \underline{f})(r, \theta) = (r\cos\theta)^{2} + (r\sin\theta)^{2}= r^2$$
Therefore applying the formula for [[Definition of Total Derivative|total derivative]] directly:
$$D(g \circ \underline{f})(r, \theta) = (2r\ \ \ 0)$$