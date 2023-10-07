# Kinematics-Velocity and Acceleration
---

In [[Position of a particle|position vector]] $\underline{r}$ assuming that the [[Orthonormal Basis for Vectors|unit vectors]] $\underline{i}, \underline{j}$ and $\underline{k}$ are **constant**, we can write **velocity** and **acceleration** in the following way:

### Velocity
---
```tikz
\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} %set default line width to 0.75pt        

\begin{tikzpicture}[x=0.75pt,y=0.75pt,yscale=-1,xscale=1]
%uncomment if require: \path (0,402); %set diagram left start at 0, and has height of 402

%Curve Lines [id:da7249822784379534] 
\draw    (108.1,195.3) .. controls (184.1,20.3) and (284.1,243.3) .. (403.1,67.3) ;
%Straight Lines [id:da07486429812279405] 
\draw    (203.5,258.3) -- (205.37,127.7) ;
\draw [shift={(205.4,125.7)}, rotate = 90.82] [color={rgb, 255:red, 0; green, 0; blue, 0 }  ][line width=0.75]    (10.93,-3.29) .. controls (6.95,-1.4) and (3.31,-0.3) .. (0,0) .. controls (3.31,0.3) and (6.95,1.4) .. (10.93,3.29)   ;
%Shape: Circle [id:dp6919219182514531] 
\draw  [fill={rgb, 255:red, 0; green, 0; blue, 0 }  ,fill opacity=1 ] (202,125.7) .. controls (202,123.82) and (203.52,122.3) .. (205.4,122.3) .. controls (207.28,122.3) and (208.8,123.82) .. (208.8,125.7) .. controls (208.8,127.58) and (207.28,129.1) .. (205.4,129.1) .. controls (203.52,129.1) and (202,127.58) .. (202,125.7) -- cycle ;
%Shape: Circle [id:dp2798104629473662] 
\draw  [fill={rgb, 255:red, 0; green, 0; blue, 0 }  ,fill opacity=1 ] (200.1,258.3) .. controls (200.1,256.42) and (201.62,254.9) .. (203.5,254.9) .. controls (205.38,254.9) and (206.9,256.42) .. (206.9,258.3) .. controls (206.9,260.18) and (205.38,261.7) .. (203.5,261.7) .. controls (201.62,261.7) and (200.1,260.18) .. (200.1,258.3) -- cycle ;
%Shape: Circle [id:dp4797202017377725] 
\draw  [fill={rgb, 255:red, 0; green, 0; blue, 0 }  ,fill opacity=1 ] (244,132.7) .. controls (244,130.82) and (245.52,129.3) .. (247.4,129.3) .. controls (249.28,129.3) and (250.8,130.82) .. (250.8,132.7) .. controls (250.8,134.58) and (249.28,136.1) .. (247.4,136.1) .. controls (245.52,136.1) and (244,134.58) .. (244,132.7) -- cycle ;
%Straight Lines [id:da797119100975235] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (203.5,258.3) -- (246.74,134.59) ;
\draw [shift={(247.4,132.7)}, rotate = 109.27] [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ][line width=0.75]    (10.93,-3.29) .. controls (6.95,-1.4) and (3.31,-0.3) .. (0,0) .. controls (3.31,0.3) and (6.95,1.4) .. (10.93,3.29)   ;
%Straight Lines [id:da3151106945356048] 
\draw [color={rgb, 255:red, 126; green, 211; blue, 33 }  ,draw opacity=1 ]   (205.4,125.7) -- (245.43,132.37) ;
\draw [shift={(247.4,132.7)}, rotate = 189.46] [color={rgb, 255:red, 126; green, 211; blue, 33 }  ,draw opacity=1 ][line width=0.75]    (10.93,-3.29) .. controls (6.95,-1.4) and (3.31,-0.3) .. (0,0) .. controls (3.31,0.3) and (6.95,1.4) .. (10.93,3.29)   ;

% Text Node
\draw (213,245) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle O$};
% Text Node
\draw (201,96) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle P$};
% Text Node
\draw (172,177) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle \underline{r}( t)$};
% Text Node
\draw (229,183) node [anchor=north west][inner sep=0.75pt]  [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,opacity=1 ] [align=left] {$\displaystyle \underline{r}( t\ +\ \delta t)$};
% Text Node
\draw (221,105) node [anchor=north west][inner sep=0.75pt]  [color={rgb, 255:red, 126; green, 211; blue, 33 }  ,opacity=1 ] [align=left] {$\displaystyle \delta \underline{r}$};


\end{tikzpicture}

\end{document}
```

From the diagram above:
$$\delta\underline{r} = \underline{r}(t+\delta t) - \underline{r}(t) $$
Dividing by $\delta t$ and taking the **limit** as $\delta \rightarrow 0$ we get
$$\dot{\underline{r}}(t) = \underline{v}(t) = \lim_{\delta t \to 0}\bigg(\frac{\underline{r}(t + \delta t) - \underline{r}(t)}{\delta t}\bigg)$$
```ad-Definition

$$\begin{split} \dot{\underline{r}} = \frac{d\underline{r}(t)}{dt}  = \lambda \dot{\underline{e_{a}}} = \dot{x}\underline{i} + \dot{y}\underline{j} +\dot{z}\underline{k}\end{split}$$
```

### Acceleration
---

Similarly **acceleration** can be defined in the following way:

```ad-Definition
$$\begin{split} \ddot{\underline{r}} = \frac{d\dot{\underline{r}}(t)}{dt}  = \lambda \ddot{\underline{e_{a}}} = \ddot{x}\underline{i} + \ddot{y}\underline{j} +\ddot{z}\underline{k}\end{split}$$
```

In terms of **limits**

$$\ddot{\underline{r}}(t) = \dot{\underline{v}}(t) = \underline{a}(t) = \lim_{\delta t \to 0}\bigg(\frac{\underline{v}(t + \delta t) - \underline{v}(t)}{\delta t}\bigg)$$

# Backlinks
---
- [[Newtonian Mechanics]]