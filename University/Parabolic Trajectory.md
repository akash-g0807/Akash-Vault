# Parabolic Trajectory
---

Consider the following equation for the [[Position of a particle|trajectory]]:  
$$\underline{r} = \underline{r_{0}}+ \underline{v}_{0}t + \underline{a_{0}}\frac{1}{2}t^2$$
where $v_{0}$ and $a_{0}$ are **constants**. Here the [[Kinematics-Velocity and Acceleration|velocity and acceleration]] is:

- $\displaystyle \underline{v}(t) = \frac{d\underline{r}(t)}{dt} = \underline{\dot{r}}(t) = \underline{v_{0}} + \underline{a_{0}}t$

- $\displaystyle \underline{a}(t) = \underline{\dot{v}}(t) = \frac{d}{dt}(\underline{v_{0}} + \underline{a_{0}}t) = \underline{a_0}$

### Example of parabolic Trajectory
---
Consider the following equation:
$$\underline{r}(t) = (\underbrace{u_{0}\underline{i} + v_{0}\underline{k}}_{\underline{v_{0}}}) - \frac{1}{2}gt^{2}\underline{k}$$
```tikz
\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} %set default line width to 0.75pt        

\begin{tikzpicture}[x=0.75pt,y=0.75pt,yscale=-1,xscale=1]
%uncomment if require: \path (0,402); %set diagram left start at 0, and has height of 402

%Straight Lines [id:da021686159454420983] 
\draw    (150.1,91.3) -- (150.1,250.3) ;
%Straight Lines [id:da9865222157984955] 
\draw    (140,240) -- (328.1,240.3) ;
%Shape: Right Angle [id:dp4412444494112757] 
\draw   (143.39,98.71) -- (150.1,91.3) -- (157.33,97.84) ;
%Shape: Right Angle [id:dp7802119319801154] 
\draw   (321.88,232.47) -- (328.1,240.3) -- (320.46,246.37) ;
%Curve Lines [id:da14645678527741524] 
\draw    (150,240) .. controls (179.1,131.3) and (251.2,119.6) .. (289.1,240.3) ;
%Straight Lines [id:da915058268090938] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (150,240) -- (252.42,173.39) ;
\draw [shift={(254.1,172.3)}, rotate = 146.96] [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ][line width=0.75]    (10.93,-3.29) .. controls (6.95,-1.4) and (3.31,-0.3) .. (0,0) .. controls (3.31,0.3) and (6.95,1.4) .. (10.93,3.29)   ;

% Text Node
\draw (188,177) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle \underline{r}( t)$};
% Text Node
\draw (165,93) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle \underline{k}$};
% Text Node
\draw (144,65) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle z$};
% Text Node
\draw (281,245) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle \underline{i}$};
% Text Node
\draw (338,227) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle x$};


\end{tikzpicture}
\end{document}
```
Here, separating the **components** if $\underline{i}$ and $\underline{k}$, we get the following (**scalars**):
$$
{x}(t) = u_{0}t \Rightarrow t = \frac{x(t)}{u_{0}}
$$
and substituting for in the value for $z(t)$ (component of $\underline{k}$),
$$\begin{aligned} z &= {v_{0}t} - \frac{1}{2}gt^{2 }\\ \\
&= \frac{v_{0}\ x}{u_{0}} - \frac{1}{2}g\Big(\frac{x}{u_{0}}\Big)^{2 } \\ \\
&= \frac{v_{0} \ x}{u_{0}}\Big(1 - \frac{1}{2}\frac{gx}{u_{0}\ v_{0}}\Big)\end{aligned}$$
And therefore as we can see, the equation for $z(t)$ is in the form of a **parabola**. 

# Backlinks
---
- [[Examples of Trajectories]]
- [[Basic Kinematics]]
- [[Newtonian Mechanics]]
- [[Classical Dynamics - MAT00048I Outline]]