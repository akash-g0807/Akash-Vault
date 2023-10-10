# Orthogonal Vectors
---

Suppose we have 2 vectors $\underline{u}$ and $\underline{v}$ such that they are **orthogonal**. 

```tikz
\begin{document}

\tikzset{every picture/.style={line width=0.75pt}} %set default line width to 0.75pt        

\begin{tikzpicture}[x=0.75pt,y=0.75pt,yscale=-1,xscale=1]
%uncomment if require: \path (0,402); %set diagram left start at 0, and has height of 402

%Straight Lines [id:da6610018448935195] 
\draw    (369.55,153.98) -- (482.96,93.99) ;
\draw [shift={(484.73,93.06)}, rotate = 152.12] [color={rgb, 255:red, 0; green, 0; blue, 0 }  ][line width=0.75]    (10.93,-3.29) .. controls (6.95,-1.4) and (3.31,-0.3) .. (0,0) .. controls (3.31,0.3) and (6.95,1.4) .. (10.93,3.29)   ;
%Straight Lines [id:da5998289006037557] 
\draw    (369.55,153.98) -- (433.48,275.26) ;
\draw [shift={(434.42,277.03)}, rotate = 242.2] [color={rgb, 255:red, 0; green, 0; blue, 0 }  ][line width=0.75]    (10.93,-3.29) .. controls (6.95,-1.4) and (3.31,-0.3) .. (0,0) .. controls (3.31,0.3) and (6.95,1.4) .. (10.93,3.29)   ;
%Shape: Right Angle [id:dp0016806891258887013] 
\draw   (378.12,149.44) -- (382.85,158.36) -- (374.28,162.91) ;

% Text Node
\draw (409,87) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle \underline{u}$};
% Text Node
\draw (380,203) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle \underline{v}$};


\end{tikzpicture}

\end{document}
```
Here, calculating the cross product:
$$\begin{aligned} \underline{u} \cdot \underline{v} \ &= \ \mid \underline{u}\ \mid \cdot\mid \underline{v} \mid \sin\theta \\ \\ 
&= \ \mid \underline{u}\ \mid \cdot\mid \underline{v} \mid {\sin}\frac{\pi}{2}  \\ \\
&= 0\end{aligned}$$
and therefor we can make the following definition

```ad-Definition
Vectors $\underline{u}$ and $\underline{v}$ are **orthogonal**
$$\iff$$
$$\underline{u} \cdot \underline{v} = 0$$
```

*Note:* Let
$$\underline{x} = \begin{pmatrix} x \\ y \end{pmatrix}$$
Then $\underline{x}$ is **perpendicular/orthogonal** to 
$$\lambda \begin{pmatrix} -y \\ x \end{pmatrix} \ \ \ \text{or} \ \ \  \lambda\begin{pmatrix} y \\-x \end{pmatrix}$$

# Backlinks
---
- [[Scalar Product]]
- [[Vector Algebra]]