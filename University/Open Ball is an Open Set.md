# Open Ball is an Open Set
---
```ad-Theorem

Title:  **Open Ball is an Open Set**

Consider the [[Definition of Topology on Metric Spaces|Topology on Metric Spaces]] $T_d$.  
$\forall x \in X$ and **for any** $\epsilon > 0$, 
$$B(x, \epsilon) \in T_{d}$$
i.e. [[Open and Closed Balls|open ball]] is an [[Open and Closed Sets|open set]]
```

`\begin{proof}`
Consider the following diagram
![[Open Ball is Open Set proof dark.svg|540]]
Take the [[Open and Closed Balls|open ball]] centered at x with radius $\epsilon$. Then:
$$y \in B(x, \epsilon)$$
1.  If $y = x$, then we are done as consider the open ball $B(y,\epsilon)$
$$B(y,\epsilon) = B(x,\epsilon) \subseteq B(x, \epsilon)$$
as the set contains itself. Hence as by [[Describing Open Sets using Interior Points|definition]], $B(x,\epsilon)$ is is an [[Open and Closed Sets|open set]]
2.  If $y \neq x$, then by [[General Definition of Metric Spaces|Axiom 1 of metric spaces]]
$$d(x,y) = \Delta > 0 \ \ \ \ \ \ \ \  \text{and} \ \ \ \ \ \ \ \  0 < \Delta < \epsilon$$
```tikz
\begin{document}



\tikzset{every picture/.style={line width=0.75pt}} %set default line width to 0.75pt        

\begin{tikzpicture}[x=0.75pt,y=0.75pt,yscale=-1,xscale=1]
%uncomment if require: \path (0,300); %set diagram left start at 0, and has height of 300

%Straight Lines [id:da6926499844966059] 
\draw    (179,120) -- (403,120) ;
%Straight Lines [id:da253576271162139] 
\draw    (330,109) -- (330,130) ;
%Straight Lines [id:da43912952513686887] 
\draw    (179,109.5) -- (179,130.5) ;
%Straight Lines [id:da5535236668912316] 
\draw    (181,130.49) -- (328,130.01) ;
\draw [shift={(330,130)}, rotate = 179.81] [color={rgb, 255:red, 0; green, 0; blue, 0 }  ][line width=0.75]    (10.93,-3.29) .. controls (6.95,-1.4) and (3.31,-0.3) .. (0,0) .. controls (3.31,0.3) and (6.95,1.4) .. (10.93,3.29)   ;
\draw [shift={(179,130.5)}, rotate = 359.81] [color={rgb, 255:red, 0; green, 0; blue, 0 }  ][line width=0.75]    (10.93,-3.29) .. controls (6.95,-1.4) and (3.31,-0.3) .. (0,0) .. controls (3.31,0.3) and (6.95,1.4) .. (10.93,3.29)   ;
%Straight Lines [id:da1938870013522258] 
\draw    (403,109.5) -- (403,130.5) ;
%Straight Lines [id:da03037219059521612] 
\draw    (332,130.01) -- (401,130.49) ;
\draw [shift={(403,130.5)}, rotate = 180.39] [color={rgb, 255:red, 0; green, 0; blue, 0 }  ][line width=0.75]    (10.93,-3.29) .. controls (6.95,-1.4) and (3.31,-0.3) .. (0,0) .. controls (3.31,0.3) and (6.95,1.4) .. (10.93,3.29)   ;
\draw [shift={(330,130)}, rotate = 0.39] [color={rgb, 255:red, 0; green, 0; blue, 0 }  ][line width=0.75]    (10.93,-3.29) .. controls (6.95,-1.4) and (3.31,-0.3) .. (0,0) .. controls (3.31,0.3) and (6.95,1.4) .. (10.93,3.29)   ;
%Straight Lines [id:da24981709766626814] 
\draw    (181,160.5) -- (401,160.5) ;
\draw [shift={(403,160.5)}, rotate = 180] [color={rgb, 255:red, 0; green, 0; blue, 0 }  ][line width=0.75]    (10.93,-3.29) .. controls (6.95,-1.4) and (3.31,-0.3) .. (0,0) .. controls (3.31,0.3) and (6.95,1.4) .. (10.93,3.29)   ;
\draw [shift={(179,160.5)}, rotate = 0] [color={rgb, 255:red, 0; green, 0; blue, 0 }  ][line width=0.75]    (10.93,-3.29) .. controls (6.95,-1.4) and (3.31,-0.3) .. (0,0) .. controls (3.31,0.3) and (6.95,1.4) .. (10.93,3.29)   ;

% Text Node
\draw (173,84) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle x$};
% Text Node
\draw (245,133) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle \Delta $};
% Text Node
\draw (323,84) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle y$};
% Text Node
\draw (401,88) node [anchor=north west][inner sep=0.75pt]   [align=left] {boundary};
% Text Node
\draw (346,134) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle \epsilon \ -\ \Delta $};
% Text Node
\draw (260,160) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle \epsilon $};


\end{tikzpicture}

\end{document}
```
So we let $\varepsilon^{'} = \min\{\Delta, \varepsilon - \Delta \}$ and let $\varepsilon = \varepsilon^{*}/2$
> [!math|{"type":"claim","number":"","setAsNoteMathLink":false}] Claim.
> $$B(y,\varepsilon^{*})  \subseteq B(x, \varepsilon)$$

That is by the definition of [[Open and Closed Balls|open ball]] we want to show what
$$\text{for any } z \in B(y, \varepsilon^{*}) \Rightarrow d(x,z) < \varepsilon$$
By [[General Definition of Metric Spaces|Triangle Inequality of metrics]], 
$$\begin{aligned}d(x,z) &\leq d(x,y) + d(y,z)\\ \\
&\leq  \Delta + \varepsilon^{*}  \ \ \ \ \ \ \ \  \ \ \ \ \ \ \ \ \ \ \ \ \text{as } z \in B(y, \varepsilon^{*})\\ \\
&= \Delta + \min\{\Delta, \varepsilon-\Delta\}/2 \\ \\ 
&\leq \Delta + \frac{\varepsilon - \Delta}{2} \\ \\
&< \Delta + \varepsilon = \varepsilon \\ \\
\Rightarrow z \in B(x, \varepsilon) \ \ \ \ \ \forall z \in B(y, \varepsilon^{*}) \end{aligned}$$
And therefore we have that
$$B(y, \varepsilon^{*}) \subseteq B(x,\varepsilon)$$
and by  [[Describing Open Sets using Interior Points|definition]], $B(x,\epsilon)$ is is an [[Open and Closed Sets|open set]]
`\end{proof}`