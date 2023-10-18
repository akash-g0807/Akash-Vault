# Example Calculating Interior, Exterior and Boundary
---

> [!question] 
> Calculate $A^{o}$, $\partial A$, $A^{e}$ where $A$ is the set
> $$A = (0,1] \subset \mathbb{R}$$
> and $d(x,y) = \mid x - y \mid$ 

*Solution*:
Consider the following pictorial diagram of $A$:
```tikz
\begin{document}

\tikzset{every picture/.style={line width=0.75pt}} %set default line width to 0.75pt        

\begin{tikzpicture}[x=0.75pt,y=0.75pt,yscale=-1,xscale=1]
%uncomment if require: \path (0,402); %set diagram left start at 0, and has height of 402

%Straight Lines [id:da5648422329864683] 
\draw    (217.2,206.75) -- (392.2,206.75) ;
%Shape: Circle [id:dp33170233725792997] 
\draw   (255.8,206.4) .. controls (255.8,204.63) and (257.23,203.2) .. (259,203.2) .. controls (260.77,203.2) and (262.2,204.63) .. (262.2,206.4) .. controls (262.2,208.17) and (260.77,209.6) .. (259,209.6) .. controls (257.23,209.6) and (255.8,208.17) .. (255.8,206.4) -- cycle ;
%Shape: Circle [id:dp50206201922898] 
\draw  [fill={rgb, 255:red, 0; green, 0; blue, 0 }  ,fill opacity=1 ] (345.8,206.4) .. controls (345.8,204.63) and (347.23,203.2) .. (349,203.2) .. controls (350.77,203.2) and (352.2,204.63) .. (352.2,206.4) .. controls (352.2,208.17) and (350.77,209.6) .. (349,209.6) .. controls (347.23,209.6) and (345.8,208.17) .. (345.8,206.4) -- cycle ;
%Curve Lines [id:da0894859445248567] 
\draw    (269.2,178.18) .. controls (253.2,193.18) and (257.2,219.18) .. (269.2,229.18) ;
%Straight Lines [id:da8428101849900285] 
\draw    (349,180.4) -- (349,232.4) ;
%Straight Lines [id:da7914068524732535] 
\draw    (349,180.4) -- (340.2,180.17) ;
%Straight Lines [id:da40705618982316816] 
\draw    (349,232.4) -- (340.2,232.17) ;

% Text Node
\draw (239.8,204.4) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle 0$};
% Text Node
\draw (352.2,206.4) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle 1$};

\end{tikzpicture}
\end{document}
```
From the following diagram, we can deduce the following which we will **need** to **prove**
- The [[Interior and Exterior and Boundary Points#^263809|interior]] $A^{o} = (0,1)$
- The [[Interior and Exterior and Boundary Points#^9381fb|exterior]] $A^{e} = (-\infty, 0) \cup (1, \infty)$
- The [[Interior and Exterior and Boundary Points#^72c666|boundary]] $\partial A = \{0,1\}$

> [!math|{"type":"claim","number":"auto","setAsNoteMathLink":false,"_index":0}] Claim 1.
> $$A^{o} = (0,1)$$

`\begin{proof}`
Take $x \in (0,1)$, then $0 < x < 1$. 
```tikz
\begin{document}



\tikzset{every picture/.style={line width=0.75pt}} %set default line width to 0.75pt        

\begin{tikzpicture}[x=0.75pt,y=0.75pt,yscale=-1,xscale=1]
%uncomment if require: \path (0,402); %set diagram left start at 0, and has height of 402

%Straight Lines [id:da5648422329864683] 
\draw    (220.2,205.75) -- (395.2,205.75) ;
%Curve Lines [id:da0894859445248567] 
\draw    (224.2,193.63) .. controls (219.2,198.63) and (218.2,210.63) .. (224.2,216.63) ;
%Curve Lines [id:da11612929956419205] 
\draw    (391.2,193.63) .. controls (397.2,201.63) and (396.2,211.63) .. (391.2,217.18) ;
%Straight Lines [id:da3156687012442382] 
\draw    (280.2,196.63) -- (280.2,213.63) ;
%Straight Lines [id:da47301842069050437] 
\draw    (222,224) -- (278.2,223.95) ;
\draw [shift={(280.2,223.95)}, rotate = 179.95] [color={rgb, 255:red, 0; green, 0; blue, 0 }  ][line width=0.75]    (10.93,-3.29) .. controls (6.95,-1.4) and (3.31,-0.3) .. (0,0) .. controls (3.31,0.3) and (6.95,1.4) .. (10.93,3.29)   ;
\draw [shift={(220,224)}, rotate = 359.95] [color={rgb, 255:red, 0; green, 0; blue, 0 }  ][line width=0.75]    (10.93,-3.29) .. controls (6.95,-1.4) and (3.31,-0.3) .. (0,0) .. controls (3.31,0.3) and (6.95,1.4) .. (10.93,3.29)   ;
%Straight Lines [id:da8573888067415902] 
\draw    (393.2,224.42) -- (282.2,223.96) ;
\draw [shift={(280.2,223.95)}, rotate = 0.24] [color={rgb, 255:red, 0; green, 0; blue, 0 }  ][line width=0.75]    (10.93,-3.29) .. controls (6.95,-1.4) and (3.31,-0.3) .. (0,0) .. controls (3.31,0.3) and (6.95,1.4) .. (10.93,3.29)   ;
\draw [shift={(395.2,224.43)}, rotate = 180.24] [color={rgb, 255:red, 0; green, 0; blue, 0 }  ][line width=0.75]    (10.93,-3.29) .. controls (6.95,-1.4) and (3.31,-0.3) .. (0,0) .. controls (3.31,0.3) and (6.95,1.4) .. (10.93,3.29)   ;

% Text Node
\draw (205.8,205.4) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle 0$};
% Text Node
\draw (395.2,205.75) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle 1$};
% Text Node
\draw (274.2,174.63) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle x$};
% Text Node
\draw (242,225) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle \epsilon $};
% Text Node
\draw (320,224) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle 1-\epsilon $};


\end{tikzpicture}

\end{document}
```
Let $\epsilon = x - 0$, $\epsilon^{'} = 1-x$, and take $\epsilon^{*} = \min\{\epsilon, \epsilon^{'}\}$. 

Consider the [[Open and Closed Balls|Open Ball]] 
$$B(x,\epsilon^{*}/2)$$
Consider the point $y \in B(x, \epsilon^{*}/ 2)$. Then we get
$$\begin{align*} y \in B(x, \epsilon^{*}/{ 2})  &\Rightarrow \mid y-x \mid < \frac{\epsilon^{*}}{2} \\ \\
&\Rightarrow \frac{e^{*}}{2} < y - x < \frac{e^{*}}{2} \\ \\
&\Rightarrow x - \frac{e^{*}}{2} < y < x + \frac{e^{*}}{2} \tag{1}
\end{align*}$$

^cd071c

Now since $\epsilon = x - 0$ and $\epsilon^{*} = \min\{e, e^{'}\} \Rightarrow \epsilon^{*} \leq \epsilon$, we get that
$$\begin{align*} x - 0 = \epsilon &\Rightarrow x - \epsilon = 0 \\ \\
&\Rightarrow x -  \epsilon^{*} \geq 0  \\ \\
&\Rightarrow x - \frac{\epsilon^{*}}{2} \geq 0\end{align*}$$
Similarly since $\epsilon^{'} = 1-x$ and $\epsilon^{*} = \min\{\epsilon, \epsilon^{'}\} \Rightarrow e^{*} \leq \epsilon^{'}$, we get
$$\begin{align*} \epsilon^{'} = 1- x &\Rightarrow 1 = \epsilon^{'} + x\\ \\
 &\Rightarrow 1 \geq e^{*} + x \\ \\
&\Rightarrow 1 \geq \frac{\epsilon^{*}}{2} + x \end{align*}$$
And combining the results with [[#^cd071c|$(1)$]], we get that
$$0 \leq x - \frac{e^{*}}{2} < y < x + \frac{e^{*}}{2} \leq 1$$
And therefore **all points** $y \in B(x, \epsilon^{*}/2)$ is an element of $A$, i.e.
$$B(x,\epsilon^{*}/2) \subset A$$
Since by the definition of an [[Interior and Exterior and Boundary Points|interior point]], the definition *implies* that the **interior point MUST belong to the set**. Since points $x<0$  and $x > 1$ lie outside the set, they are **not** interior points.

Further $1 \in A$ is **NOT** an interior point as take $\epsilon > 0$ and [[Open and Closed Balls|Open Ball]] $B(1,\epsilon)$. This contains a point
$$\begin{aligned} y \in B(1, \epsilon) \Rightarrow y > 1 &\Rightarrow y \notin A  \\ \\
&\Rightarrow B(1,\epsilon) \not\subset A\end{aligned}$$
And hence 1 is **NOT an interior point**. Therefore
$$A^{o} = (0,1)$$`\end{proof}`

Now we prove for boundary points
> [!math|{"type":"claim","number":"auto","setAsNoteMathLink":false,"_index":1}] Claim 2.
> $$\partial A = \{0,1\}$$

`\begin{proof}`
Take any $\epsilon > 0$.  And consider $B(0,\epsilon) = (-\epsilon, \epsilon)$.  Take $\delta > 0$ such that
$$\delta < \epsilon \ \ \ \text{and} \ \ \ \delta < 1$$
And therefore we can construct any $y = 0 + \delta \in A$ and therefore $B(0,\epsilon) \cap A \neq \emptyset$.  

Similarly we can show that there exist $y \in B(0,\epsilon)$ for which $y < 0$, so $B(0,e) \cap A^{c} \neq \emptyset$ namely $y = 0-\delta$ such that $\delta < \epsilon$ and $\delta < 1$. 

Now we must show that there are **no** other [[Interior and Exterior and Boundary Points|boundary]]. By the [[Disjoint Union Property for Interior, Exterior and Boundary Points|disjoint union property]], 
$$\partial A \cap A^{o} = \emptyset$$
No point in $A^{o} = (0,1)$ is a boundary point. 
Now consider the point $y >1$. Then $\exists \epsilon > 0$ such that $y= 1 + \epsilon$. And then take the [[Open and Closed Balls|open ball]] *say* $B(y, \epsilon/10)$.
Since $\epsilon/10< \epsilon$ , the open ball $B(y,\epsilon/10)$ **will not intersect** $A$ since it is *more* than $\epsilon/10$ away from boundary 1.  Therefore
$$B(y,{\epsilon}/10 \subset A^{c})$$
A similar argument for points $y < 0$

`\end{proof}`
Now for the proof for exterior points:
> [!math|{"type":"claim","number":"auto","setAsNoteMathLink":false,"_index":2}] Claim 3.
> $$A^{e} = A^{e} = (-\infty, 0) \cup (1, \infty)$$

`\begin{proof}`
By the [[Disjoint Union Property for Interior, Exterior and Boundary Points|disjoint union property]], 
$$\begin{aligned} & \partial A \cup A^{o} \cup A^{e} = X \\ \\
& \partial A \cap A^{o} = \emptyset \\ \\
& A^{o} \cap A^{e} = \emptyset \\ \\
& \partial A \cap A^{e} = \emptyset\end{aligned}$$
Then
$$\begin{align*} A^{e} &= \mathbb{R} \setminus (A^{o} \cup \partial A) = A^{e} = A^{e} = (-\infty, 0) \cup (1, \infty) \end{align*}$$
`\end{proof}`
# Backlinks
---
- [[Interior and Exterior and Boundary Points]]
- [[The (basic) Geometry of Metric Spaces]]