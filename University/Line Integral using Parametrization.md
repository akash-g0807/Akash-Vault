# Line Integral using Parametrization
---

```ad-Theorem

Title: **Line Integral using Parametrization**

The [[Line Integrals|line integral]] of a [[Scalar and Vector Fields|vector field]] $\underline{g}$ along curve $C$ in $\mathbb{R}^n$ is
$$\int_{C}\underline{g}(\underline{x})\cdot d\underline{x} = \int_{a}^{b}\underline{g}(\underline{p}(t)) \cdot \underline{\dot{p}}(t)dt$$
for any [[Oriented Curves#^a5558f|parametrization]] using [[Parametric Curves|parametric curve]] $\underline{p}:[a,b] \rightarrow  \mathbb{R}^n$ of $C$
```

`\begin{proof}`
To and try and compute the line integral of $\underline{g}$ along $C$, we can try breaking $C$ into small pieces.
Let $\underline{x}_{0}, \underline{x}_{1}, \ldots \underline{x}_{N}$ be points on $C$ ordered with respect to [[Oriented Curves|orientation]] with $x_{0}$ be at the beginning and $x_{N}$ at the end of $C$.  
```tikz
\begin{document}


\tikzset{every picture/.style={line width=0.75pt}} %set default line width to 0.75pt        

\begin{tikzpicture}[x=0.75pt,y=0.75pt,yscale=-1,xscale=1]
%uncomment if require: \path (0,402); %set diagram left start at 0, and has height of 402

%Curve Lines [id:da7080647742603929] 
\draw    (87.94,286.98) .. controls (326.99,-71.16) and (345.1,397.07) .. (537.06,25.67) ;
%Shape: Ellipse [id:dp8753266493222388] 
\draw  [color={rgb, 255:red, 0; green, 0; blue, 0 }  ,draw opacity=1 ][fill={rgb, 255:red, 0; green, 0; blue, 0 }  ,fill opacity=1 ] (83.05,286.98) .. controls (83.05,284.01) and (85.24,281.61) .. (87.94,281.61) .. controls (90.64,281.61) and (92.83,284.01) .. (92.83,286.98) .. controls (92.83,289.94) and (90.64,292.35) .. (87.94,292.35) .. controls (85.24,292.35) and (83.05,289.94) .. (83.05,286.98) -- cycle ;
%Shape: Ellipse [id:dp7030608029641903] 
\draw  [color={rgb, 255:red, 0; green, 0; blue, 0 }  ,draw opacity=1 ][fill={rgb, 255:red, 0; green, 0; blue, 0 }  ,fill opacity=1 ] (532.17,25.67) .. controls (532.17,22.71) and (534.36,20.3) .. (537.06,20.3) .. controls (539.76,20.3) and (541.95,22.71) .. (541.95,25.67) .. controls (541.95,28.64) and (539.76,31.04) .. (537.06,31.04) .. controls (534.36,31.04) and (532.17,28.64) .. (532.17,25.67) -- cycle ;
%Straight Lines [id:da48029003375992374] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (188.15,151.77) -- (203.84,174.32) ;
%Straight Lines [id:da27243334042533274] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (176.07,161.06) -- (191.77,183.61) ;
%Straight Lines [id:da32607990099267825] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (83.11,263.19) -- (108.46,281.76) ;
%Straight Lines [id:da5603398108227334] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (91.56,249.93) -- (115.71,269.82) ;
%Straight Lines [id:da3291374187399072] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (162.79,169.01) -- (179.7,192.89) ;
%Straight Lines [id:da08166172435140162] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (154.34,179.63) -- (172.45,203.5) ;
%Straight Lines [id:da8563082383418357] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (100.01,240.64) -- (125.37,260.54) ;
%Straight Lines [id:da27661141104063836] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (202.64,143.81) -- (215.92,166.27) ;
%Straight Lines [id:da8753209042607654] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (217.12,138.51) -- (227.99,162.29) ;
%Straight Lines [id:da5326663622670924] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (498.43,56.27) -- (523.78,74.84) ;
%Straight Lines [id:da3675201339041788] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (256.96,122.5) -- (258.17,154.34) ;
%Straight Lines [id:da9432105844740701] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (227.99,130.46) -- (237.65,159.64) ;
%Straight Lines [id:da7676581055944196] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (267.83,125.24) -- (267.83,153.01) ;
%Straight Lines [id:da08431466561874457] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (491.19,65.55) -- (516.54,84.12) ;
%Straight Lines [id:da2972271243908684] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (242.48,127.81) -- (248.51,156.99) ;
%Straight Lines [id:da05502690954968548] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (104.84,228.7) -- (130.2,249.93) ;
%Straight Lines [id:da2118433662313184] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (113.29,218.09) -- (137.44,240.64) ;
%Straight Lines [id:da8527533347914183] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (120.54,206.15) -- (144.68,228.7) ;
%Straight Lines [id:da6084769967088949] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (132.61,194.22) -- (154.34,218.09) ;
%Straight Lines [id:da4385357752300898] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (143.48,186.26) -- (162.79,208.81) ;
%Straight Lines [id:da03135847993773255] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (447.72,123.92) -- (473.08,145.05) ;
%Straight Lines [id:da20219995811669378] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (433.23,142.49) -- (456.17,166.27) ;
%Straight Lines [id:da7585426180866847] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (440.48,133.2) -- (464.62,158.31) ;
%Straight Lines [id:da5061042001000496] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (457.38,113.22) -- (483.94,134.44) ;
%Straight Lines [id:da07487705200058359] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (407.88,159.73) -- (409.09,192.8) ;
%Straight Lines [id:da986829014203845] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (352.34,151.68) -- (340.27,182.19) ;
%Straight Lines [id:da42943691517016536] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (395.81,160.97) -- (395.81,192.8) ;
%Straight Lines [id:da6119524013302694] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (340.27,143.72) -- (328.2,175.65) ;
%Straight Lines [id:da8485502080918114] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (326.99,138.42) -- (316.12,170.25) ;
%Straight Lines [id:da4038884263324438] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (313.71,134.44) -- (305.26,163.62) ;
%Straight Lines [id:da005155887255251956] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (302.84,129.13) -- (295.6,160.97) ;
%Straight Lines [id:da9895640862316936] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (291.98,121.17) -- (287.15,159.64) ;
%Straight Lines [id:da32498785240498795] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (464.62,104.02) -- (489.98,122.59) ;
%Straight Lines [id:da8771574336517028] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (278.7,122.5) -- (277.49,156.99) ;
%Straight Lines [id:da14672226695910595] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (473.08,96.06) -- (498.43,114.63) ;
%Straight Lines [id:da37625565838233366] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (480.32,86.78) -- (505.67,105.35) ;
%Straight Lines [id:da7790250389772266] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (485.15,76.16) -- (510.5,94.73) ;
%Straight Lines [id:da22795717477281707] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (517.75,25.76) -- (543.1,44.33) ;
%Straight Lines [id:da37728878139297783] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (504.47,45.66) -- (529.82,64.23) ;
%Straight Lines [id:da7569828624963959] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (510.5,35.05) -- (535.86,53.62) ;
%Straight Lines [id:da5462226707469738] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (366.83,155.66) -- (354.76,190.15) ;
%Straight Lines [id:da12114405007392182] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (388.56,156.99) -- (386.15,195.45) ;
%Straight Lines [id:da6522203333410436] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (378.9,155.66) -- (372.87,194.13) ;
%Straight Lines [id:da6650418932207904] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (421.16,154.42) -- (436.86,186.17) ;
%Straight Lines [id:da21130754817625008] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (415.12,157.08) -- (421.16,192.8) ;
%Straight Lines [id:da58526366081057] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (427.2,149.03) -- (450.14,176.88) ;

% Text Node
\draw (351,181) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle \underline{x}_{k}$};
% Text Node
\draw (370,129) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle \underline{x}_{k+1}$};
% Text Node
\draw (331.19,168.87) node [anchor=north west][inner sep=0.75pt]  [rotate=-32.94] [align=left] {$\displaystyle \underline{x}_{k-1}$};
% Text Node
\draw (550,19) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle \underline{x}_{N}$};
% Text Node
\draw (68,296) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle \underline{x}_{0}$};


\end{tikzpicture}

\end{document}
```
Let $C_k$ be the piece from of $C$ from $\underline{x}_{k-1}$ to $\underline{x}_{k}$, so that
$$C = C_{1} \cup C_{2}\cup C_{3} \cup\cdots \cup C_{N}$$
If these pieces *are small enough*, and $\underline{g}:\mathbb{R}^{n}\rightarrow \mathbb{R}^n$ is continuous, then the value of $\underline{g}$
over a curve segment $C_{k}$ is ***approximately constant*** and therefore, we can approximate the line integral over the segment $C_{k}$ using [[Properties of Line Integrals|property 2]] of line integrals. Therefore we get
$$\begin{aligned} \int_{C}\underline{g}(\underline{x})\cdot d\underline{x} &= \sum\limits_{k=1}^{N}\int_{C_{k}}\underline{g}(\underline{x}) \cdot d\underline{x} \ \ \ \ \ \ \ \ \ \ \ \ \text{property 1} \\ \\
&\approx \sum\limits_{k=1}^{N}\int_{C_k}\underline{g}(\underline{x}_{k}) \cdot d\underline{x}  \ \ \ \ \ \ \  \ \ \ \ \ \ \ \ \   \text{property 2} \\ \\
&= \sum\limits_{k=1}^{N}\underline{g}(\underline{x}_{k}) \cdot (\underline{x}_{k}- \underline{x}_{k-1})  \ \ \ \ \ \ \  \ \ \ \   \text{property 3}\end{aligned}$$
This is the line integral version of a **Riemann sum**. The **line integral** can be defined
as a **limit** of such sums as C is broken into smaller and smaller pieces.

