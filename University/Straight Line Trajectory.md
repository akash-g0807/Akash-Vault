# Straight Line Trajectory
---

Consider the following diagram:

```tikz
\begin{document}

\tikzset{every picture/.style={line width=0.75pt}} %set default line width to 0.75pt        

\begin{tikzpicture}[x=0.75pt,y=0.75pt,yscale=-1,xscale=1]
%uncomment if require: \path (0,402); %set diagram left start at 0, and has height of 402

%Straight Lines [id:da07486429812279405] 
\draw    (203.5,258.3) -- (205.37,127.7) ;
\draw [shift={(205.4,125.7)}, rotate = 90.82] [color={rgb, 255:red, 0; green, 0; blue, 0 }  ][line width=0.75]    (10.93,-3.29) .. controls (6.95,-1.4) and (3.31,-0.3) .. (0,0) .. controls (3.31,0.3) and (6.95,1.4) .. (10.93,3.29)   ;
%Shape: Circle [id:dp6919219182514531] 
\draw  [fill={rgb, 255:red, 0; green, 0; blue, 0 }  ,fill opacity=1 ] (202,125.7) .. controls (202,123.82) and (203.52,122.3) .. (205.4,122.3) .. controls (207.28,122.3) and (208.8,123.82) .. (208.8,125.7) .. controls (208.8,127.58) and (207.28,129.1) .. (205.4,129.1) .. controls (203.52,129.1) and (202,127.58) .. (202,125.7) -- cycle ;
%Shape: Circle [id:dp2798104629473662] 
\draw  [fill={rgb, 255:red, 0; green, 0; blue, 0 }  ,fill opacity=1 ] (200.1,258.3) .. controls (200.1,256.42) and (201.62,254.9) .. (203.5,254.9) .. controls (205.38,254.9) and (206.9,256.42) .. (206.9,258.3) .. controls (206.9,260.18) and (205.38,261.7) .. (203.5,261.7) .. controls (201.62,261.7) and (200.1,260.18) .. (200.1,258.3) -- cycle ;
%Shape: Circle [id:dp4797202017377725] 
\draw  [fill={rgb, 255:red, 0; green, 0; blue, 0 }  ,fill opacity=1 ] (264,100.7) .. controls (264,98.82) and (265.52,97.3) .. (267.4,97.3) .. controls (269.28,97.3) and (270.8,98.82) .. (270.8,100.7) .. controls (270.8,102.58) and (269.28,104.1) .. (267.4,104.1) .. controls (265.52,104.1) and (264,102.58) .. (264,100.7) -- cycle ;
%Straight Lines [id:da797119100975235] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (203.5,258.3) -- (266.65,102.55) ;
\draw [shift={(267.4,100.7)}, rotate = 112.07] [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ][line width=0.75]    (10.93,-3.29) .. controls (6.95,-1.4) and (3.31,-0.3) .. (0,0) .. controls (3.31,0.3) and (6.95,1.4) .. (10.93,3.29)   ;
%Straight Lines [id:da8657231564938234] 
\draw    (146,151.7) -- (371.1,57.3) ;
%Shape: Right Angle [id:dp4402177451309871] 
\draw  [color={rgb, 255:red, 245; green, 166; blue, 35 }  ,draw opacity=1 ] (295.76,82.07) -- (305.33,84.96) -- (302.44,94.53) ;

% Text Node
\draw (213,245) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle O$};
% Text Node
\draw (201,96) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle P$};
% Text Node
\draw (172,177) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle \underline{r_{0}}$};
% Text Node
\draw (229,183) node [anchor=north west][inner sep=0.75pt]  [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,opacity=1 ] [align=left] {$\displaystyle \underline{r}( t)$};
% Text Node
\draw (288,55) node [anchor=north west][inner sep=0.75pt]  [color={rgb, 255:red, 245; green, 166; blue, 35 }  ,opacity=1 ] [align=left] {$\displaystyle \underline{v}( t)$};


\end{tikzpicture}
\end{document}
```
Using [[Vector Equation of Lines| vector equation of lines]], we get the following equation for $\underline{r}(t)$
$$\underline{r}(t) = \underline{r_{0}} + t\underline{v} \ \ \ \ \ \ \ \ \ \ \ \ \ \underline{v}, \underline{r_{0}}\ \ \ \text{are constants}$$
Then we can find the [[Kinematics-Velocity and Acceleration|velocity]] as
$$\begin{aligned}&\underline{v}(t) = \frac{d\underline{r}(t)}{dt} = \underline{\dot{r}}(t) = \underline{v} \\ \\
&\underline{a}(t) = \frac{d\underline{\dot{r}}(t)}{dt} = \ddot{\underline{r}(t)} = \underline{0}\end{aligned}$$
# Backlinks
---
- [[Examples of Trajectories]]
- [[Newtonian Mechanics]]