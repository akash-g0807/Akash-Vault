# Angular Momentum
---
Consider the following diagram:
```tikz
\begin{document}



\tikzset{every picture/.style={line width=0.75pt}} %set default line width to 0.75pt        

\begin{tikzpicture}[x=0.75pt,y=0.75pt,yscale=-1,xscale=1]
%uncomment if require: \path (0,391); %set diagram left start at 0, and has height of 391

%Straight Lines [id:da12700555851024187] 
\draw    (201,170) -- (345.14,71.34) ;
\draw [shift={(346.8,70.21)}, rotate = 145.61] [color={rgb, 255:red, 0; green, 0; blue, 0 }  ][line width=0.75]    (10.93,-3.29) .. controls (6.95,-1.4) and (3.31,-0.3) .. (0,0) .. controls (3.31,0.3) and (6.95,1.4) .. (10.93,3.29)   ;

% Text Node
\draw (179.79,167) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle O$};
% Text Node
\draw (347.79,79) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle \underline{r}$};


\end{tikzpicture}

\end{document}
```
```ad-Definition

Title: **Angular Momentum**

Angular Momentum of a [[Newtonian Mechanics#^36eaf6|particle]] of mass $m$ is about the origin $O$ is defined to be
$$\underline{J} = \underline{r} \times \underline{p} = m\underline{\dot{r}} \times \underline{r}$$
where $\underline{p}$ is the [[Momentum|momentum]] of the particle. 
```

### Moment of Force
---
From the following calculation:

$$\begin{aligned} \underline{\dot{J}} = \frac{d}{dt}\Big(m\underline{r}\Big) \end{aligned}$$