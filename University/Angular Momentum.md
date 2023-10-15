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
$$\underline{J} = \underline{r} \times \underline{p} = m\underline{{r}} \times \underline{\dot{r}}$$
where $\underline{p}$ is the [[Momentum|momentum]] of the particle. 
```

*Note:* Angular Momentum definition uses the [[Vector Product]]
### Moment of Force
---
From the following calculation:
$$\begin{align*} \underline{\dot{J}} &= \frac{d}{dt}\Big(m\underline{{r}} \times \underline{\dot{r}}\Big) \\ \\ &= m\underline{\dot{r}} \times \underline{\dot{r}} + m\underline{{r}} \times \underline{\ddot{r}}\ \ \ \ \ \ \ \ \ \ \ \text{product rule} \\ \\
&= 0 + m\underline{r}  \times \underline{\ddot{r}} \tag{1}\\ \\
&= m\underline{r} \times \underline{\ddot{r}}\\\\
&= \underline{r} \times \underline{F} \tag{2}\\ \\
&\equiv  \underline{M}
\end{align*}$$

^f1af79

- [[#^f1af79|$(1)$]]: $m\underline{\dot{r}} \times \underline{\dot{r}}$ due to [[Properties of Vector Product]]
-  [[#^f1af79|$(2)$]]: By [[Newton's Equation of Motion]], $m\underline{\ddot{r}} = \underline{F}$

```ad-Definition

Title: **Moment of Force**

The moment of force of a [[Newtonian Mechanics#^36eaf6|particle]] of mass $m$ about the origin $O$ is defined to be the **rate of change** of **Angular Momentum** 
$$M = \underline{\dot{J}} = \underline{r} \times \underline{F}$$
```

#### Conservation of Angular Momentum
---
Consider a particle moving under a force directed towards or away from the origin. 
$$\underline{F} = f(\underline{r})\underline{r}$$
where $f(\underline{r})$ is a **scalar**. Hence calculating moment:

$$\begin{align*} \underline{\dot{J}} = \underline{r} \times \underline{F} &= f(\underline{r})\underline{r} \times \underline{r} \\ \\
&= 0 \tag{3}\\ \\
\Rightarrow \underline{\dot{J}} = 0 \end{align*}$$

^ea6cbb

And therefore **angular momentum is conserved**

> [!note]+ Conservation of Angular Momentum
> If a force $\underline{F}$ is proportional to $\underline{r}$, i.e. 
> $$\underline{F}=f(\underline{r})$$
> then angular momentum is conserved:
> $$\underline{\dot{J}} = 0$$

-  [[#^ea6cbb|$(3)$]]: due to [[Properties of Vector Product]]

# Backlinks
---
- [[Newtonian Mechanics]]
- [[Classical Dynamics - MAT00048I Outline]]