A [[Oriented Curves#^a5558f|parametrization]] is now useful. Suppose that $p : [a, b] \rightarrow \mathbb{R}^n$ is a **parametrization**
of $C$, and $a = t_{0} < t_{1} < \cdots < t_{N−1} < t_{N} = b$ are closely spaced numbers. We can
let $\underline{x}_{k} = \underline{p}(t_{k})$. This gives:
$$\begin{aligned} \int_{C}\underline{g}(\underline{x})\cdot d\underline{x} &\approx \sum\limits_{k=1}^{N}\underline{g}(\underline{p}(t_{k})) \cdot (\underline{p}(t_{k})-\underline{p}(t_{k-1})) \\ \\
&\approx   \sum\limits_{k=1}^{N}\underline{g}(\underline{p}(t_{k})) \cdot \underline{\dot{p}}(t_k)(t_{k} - t_{k-1}) \ \ \ \ \ \ \ \ \ \ \text{Linearization approximation} \\ \\
&\approx \int_{a}^{b}\underline{g}(\underline{p}(t)) \cdot \underline{\dot{p}}(t) \ dt \end{aligned}$$
since the last sum is just a **Riemann sum** for an ordinary integral.
This becomes an equality in the **limit** of breaking $[a, b]$ up into arbitrarily small
pieces, and leads to a practical formula for the line integral
  `\end{proof}`
## Further Notes
---
-  [[Reparameterization in Line Integrals]]
- [[Examples of Line Integrals using Parametrization]]


# Backlinks
---
- [[Line Integrals]]
- [[Vector & Complex Calculus - MAT00047I Outline]]