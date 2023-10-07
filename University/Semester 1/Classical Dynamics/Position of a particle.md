# Position of a particle
---

A point particle's **position** at time $t$ on a **trajectory** relative to an **origin** can be described by a [[Position Vectors|position vector]] relative to an origin $O$.
```tikz
\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} %set default line width to 0.75pt        

\begin{tikzpicture}[x=0.75pt,y=0.75pt,yscale=-1,xscale=1]
%uncomment if require: \path (0,402); %set diagram left start at 0, and has height of 402

%Curve Lines [id:da7249822784379534] 
\draw    (108.1,195.3) .. controls (184.1,20.3) and (248.1,240.3) .. (367.1,64.3) ;
%Straight Lines [id:da07486429812279405] 
\draw    (203.5,258.3) -- (244.75,137.59) ;
\draw [shift={(245.4,135.7)}, rotate = 108.87] [color={rgb, 255:red, 0; green, 0; blue, 0 }  ][line width=0.75]    (10.93,-3.29) .. controls (6.95,-1.4) and (3.31,-0.3) .. (0,0) .. controls (3.31,0.3) and (6.95,1.4) .. (10.93,3.29)   ;
%Shape: Circle [id:dp6919219182514531] 
\draw  [fill={rgb, 255:red, 0; green, 0; blue, 0 }  ,fill opacity=1 ] (242,135.7) .. controls (242,133.82) and (243.52,132.3) .. (245.4,132.3) .. controls (247.28,132.3) and (248.8,133.82) .. (248.8,135.7) .. controls (248.8,137.58) and (247.28,139.1) .. (245.4,139.1) .. controls (243.52,139.1) and (242,137.58) .. (242,135.7) -- cycle ;
%Shape: Circle [id:dp2798104629473662] 
\draw  [fill={rgb, 255:red, 0; green, 0; blue, 0 }  ,fill opacity=1 ] (200.1,258.3) .. controls (200.1,256.42) and (201.62,254.9) .. (203.5,254.9) .. controls (205.38,254.9) and (206.9,256.42) .. (206.9,258.3) .. controls (206.9,260.18) and (205.38,261.7) .. (203.5,261.7) .. controls (201.62,261.7) and (200.1,260.18) .. (200.1,258.3) -- cycle ;

% Text Node
\draw (213,245) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle O$};
% Text Node
\draw (241,108) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle P$};
% Text Node
\draw (236,173) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle \underline{r}( t)$};


\end{tikzpicture}

\end{document}

```
The **position vector** is $\underline{r}$ and can be represented using [[Orthonormal Basis for Vectors|basis vectors]] 
$$\underline{r}(t) = x\underline{i} + y\underline{j} + z\underline{k}$$
Using [[Einstein's Notation|Einstein's Notation]] we can also represented it in the following way:
$$\underline{r}(t) = \lambda_{a}\underline{e_{a}}$$

# Backlinks
---
- [[Newtonian Mechanics]]