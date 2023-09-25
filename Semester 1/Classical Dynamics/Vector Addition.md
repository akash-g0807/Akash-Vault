# Vector Addition
---

Two vectors of the same dimension can be added. 

```tikz
\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} %set default line width to 0.75pt        

\begin{tikzpicture}[x=0.75pt,y=0.75pt,yscale=-1,xscale=1]
%uncomment if require: \path (0,402); %set diagram left start at 0, and has height of 402

%Straight Lines [id:da2842241731121655] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (336.25,251.15) -- (185.68,308.83) ;
\draw  [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ] (247.22,272.74) -- (271.09,275.83) -- (255.76,295.04) ;
%Straight Lines [id:da6607175527808323] 
\draw [color={rgb, 255:red, 74; green, 144; blue, 226 }  ,draw opacity=1 ]   (233.53,127.1) -- (185.68,308.83) ;
\draw  [color={rgb, 255:red, 74; green, 144; blue, 226 }  ,draw opacity=1 ] (195.44,232.03) -- (210.69,215.2) -- (214.14,238.15) ;
%Shape: Ellipse [id:dp6889641750764928] 
\draw  [fill={rgb, 255:red, 0; green, 0; blue, 0 }  ,fill opacity=1 ] (187.91,306.79) .. controls (186.84,305.49) and (184.96,305.36) .. (183.73,306.49) .. controls (182.5,307.62) and (182.37,309.58) .. (183.44,310.88) .. controls (184.52,312.18) and (186.39,312.31) .. (187.62,311.18) .. controls (188.86,310.05) and (188.99,308.08) .. (187.91,306.79) -- cycle ;
%Straight Lines [id:da6268121816752817] 
\draw [color={rgb, 255:red, 74; green, 144; blue, 226 }  ,draw opacity=1 ] [dash pattern={on 0.84pt off 2.51pt}]  (384.1,69.41) -- (336.25,251.15) ;
%Straight Lines [id:da7736120018750587] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ] [dash pattern={on 0.84pt off 2.51pt}]  (384.1,69.41) -- (233.53,127.1) ;
%Straight Lines [id:da08290085932723901] 
\draw [color={rgb, 255:red, 245; green, 166; blue, 35 }  ,draw opacity=1 ]   (384.1,69.41) -- (187.91,306.79) ;
\draw  [color={rgb, 255:red, 245; green, 166; blue, 35 }  ,draw opacity=1 ] (269.6,189.96) -- (295.25,176.75) -- (291.1,205.3) ;

% Text Node
\draw (153.09,300.59) node [anchor=north west][inner sep=0.75pt]  [rotate=-359.87] [align=left] {$\displaystyle O$};
% Text Node
\draw (179,198) node [anchor=north west][inner sep=0.75pt]  [color={rgb, 255:red, 74; green, 144; blue, 226 }  ,opacity=1 ] [align=left] {$\displaystyle \underline{v}$};
% Text Node
\draw (300,269) node [anchor=north west][inner sep=0.75pt]  [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,opacity=1 ] [align=left] {$\displaystyle \underline{u}$};
% Text Node
\draw (395,76) node [anchor=north west][inner sep=0.75pt]  [color={rgb, 255:red, 245; green, 166; blue, 35 }  ,opacity=1 ] [align=left] {$\displaystyle \underline{u} \ +\ \underline{v}$};


\end{tikzpicture}
\end{document}
```
Geometrically it is clear that you get the same effect as travelling along $\underline{u}$ and then along $\underline{v}$ . 

### Properties of vector addition

1. Geometrically it is clear vector addition is **commutative**
$$\boxed{\underline{u} + \underline{v} = \underline{v} + \underline{u}}$$
2. Adding vectors is **associative** 
$$\boxed{(\underline{u} + \underline{v}) + \underline{w} = \underline{u} + (\underline{v} + \underline{w})}$$
Below is the *geometric proof*:

```tikz
\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} %set default line width to 0.75pt        

\begin{tikzpicture}[x=0.75pt,y=0.75pt,yscale=-1,xscale=1]
%uncomment if require: \path (0,402); %set diagram left start at 0, and has height of 402

%Shape: Ellipse [id:dp6889641750764928] 
\draw  [fill={rgb, 255:red, 0; green, 0; blue, 0 }  ,fill opacity=1 ] (109.39,220.57) .. controls (108.73,219.81) and (107.58,219.73) .. (106.82,220.39) .. controls (106.07,221.06) and (105.99,222.22) .. (106.65,222.98) .. controls (107.31,223.75) and (108.46,223.83) .. (109.21,223.16) .. controls (109.97,222.5) and (110.05,221.34) .. (109.39,220.57) -- cycle ;
%Straight Lines [id:da43992478876385] 
\draw [color={rgb, 255:red, 74; green, 144; blue, 226 }  ,draw opacity=1 ]   (108.02,221.78) -- (116.39,202.29) -- (154.5,113.52) ;
\draw [shift={(155.29,111.68)}, rotate = 113.24] [color={rgb, 255:red, 74; green, 144; blue, 226 }  ,draw opacity=1 ][line width=0.75]    (10.93,-3.29) .. controls (6.95,-1.4) and (3.31,-0.3) .. (0,0) .. controls (3.31,0.3) and (6.95,1.4) .. (10.93,3.29)   ;
%Straight Lines [id:da22123149914858953] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (155.29,111.68) -- (227.51,167.08) ;
\draw [shift={(229.1,168.3)}, rotate = 217.49] [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ][line width=0.75]    (10.93,-3.29) .. controls (6.95,-1.4) and (3.31,-0.3) .. (0,0) .. controls (3.31,0.3) and (6.95,1.4) .. (10.93,3.29)   ;
%Straight Lines [id:da7868096898089753] 
\draw [color={rgb, 255:red, 245; green, 166; blue, 35 }  ,draw opacity=1 ][fill={rgb, 255:red, 245; green, 166; blue, 35 }  ,fill opacity=1 ]   (229.1,168.3) -- (223.29,228.31) ;
\draw [shift={(223.1,230.3)}, rotate = 275.53] [color={rgb, 255:red, 245; green, 166; blue, 35 }  ,draw opacity=1 ][line width=0.75]    (10.93,-3.29) .. controls (6.95,-1.4) and (3.31,-0.3) .. (0,0) .. controls (3.31,0.3) and (6.95,1.4) .. (10.93,3.29)   ;
%Straight Lines [id:da7357429604460244] 
\draw [color={rgb, 255:red, 126; green, 211; blue, 33 }  ,draw opacity=1 ]   (109.21,223.16) -- (221.1,230.17) ;
\draw [shift={(223.1,230.3)}, rotate = 183.59] [color={rgb, 255:red, 126; green, 211; blue, 33 }  ,draw opacity=1 ][line width=0.75]    (10.93,-3.29) .. controls (6.95,-1.4) and (3.31,-0.3) .. (0,0) .. controls (3.31,0.3) and (6.95,1.4) .. (10.93,3.29)   ;
%Straight Lines [id:da5053032901437371] 
\draw [color={rgb, 255:red, 189; green, 16; blue, 224 }  ,draw opacity=1 ] [dash pattern={on 0.84pt off 2.51pt}]  (108.02,221.78) -- (227.27,169.11) ;
\draw [shift={(229.1,168.3)}, rotate = 156.17] [color={rgb, 255:red, 189; green, 16; blue, 224 }  ,draw opacity=1 ][line width=0.75]    (10.93,-3.29) .. controls (6.95,-1.4) and (3.31,-0.3) .. (0,0) .. controls (3.31,0.3) and (6.95,1.4) .. (10.93,3.29)   ;
%Shape: Ellipse [id:dp017834389948185647] 
\draw  [fill={rgb, 255:red, 0; green, 0; blue, 0 }  ,fill opacity=1 ] (277.39,226.57) .. controls (276.73,225.81) and (275.58,225.73) .. (274.82,226.39) .. controls (274.07,227.06) and (273.99,228.22) .. (274.65,228.98) .. controls (275.31,229.75) and (276.46,229.83) .. (277.21,229.16) .. controls (277.97,228.5) and (278.05,227.34) .. (277.39,226.57) -- cycle ;
%Straight Lines [id:da7750762549328006] 
\draw [color={rgb, 255:red, 74; green, 144; blue, 226 }  ,draw opacity=1 ]   (276.02,227.78) -- (284.39,208.29) -- (322.5,119.52) ;
\draw [shift={(323.29,117.68)}, rotate = 113.24] [color={rgb, 255:red, 74; green, 144; blue, 226 }  ,draw opacity=1 ][line width=0.75]    (10.93,-3.29) .. controls (6.95,-1.4) and (3.31,-0.3) .. (0,0) .. controls (3.31,0.3) and (6.95,1.4) .. (10.93,3.29)   ;
%Straight Lines [id:da4863048697575807] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (323.29,117.68) -- (395.51,173.08) ;
\draw [shift={(397.1,174.3)}, rotate = 217.49] [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ][line width=0.75]    (10.93,-3.29) .. controls (6.95,-1.4) and (3.31,-0.3) .. (0,0) .. controls (3.31,0.3) and (6.95,1.4) .. (10.93,3.29)   ;
%Straight Lines [id:da832126478723327] 
\draw [color={rgb, 255:red, 245; green, 166; blue, 35 }  ,draw opacity=1 ][fill={rgb, 255:red, 245; green, 166; blue, 35 }  ,fill opacity=1 ]   (397.1,174.3) -- (391.29,234.31) ;
\draw [shift={(391.1,236.3)}, rotate = 275.53] [color={rgb, 255:red, 245; green, 166; blue, 35 }  ,draw opacity=1 ][line width=0.75]    (10.93,-3.29) .. controls (6.95,-1.4) and (3.31,-0.3) .. (0,0) .. controls (3.31,0.3) and (6.95,1.4) .. (10.93,3.29)   ;
%Straight Lines [id:da7282921278897991] 
\draw [color={rgb, 255:red, 126; green, 211; blue, 33 }  ,draw opacity=1 ]   (277.21,229.16) -- (389.1,236.17) ;
\draw [shift={(391.1,236.3)}, rotate = 183.59] [color={rgb, 255:red, 126; green, 211; blue, 33 }  ,draw opacity=1 ][line width=0.75]    (10.93,-3.29) .. controls (6.95,-1.4) and (3.31,-0.3) .. (0,0) .. controls (3.31,0.3) and (6.95,1.4) .. (10.93,3.29)   ;
%Straight Lines [id:da5895209641943281] 
\draw [color={rgb, 255:red, 189; green, 16; blue, 224 }  ,draw opacity=1 ] [dash pattern={on 0.84pt off 2.51pt}]  (323.29,117.68) -- (390.11,234.56) ;
\draw [shift={(391.1,236.3)}, rotate = 240.25] [color={rgb, 255:red, 189; green, 16; blue, 224 }  ,draw opacity=1 ][line width=0.75]    (10.93,-3.29) .. controls (6.95,-1.4) and (3.31,-0.3) .. (0,0) .. controls (3.31,0.3) and (6.95,1.4) .. (10.93,3.29)   ;

% Text Node
\draw (81.79,211.82) node [anchor=north west][inner sep=0.75pt]  [rotate=-359.87] [align=left] {$\displaystyle O$};
% Text Node
\draw (98.46,151.32) node [anchor=north west][inner sep=0.75pt]  [color={rgb, 255:red, 74; green, 144; blue, 226 }  ,opacity=1 ] [align=left] {$\displaystyle \underline{u}$};
% Text Node
\draw (186.31,105.37) node [anchor=north west][inner sep=0.75pt]  [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,opacity=1 ] [align=left] {$\displaystyle \underline{v}$};
% Text Node
\draw (238,185) node [anchor=north west][inner sep=0.75pt]  [color={rgb, 255:red, 245; green, 166; blue, 35 }  ,opacity=1 ] [align=left] {$\displaystyle \underline{w}$};
% Text Node
\draw (144,161) node [anchor=north west][inner sep=0.75pt]  [color={rgb, 255:red, 189; green, 16; blue, 224 }  ,opacity=1 ] [align=left] {$\displaystyle \underline{u} \ +\ \underline{v}$};
% Text Node
\draw (117,235) node [anchor=north west][inner sep=0.75pt]  [color={rgb, 255:red, 126; green, 211; blue, 33 }  ,opacity=1 ] [align=left] {$\displaystyle (\underline{u} \ +\ \underline{v}) \ +\ \underline{w}$};
% Text Node
\draw (249.79,217.82) node [anchor=north west][inner sep=0.75pt]  [rotate=-359.87] [align=left] {$\displaystyle O$};
% Text Node
\draw (266.46,157.32) node [anchor=north west][inner sep=0.75pt]  [color={rgb, 255:red, 74; green, 144; blue, 226 }  ,opacity=1 ] [align=left] {$\displaystyle \underline{u}$};
% Text Node
\draw (354.31,111.37) node [anchor=north west][inner sep=0.75pt]  [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,opacity=1 ] [align=left] {$\displaystyle \underline{v}$};
% Text Node
\draw (406,191) node [anchor=north west][inner sep=0.75pt]  [color={rgb, 255:red, 245; green, 166; blue, 35 }  ,opacity=1 ] [align=left] {$\displaystyle \underline{w}$};
% Text Node
\draw (309,181) node [anchor=north west][inner sep=0.75pt]  [color={rgb, 255:red, 189; green, 16; blue, 224 }  ,opacity=1 ] [align=left] {$\displaystyle \underline{v} \ +\ \underline{w}$};
% Text Node
\draw (285,241) node [anchor=north west][inner sep=0.75pt]  [color={rgb, 255:red, 126; green, 211; blue, 33 }  ,opacity=1 ] [align=left] {$\displaystyle \underline{u} \ +( \ \underline{v} \ +\ \underline{w})$};


\end{tikzpicture}
\end{document}
```

# Backlinks
---
- [[Vector Algebra]]