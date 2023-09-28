# Scalar Product
---
Scalar product is a function *denoted* by "$\boldsymbol{\cdot}$".  (**Binary operator**)

$$\boldsymbol{\cdot} : \mathbb{E}^{3}\rightarrow \mathbb{R}$$
i.e. we get a **real/scalar output** (hence the name!!!!!)

Let $\underline{u}, \space \underline{v} \in \mathbb{E^3}$  and let $\theta \in \mathbb{R}$ be the **planar angle** between  two vectors. In order to do a scalar product, **two properties** must hold:

- $\theta \in [0,\pi]$ 
- The two vectors are **going outwards** from point of intersection

```tikz
\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} %set default line width to 0.75pt        

\begin{tikzpicture}[x=0.75pt,y=0.75pt,yscale=-1,xscale=1]
%uncomment if require: \path (0,402); %set diagram left start at 0, and has height of 402

%Straight Lines [id:da4437652617379132] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (184.85,216.98) -- (109.47,136.76) ;
\draw [shift={(108.1,135.3)}, rotate = 46.79] [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ][line width=0.75]    (10.93,-3.29) .. controls (6.95,-1.4) and (3.31,-0.3) .. (0,0) .. controls (3.31,0.3) and (6.95,1.4) .. (10.93,3.29)   ;
%Straight Lines [id:da6919359366246228] 
\draw [color={rgb, 255:red, 74; green, 144; blue, 226 }  ,draw opacity=1 ]   (184.85,216.98) -- (298.51,141.58) ;
\draw [shift={(300.17,140.48)}, rotate = 146.44] [color={rgb, 255:red, 74; green, 144; blue, 226 }  ,draw opacity=1 ][line width=0.75]    (10.93,-3.29) .. controls (6.95,-1.4) and (3.31,-0.3) .. (0,0) .. controls (3.31,0.3) and (6.95,1.4) .. (10.93,3.29)   ;
%Shape: Ellipse [id:dp7599712014506931] 
\draw  [fill={rgb, 255:red, 0; green, 0; blue, 0 }  ,fill opacity=1 ] (182.67,216.98) .. controls (182.67,218.22) and (183.65,219.23) .. (184.85,219.23) .. controls (186.04,219.23) and (187.02,218.22) .. (187.02,216.98) .. controls (187.02,215.75) and (186.04,214.74) .. (184.85,214.74) .. controls (183.65,214.74) and (182.67,215.75) .. (182.67,216.98) -- cycle ;
%Curve Lines [id:da9435159136782311] 
\draw    (170.73,202.58) .. controls (178.25,187.05) and (197.1,183.3) .. (202.47,205.17) ;
%Curve Lines [id:da043732572464616704] 
\draw [color={rgb, 255:red, 245; green, 166; blue, 35 }  ,draw opacity=1 ]   (170.73,202.58) .. controls (149.85,239.67) and (214.99,245.71) .. (202.47,205.17) ;
%Straight Lines [id:da6201503651143601] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (387.77,223.02) -- (312.4,142.8) ;
\draw [shift={(311.03,141.34)}, rotate = 46.79] [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ][line width=0.75]    (10.93,-3.29) .. controls (6.95,-1.4) and (3.31,-0.3) .. (0,0) .. controls (3.31,0.3) and (6.95,1.4) .. (10.93,3.29)   ;
%Straight Lines [id:da44499435743744065] 
\draw [color={rgb, 255:red, 74; green, 144; blue, 226 }  ,draw opacity=1 ]   (387.77,223.02) -- (501.43,147.62) ;
\draw [shift={(503.1,146.51)}, rotate = 146.44] [color={rgb, 255:red, 74; green, 144; blue, 226 }  ,draw opacity=1 ][line width=0.75]    (10.93,-3.29) .. controls (6.95,-1.4) and (3.31,-0.3) .. (0,0) .. controls (3.31,0.3) and (6.95,1.4) .. (10.93,3.29)   ;
%Shape: Ellipse [id:dp13145555074263104] 
\draw  [fill={rgb, 255:red, 0; green, 0; blue, 0 }  ,fill opacity=1 ] (385.6,223.02) .. controls (385.6,224.26) and (386.57,225.26) .. (387.77,225.26) .. controls (388.97,225.26) and (389.94,224.26) .. (389.94,223.02) .. controls (389.94,221.78) and (388.97,220.78) .. (387.77,220.78) .. controls (386.57,220.78) and (385.6,221.78) .. (385.6,223.02) -- cycle ;
%Curve Lines [id:da424029835736604] 
\draw    (373.66,208.62) .. controls (381.18,193.09) and (403.1,187.3) .. (405.39,211.2) ;
%Straight Lines [id:da38053982821885624] 
\draw    (387.77,223.02) -- (423.16,256.92) ;
\draw [shift={(424.6,258.3)}, rotate = 223.77] [color={rgb, 255:red, 0; green, 0; blue, 0 }  ][line width=0.75]    (10.93,-3.29) .. controls (6.95,-1.4) and (3.31,-0.3) .. (0,0) .. controls (3.31,0.3) and (6.95,1.4) .. (10.93,3.29)   ;
%Curve Lines [id:da7344761482411821] 
\draw [color={rgb, 255:red, 245; green, 166; blue, 35 }  ,draw opacity=1 ]   (405.39,211.2) .. controls (416.25,212.07) and (420.43,237.08) .. (400.38,235.36) ;

% Text Node
\draw (114.3,157.54) node [anchor=north west][inner sep=0.75pt]  [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,opacity=1 ] [align=left] {$\displaystyle \underline{u}$};
% Text Node
\draw (251.61,180.86) node [anchor=north west][inner sep=0.75pt]  [color={rgb, 255:red, 74; green, 144; blue, 226 }  ,opacity=1 ] [align=left] {$\displaystyle \underline{v}$};
% Text Node
\draw (178.35,193.32) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle \theta $};
% Text Node
\draw (131.86,233.65) node [anchor=north west][inner sep=0.75pt]  [font=\small,color={rgb, 255:red, 245; green, 166; blue, 35 }  ,opacity=1 ] [align=left] {Not a planar angle};
% Text Node
\draw (317.22,163.58) node [anchor=north west][inner sep=0.75pt]  [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,opacity=1 ] [align=left] {$\displaystyle \underline{u}$};
% Text Node
\draw (468.54,181.89) node [anchor=north west][inner sep=0.75pt]  [color={rgb, 255:red, 74; green, 144; blue, 226 }  ,opacity=1 ] [align=left] {$\displaystyle \underline{v}$};
% Text Node
\draw (381.28,199.36) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle \theta $};
% Text Node
\draw (284.68,226.75) node [anchor=north west][inner sep=0.75pt]  [font=\small,color={rgb, 255:red, 245; green, 166; blue, 35 }  ,opacity=1 ] [align=left] {Not a planar angle};


\end{tikzpicture}

\end{document}
```

