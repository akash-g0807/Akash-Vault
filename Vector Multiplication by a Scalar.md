# Vector Multiplication by a Scalar
---
Vectors can be multiplied by a scalar value (real numbers $\mathbb{R}$) to get another vector. The direction of the new vector depends on the sign of the scalar value


```tikz
\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} %set default line width to 0.75pt        

\begin{tikzpicture}[x=0.75pt,y=0.75pt,yscale=-1,xscale=1]
%uncomment if require: \path (0,402); %set diagram left start at 0, and has height of 402

%Straight Lines [id:da7167353389209443] 
\draw    (252.21,236.82) -- (261.7,229.82) -- (279.26,216.3) ;
\draw [shift={(280.84,215.08)}, rotate = 142.4] [color={rgb, 255:red, 0; green, 0; blue, 0 }  ][line width=0.75]    (10.93,-3.29) .. controls (6.95,-1.4) and (3.31,-0.3) .. (0,0) .. controls (3.31,0.3) and (6.95,1.4) .. (10.93,3.29)   ;
%Straight Lines [id:da18547876587091028] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (280.84,215.08) -- (336.51,172.81) ;
\draw [shift={(338.1,171.6)}, rotate = 142.79] [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ][line width=0.75]    (10.93,-3.29) .. controls (6.95,-1.4) and (3.31,-0.3) .. (0,0) .. controls (3.31,0.3) and (6.95,1.4) .. (10.93,3.29)   ;
%Straight Lines [id:da3504525720449021] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (252.21,236.82) -- (196.54,279.09) ;
\draw [shift={(194.95,280.3)}, rotate = 322.79] [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ][line width=0.75]    (10.93,-3.29) .. controls (6.95,-1.4) and (3.31,-0.3) .. (0,0) .. controls (3.31,0.3) and (6.95,1.4) .. (10.93,3.29)   ;

% Text Node
\draw (261.7,229.82) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle \underline{v}$};
% Text Node
\draw (325,190) node [anchor=north west][inner sep=0.75pt]  [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,opacity=1 ] [align=left] {$\displaystyle \lambda \underline{v}$ when $\displaystyle \lambda  >0$};
% Text Node
\draw (99,234) node [anchor=north west][inner sep=0.75pt]  [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,opacity=1 ] [align=left] {$\displaystyle \lambda \underline{v}$ when $\displaystyle \lambda < 0$};


\end{tikzpicture}
\end{document}
```
Lets say we multiply a vector $\underline{v}$ by a scalar value $\lambda \in \mathbb{R}$. Then:

- If $\underline{\lambda > 0}$: Then the new vector is in the *same direction* as the original vector.
-  If $\underline{\lambda < 0}$: Then the new vector is in the *opposite direction* as the original vector.

The new vector has **magnitude**:
$$\mid \lambda\cdot\underline{v}\mid \ = \ \mid\lambda\mid\cdot\mid\underline{v}\mid $$

### Scalar multiplication for *n-dimensional* vectors

```ad-Definition
Title **Scalar multiplication for n-dimensonal vectors**
Let $\underline{x} \in \mathbb{R}^n$ and $\lambda \in \mathbb{R}$. These vectors can be multiplied by the scalar being defined as
$$\underline{x} + \underline{y} = (x_{1} + y_{1} , \ldots , x_{n} + y_{n})$$
```

# Backlinks
---
- [[Vector Algebra]]

