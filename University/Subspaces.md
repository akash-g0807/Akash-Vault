# Subspaces
---

```ad-Definition

Title: **Subspaces**

Let $(X,d)$ and $(Y,d^{'})$ be [[General Definition of Metric Spaces#^eb87d4|metric spaces]]. We say that $(Y,d^{'})$ is a **subspace**
of $(X,d)$ if:
1. $Y \subseteq X$;
2. $d^{'} = d \mid Y \times Y$ 

So all axioms of metrix spaces hold in $Y$ and
$$(Y, d^{'})$$
is a metric space
```

*Note*: 
1. $d^{'} = d \mid Y \times Y$ means that the distance function $d^{'}$ is **restricted** to the set $Y \times Y$ and can also be denoted $d\mid_{Y}$.
2. We call $X$ the **ambient space**.
3. **REMEMBER:** Subset DOES NOT MEAN subspace.

```tikz
\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} %set default line width to 0.75pt        

\begin{tikzpicture}[x=0.75pt,y=0.75pt,yscale=-1,xscale=1]
%uncomment if require: \path (0,300); %set diagram left start at 0, and has height of 300

%Shape: Polygon Curved [id:ds6979508109231568] 
\draw   (167.83,110.5) .. controls (165.83,42.5) and (250.83,54.5) .. (310.83,109.5) .. controls (370.83,164.5) and (379.83,108.5) .. (420.83,109.5) .. controls (461.83,110.5) and (448.83,203.5) .. (413.83,244.5) .. controls (378.83,285.5) and (183.83,269.5) .. (177.83,216.5) .. controls (171.83,163.5) and (169.83,178.5) .. (167.83,110.5) -- cycle ;
%Shape: Polygon Curved [id:ds38992034422558886] 
\draw  [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ] (246,155) .. controls (266,145) and (356,135) .. (336,155) .. controls (316,175) and (316,185) .. (336,215) .. controls (356,245) and (266,245) .. (246,215) .. controls (226,185) and (226,165) .. (246,155) -- cycle ;
%Shape: Circle [id:dp14331387539559937] 
\draw  [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ] (271.5,189.75) .. controls (271.5,183.26) and (276.76,178) .. (283.25,178) .. controls (289.74,178) and (295,183.26) .. (295,189.75) .. controls (295,196.24) and (289.74,201.5) .. (283.25,201.5) .. controls (276.76,201.5) and (271.5,196.24) .. (271.5,189.75) -- cycle ;

% Text Node
\draw (176,90) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle X$};
% Text Node
\draw (231,132) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle Y$};


\end{tikzpicture}

\end{document}
```

## Further Notes
---
- [[Examples of Subspaces]]

# Backlinks
---
- [[Subspaces and Equivalence of Metric Spaces]]