The **scalar product** is defined in the following way:

```ad-Definition
Title: **Sclar Product**

Let $\underline{u}, \space \underline{v} \in \mathbb{E^3}$ and $\theta \in \mathbb{R}$. Then the scalar product $\underline{u} \cdot \underline{v} \in \mathbb{R}$ is defined as:

$$\underline{u} \cdot \underline{v} \space = \space \mid \underline{u} \mid \cdot \mid \underline{v} \mid \cos\theta$$ 

where $\theta$ is the planar angle
```

### Scalar Product using Orthonormal Basis Vectors

We can use [[Orthonormal Basis for Vectors|orthonormal basis vectors]] to give a different definition for the scalar product:

```ad-Theorem
Title: **Sclar Product**

Let 
$$\underline{u} = \sum_{a = 1}^{3}{u_a}\space\underline{e_{a}} \hspace{80px} \underline{v} = \sum_{b = 1}^{3}{v_b}\space\underline{e_{b}}$$

Then the scalar product can be defined as:

$$\underline{u} \cdot \underline{v} = \sum_{i=1}^{3}u_{i} \space v_{i} = u_{1}v_{1} + u_{2}v_{2} + u_{3}v_{3} $$
```

`\begin{proof}`
**PLACE PROOF HERE AFTERWARDS**
`\end{proof}`
## Scalar Product Further Notes
---
-  [[Properties of Scalar Product]]
- [[Scalar Product using Kronecker Delta]]





