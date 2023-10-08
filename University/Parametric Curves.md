# Parametric Curves
---

```ad-Definition

Title: **Parametric Curves**

A **parametric** (or path) is a [[Continuously Differentiable Functions|continuously differentiable]] [[Basics of Continuity on Open Sets|map]] 
$$\begin{aligned}p \in \mathcal{C}^{\ 1}([a,b],\mathbb{R}^n)
\\ \\ \underline{p}: [a,b] \rightarrow \mathbb{R}^{n}\end{aligned}$$

for some $a < b$ and $a,b \in \mathbb{R}$
```

*Notation:* The notation for the [[Definition of Total Derivative|derivative]] of a parametric map:
$$D(\underline{p}(t)) = \dot{\underline{p}}(t)$$

## Reparameterization
---

```ad-Definition

Title: **Reparameterization**

Another curve
$$\underline{q}: [a^{'}. b^{'}] \rightarrow \mathbb{R}^n$$
is a **reparametrization** of $\underline{p}:[a,b] \rightarrow \mathbb{R}^n$ if $\underline{q} = \underline{p} \circ h$ for some function
$$h:[a^{'}, b{'}] \rightarrow [a,b]$$
such that $\dot{h} \geq 0$, $h(a^{'}) = a$, $h(b^{'}) = b$
```

^2f90b6

Reparameterization as the name implies is just a change in parameters. 

Drawing a diagram below of an example, let the start and end points of $\underline{p}$ be:
- $\underline{p}(a) = \underline{a}$
- $\underline{p}(b) = \underline{b}$

```tikz
\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} %set default line width to 0.75pt        

\begin{tikzpicture}[x=0.75pt,y=0.75pt,yscale=-1,xscale=1]
%uncomment if require: \path (0,402); %set diagram left start at 0, and has height of 402

%Straight Lines [id:da3132195782925419] 
\draw    (190.1,74.3) -- (190,243) ;
%Curve Lines [id:da7249822784379534] 
\draw    (216.1,203.3) .. controls (246.1,132.3) and (304.1,165.3) .. (328.1,108.3) ;
%Straight Lines [id:da5905464652205623] 
\draw    (174.1,230.3) -- (369.1,230.3) ;
%Straight Lines [id:da9213242215472403] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ] [dash pattern={on 0.84pt off 2.51pt}]  (216.1,203.3) -- (216.1,233.3) ;
%Straight Lines [id:da6322209534625715] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ] [dash pattern={on 0.84pt off 2.51pt}]  (328.1,108.3) -- (329.1,234.3) ;
%Straight Lines [id:da028552610850507087] 
\draw [color={rgb, 255:red, 74; green, 144; blue, 226 }  ,draw opacity=1 ] [dash pattern={on 0.84pt off 2.51pt}]  (187.1,108.3) -- (328.1,108.3) ;
%Straight Lines [id:da7038174147820293] 
\draw [color={rgb, 255:red, 74; green, 144; blue, 226 }  ,draw opacity=1 ] [dash pattern={on 0.84pt off 2.51pt}]  (185.1,203.3) -- (216.1,203.3) ;

% Text Node
\draw (211,230) node [anchor=north west][inner sep=0.75pt]  [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,opacity=1 ] [align=left] {$\displaystyle a$};
% Text Node
\draw (322,234) node [anchor=north west][inner sep=0.75pt]  [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,opacity=1 ] [align=left] {$\displaystyle b$};
% Text Node
\draw (166,194) node [anchor=north west][inner sep=0.75pt]  [color={rgb, 255:red, 74; green, 144; blue, 226 }  ,opacity=1 ] [align=left] {$\displaystyle a^{'}$};
% Text Node
\draw (166,87) node [anchor=north west][inner sep=0.75pt]  [color={rgb, 255:red, 74; green, 144; blue, 226 }  ,opacity=1 ] [align=left] {$\displaystyle b^{'}$};


\end{tikzpicture}

\end{document}
```
This is an example of a function $h$. 
**Note:** The derivative of $h$, $\dot{h} \geq 0$ which means $h$ is an **increasing function**.

## Further Notes
---
- [[Parametric Curves as Equivalence Relations]]
# Backlinks
---
- [[Curves]]
- [[Vector & Complex Calculus - MAT00047I Outline]]