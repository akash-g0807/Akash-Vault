# The Polar Co-Ordinate System
---

For any [[General Definition of Vectors|vector]] $\underline{x}$ on the $xy-$plane, we can introduce 2 new **[[Unit Vector|unit vectors]]** 
$$\underline{e_{r}} \ \ ,  \ \ \underline{e_{\theta}}$$
where $\underline{e_{r}}$ is the unit vector in the **radial direction** and $\underline{e_{\theta}}$ is the unit vector in the **azimuthal direction**.

```tikz
\begin{document}



\tikzset{every picture/.style={line width=0.75pt}} %set default line width to 0.75pt        

\begin{tikzpicture}[x=0.75pt,y=0.75pt,yscale=-1,xscale=1]
%uncomment if require: \path (0,402); %set diagram left start at 0, and has height of 402

%Straight Lines [id:da021686159454420983] 
\draw    (351.43,1.3) -- (353.12,398.08) ;
%Straight Lines [id:da9865222157984955] 
\draw    (105.55,199.45) -- (598.99,199.93) ;
%Shape: Right Angle [id:dp4412444494112757] 
\draw   (339.4,12.63) -- (351.43,1.3) -- (363,12.5) ;
%Shape: Right Angle [id:dp7802119319801154] 
\draw   (587.75,187.9) -- (598.99,199.93) -- (586.7,210.41) ;
%Shape: Ellipse [id:dp5189182370807889] 
\draw  [dash pattern={on 0.84pt off 2.51pt}] (197.24,199.69) .. controls (197.24,117.94) and (266.65,51.66) .. (352.27,51.66) .. controls (437.9,51.66) and (507.31,117.94) .. (507.31,199.69) .. controls (507.31,281.45) and (437.9,347.72) .. (352.27,347.72) .. controls (266.65,347.72) and (197.24,281.45) .. (197.24,199.69) -- cycle ;
%Straight Lines [id:da678334264237589] 
\draw    (352.27,199.69) -- (466.49,99.4) ;
\draw [shift={(467.99,98.08)}, rotate = 138.71] [color={rgb, 255:red, 0; green, 0; blue, 0 }  ][line width=0.75]    (10.93,-3.29) .. controls (6.95,-1.4) and (3.31,-0.3) .. (0,0) .. controls (3.31,0.3) and (6.95,1.4) .. (10.93,3.29)   ;
%Shape: Ellipse [id:dp07755096578723952] 
\draw  [fill={rgb, 255:red, 0; green, 0; blue, 0 }  ,fill opacity=1 ] (462.84,98.08) .. controls (462.84,95.36) and (465.14,93.16) .. (467.99,93.16) .. controls (470.83,93.16) and (473.14,95.36) .. (473.14,98.08) .. controls (473.14,100.79) and (470.83,103) .. (467.99,103) .. controls (465.14,103) and (462.84,100.79) .. (462.84,98.08) -- cycle ;
%Straight Lines [id:da47746960657082327] 
\draw [color={rgb, 255:red, 74; green, 144; blue, 226 }  ,draw opacity=1 ]   (467.99,98.08) -- (505.35,64.99) ;
\draw [shift={(506.84,63.67)}, rotate = 138.47] [color={rgb, 255:red, 74; green, 144; blue, 226 }  ,draw opacity=1 ][line width=0.75]    (10.93,-3.29) .. controls (6.95,-1.4) and (3.31,-0.3) .. (0,0) .. controls (3.31,0.3) and (6.95,1.4) .. (10.93,3.29)   ;
%Straight Lines [id:da6490221790082495] 
\draw [color={rgb, 255:red, 74; green, 144; blue, 226 }  ,draw opacity=1 ]   (467.99,98.08) -- (432.3,65.21) ;
\draw [shift={(430.82,63.86)}, rotate = 42.64] [color={rgb, 255:red, 74; green, 144; blue, 226 }  ,draw opacity=1 ][line width=0.75]    (10.93,-3.29) .. controls (6.95,-1.4) and (3.31,-0.3) .. (0,0) .. controls (3.31,0.3) and (6.95,1.4) .. (10.93,3.29)   ;
%Straight Lines [id:da4708485533590365] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ] [dash pattern={on 0.84pt off 2.51pt}]  (430.82,63.86) -- (430.82,97.73) ;
%Straight Lines [id:da004192017604060294] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ] [dash pattern={on 0.84pt off 2.51pt}]  (467.99,98.08) -- (430.82,97.73) ;
%Straight Lines [id:da2288290067165305] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ] [dash pattern={on 0.84pt off 2.51pt}]  (507.1,98.08) -- (506.84,63.67) ;
%Straight Lines [id:da8720909795724745] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ] [dash pattern={on 0.84pt off 2.51pt}]  (507.1,98.08) -- (467.99,98.08) ;
%Curve Lines [id:da03516890978243714] 
\draw    (378.1,177.08) .. controls (395.1,172.08) and (398.1,191.08) .. (393.1,200.08) ;
%Straight Lines [id:da8974682091961091] 
\draw  [dash pattern={on 4.5pt off 4.5pt}]  (467.99,98.08) -- (468.1,204.08) ;
%Straight Lines [id:da9922721724934852] 
\draw  [dash pattern={on 4.5pt off 4.5pt}]  (352.1,98.08) -- (467.99,98.08) ;
%Curve Lines [id:da6694541782019319] 
\draw    (481.1,86.78) .. controls (493.1,81.78) and (493.54,99.08) .. (487.54,98.08) ;

% Text Node
\draw (421.62,136.07) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle r$};
% Text Node
\draw (384,71) node [anchor=north west][inner sep=0.75pt]  [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,opacity=1 ] [align=left] {$\displaystyle \cos \theta $};
% Text Node
\draw (487.54,98.08) node [anchor=north west][inner sep=0.75pt]  [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,opacity=1 ] [align=left] {$\displaystyle \cos \theta $};
% Text Node
\draw (378.1,177.08) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle \theta $};
% Text Node
\draw (423,28) node [anchor=north west][inner sep=0.75pt]  [color={rgb, 255:red, 74; green, 144; blue, 226 }  ,opacity=1 ] [align=left] {$\displaystyle \underline{e_{\theta }}$};
% Text Node
\draw (514,39) node [anchor=north west][inner sep=0.75pt]  [color={rgb, 255:red, 74; green, 144; blue, 226 }  ,opacity=1 ] [align=left] {$\displaystyle \underline{e_{r}}$};
% Text Node
\draw (421,98) node [anchor=north west][inner sep=0.75pt]  [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,opacity=1 ] [align=left] {$\displaystyle sin\theta $};
% Text Node
\draw (513,70) node [anchor=north west][inner sep=0.75pt]  [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,opacity=1 ] [align=left] {$\displaystyle sin\theta $};
% Text Node
\draw (462,200) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle x$};
% Text Node
\draw (334,85) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle y$};


\end{tikzpicture}
\end{document}
```
The relation between between **polar** and **cartesian** is given by:
$$x = r\cos\theta \ \ \ \ \ \ \  y=r\sin\theta$$
Just like $\underline{i}$ and $\underline{j}$, $\underline{e_{r}}$ and $\underline{e_{\theta}}$ form an [[Orthonormal Basis for Vectors|orthonormal basis]]. 

# Backlinks
---
- [[Motion in Plane Polar Co-ordinates]]
- [[Newtonian Mechanics]]