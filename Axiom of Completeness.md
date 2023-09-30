# Axiom of Completeness
---
The **Axiom of Completeness** is an important property of the real numbers as it *encapsulates* the idea of **NO GAPS**  on the real line.

```ad-Axiom
Title: **Axiom of Completeness**

Suppose $A$ and $B$ are non-empty subsets of $R$ i.e. $A \neq \emptyset$ and $B \neq \emptyset$ and $A, B \subseteq \mathbb{R}$ with the property that if $a \in A$ and $b \in B$, then $a \leq b$ 

Then *there exists* $c \in \mathbb{R}$ such that **for all** $a \in A$ and $b \in B$, 
$$a \leq c \leq b$$
```

```tikz
\begin{document}


\tikzset{every picture/.style={line width=0.75pt}} %set default line width to 0.75pt        

\begin{tikzpicture}[x=0.75pt,y=0.75pt,yscale=-1,xscale=1]
%uncomment if require: \path (0,402); %set diagram left start at 0, and has height of 402

%Straight Lines [id:da8922048683708794] 
\draw    (141.1,240.3) -- (438.1,240.3) ;
%Straight Lines [id:da36352049321247937] 
\draw    (141.1,270.3) -- (438.1,270.3) ;
%Shape: Rectangle [id:dp9716199715476529] 
\draw  [fill={rgb, 255:red, 0; green, 0; blue, 0 }  ,fill opacity=1 ] (178,232) -- (220.1,232) -- (220.1,248.3) -- (178,248.3) -- cycle ;
%Shape: Rectangle [id:dp9872960498100054] 
\draw  [fill={rgb, 255:red, 0; green, 0; blue, 0 }  ,fill opacity=1 ] (240,232) -- (266.1,232) -- (266.1,248.3) -- (240,248.3) -- cycle ;
%Shape: Rectangle [id:dp29970155617755545] 
\draw  [fill={rgb, 255:red, 0; green, 0; blue, 0 }  ,fill opacity=1 ] (276.55,232.15) -- (293.1,232.15) -- (293.1,248.3) -- (276.55,248.3) -- cycle ;
%Straight Lines [id:da06994738144421009] 
\draw [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ]   (310.1,197.3) -- (310,294) ;
%Shape: Rectangle [id:dp57977582896997] 
\draw  [fill={rgb, 255:red, 0; green, 0; blue, 0 }  ,fill opacity=1 ] (177,262) -- (309.1,262) -- (309.1,278.3) -- (177,278.3) -- cycle ;
%Shape: Rectangle [id:dp2278217118695144] 
\draw  [fill={rgb, 255:red, 0; green, 0; blue, 0 }  ,fill opacity=1 ] (311.1,262) -- (443.2,262) -- (443.2,278.3) -- (311.1,278.3) -- cycle ;
%Shape: Rectangle [id:dp47167993671338804] 
\draw  [fill={rgb, 255:red, 0; green, 0; blue, 0 }  ,fill opacity=1 ] (325.55,232.15) -- (342.1,232.15) -- (342.1,248.3) -- (325.55,248.3) -- cycle ;
%Shape: Rectangle [id:dp5549839217552961] 
\draw  [fill={rgb, 255:red, 0; green, 0; blue, 0 }  ,fill opacity=1 ] (364,232) -- (432.1,232) -- (432.1,248.3) -- (364,248.3) -- cycle ;

% Text Node
\draw (229,195) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle A$};
% Text Node
\draw (228,290) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle A$};
% Text Node
\draw (381,284) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle B$};
% Text Node
\draw (374,195) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle B$};
% Text Node
\draw (310,294) node [anchor=north west][inner sep=0.75pt]  [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,opacity=1 ] [align=left] {$\displaystyle c$};


\end{tikzpicture}

\end{document}
```
In terms of bounds:
- Every **element of $A$ is a [[Boundedness of Sets#^cbfd30|lowerbound]] for $B$** and **every element of $B$ is an [[Boundedness of Sets#^49715c|upperbound]] for $A$**
- This property of $\mathbb{R}$ is called completeness. 

We can use the property of **completeness** to define and prove [[Infimum and Supremum#^6ee25d| infimum and supremum]].