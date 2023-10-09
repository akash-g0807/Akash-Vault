# Circular Trajectory
---
Consider a particle's [[Position of a particle|trajectory]] be described by the following equation:
$$\underline{r}(t) = a(\cos(\omega t)\underline{i} + \sin(\omega t)\underline{j})$$
where:
- $x(t) = a\cos(\omega t)$ i.e. the **$x$-component**
-  $y(t) = a\sin(\omega t)$ i.e. the **$y$-component

> [!math|{"type":"remark","number":"","setAsNoteMathLink":false}] Remark.
> $$x^{2}+ y^{2} = a^{2}\cos^{2}(\omega t) + a^{2}\cos^{2}(\omega t) \ \ \ \Rightarrow \ \ \  x^{2} + y^{2} = a^{2}$$
> which is the [[equation of a circle]] of radius $a$.

#### Velocity and Acceleration
##### Velocity
---
First calculating the [[Kinematics-Velocity and Acceleration|velocity]],
$$\underline{\dot{r}}(t) = a(-\omega \sin(\omega t)\underline{i} + \omega\cos(\omega t)\underline{j})$$
where:
- $\dot{x}(t) = -a\ \omega\sin(\omega t)$ i.e. the velocity in **$x$-direction**
- $\dot{y}(t) = a\ \omega\cos(\omega t)$ i.e. the velocity in **$y$-direction**

The [[Vectors as displacement|magnitude]] of velocity is:
$$\begin{aligned} \mid \underline{\dot{r}} \mid^{2} &= x^{2} + y^{2} \\ \\
&= a^{2}\omega^{2}\sin^{2}(\omega t) + a^{2}\omega^{2}\cos^{2}(\omega t) \\ \\
&= a^{2} \omega^{2} \\
\Rightarrow\mid\underline{\dot{r}}\mid =  \mid\underline{v}\mid =a\omega\end{aligned}$$
We can see that velocity has a **constant magnitude**, but is clearly changing in direction. 
The particle is moving in the **anti-clockwise** direction. (This can be verified by *checking any random point*). 

##### Acceleration
---
Calculating the [[Kinematics-Velocity and Acceleration|acceleration]]:
$$\begin{aligned} \underline{\ddot{r}}(t) &= -a\omega^{2}(\cos(\omega t)\underline{i} + \sin(\omega t)\underline{j})\\ \\
&= -\omega^{2}\underline{r}\end{aligned}$$
So as we can see from the equation $\underline{\ddot{r}}(t) = -\omega^{2}\underline{r}$, we can see that the **acceleration points downwards**, i.e. opposite to the direction of $\underline{r}$ i.e. position vector. 

```tikz
\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} %set default line width to 0.75pt        

\begin{tikzpicture}[x=0.75pt,y=0.75pt,yscale=-1,xscale=1]
%uncomment if require: \path (0,402); %set diagram left start at 0, and has height of 402

%Straight Lines [id:da021686159454420983] 
\draw    (230.1,98.3) -- (231.1,344.3) ;
%Straight Lines [id:da9865222157984955] 
\draw    (84.55,221.15) -- (376.65,221.45) ;
%Shape: Right Angle [id:dp4412444494112757] 
\draw   (222.98,105.32) -- (230.1,98.3) -- (236.95,105.24) ;
%Shape: Right Angle [id:dp7802119319801154] 
\draw   (369.99,213.99) -- (376.65,221.45) -- (369.37,227.94) ;
%Shape: Circle [id:dp5189182370807889] 
\draw   (138.82,221.3) .. controls (138.82,170.61) and (179.91,129.53) .. (230.6,129.53) .. controls (281.29,129.53) and (322.37,170.61) .. (322.37,221.3) .. controls (322.37,271.99) and (281.29,313.07) .. (230.6,313.07) .. controls (179.91,313.07) and (138.82,271.99) .. (138.82,221.3) -- cycle ;
%Straight Lines [id:da030770231855278496] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (230.6,129.53) -- (179.1,130.27) ;
\draw [shift={(177.1,130.3)}, rotate = 359.17] [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ][line width=0.75]    (10.93,-3.29) .. controls (6.95,-1.4) and (3.31,-0.3) .. (0,0) .. controls (3.31,0.3) and (6.95,1.4) .. (10.93,3.29)   ;
%Straight Lines [id:da00482572515300661] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (289.1,151.3) -- (251.5,112.73) ;
\draw [shift={(250.1,111.3)}, rotate = 45.73] [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ][line width=0.75]    (10.93,-3.29) .. controls (6.95,-1.4) and (3.31,-0.3) .. (0,0) .. controls (3.31,0.3) and (6.95,1.4) .. (10.93,3.29)   ;
%Straight Lines [id:da678334264237589] 
\draw    (230.6,221.3) -- (287.82,152.83) ;
\draw [shift={(289.1,151.3)}, rotate = 129.89] [color={rgb, 255:red, 0; green, 0; blue, 0 }  ][line width=0.75]    (10.93,-3.29) .. controls (6.95,-1.4) and (3.31,-0.3) .. (0,0) .. controls (3.31,0.3) and (6.95,1.4) .. (10.93,3.29)   ;
%Straight Lines [id:da503332446941831] 
\draw [color={rgb, 255:red, 126; green, 211; blue, 33 }  ,draw opacity=1 ]   (310.1,128.3) -- (290.45,149.82) ;
\draw [shift={(289.1,151.3)}, rotate = 312.4] [color={rgb, 255:red, 126; green, 211; blue, 33 }  ,draw opacity=1 ][line width=0.75]    (10.93,-3.29) .. controls (6.95,-1.4) and (3.31,-0.3) .. (0,0) .. controls (3.31,0.3) and (6.95,1.4) .. (10.93,3.29)   ;

% Text Node
\draw (262,181) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle \underline{r}( t)$};
% Text Node
\draw (239,71) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle \underline{j}$};
% Text Node
\draw (206,54) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle y$};
% Text Node
\draw (346,223) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle \underline{i}$};
% Text Node
\draw (384,210) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle x$};
% Text Node
\draw (195,104) node [anchor=north west][inner sep=0.75pt]  [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,opacity=1 ] [align=left] {$\displaystyle \underline{v}$};
% Text Node
\draw (277,112) node [anchor=north west][inner sep=0.75pt]  [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,opacity=1 ] [align=left] {$\displaystyle \underline{v}$};
% Text Node
\draw (312,109) node [anchor=north west][inner sep=0.75pt]  [color={rgb, 255:red, 126; green, 211; blue, 33 }  ,opacity=1 ] [align=left] {$\displaystyle \underline{a}$};


\end{tikzpicture}
\end{document}
```
# Backlinks
---
- [[Examples of Trajectories]]
- [[Basic Kinematics]]
- [[Newtonian Mechanics]]