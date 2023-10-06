# Maximum and Minimum Element
---
We define the **maximum and minimum** element of  a **set** $S \subseteq \mathbb{K}$. (i.e. $S$ is a subset of an ordered filed $\mathbb{K}$).

```ad-Definition
TItle: **Maximum/Maximal Element**

Suppose $S \subseteq \mathbb{K}$. We say that $S$ is has a **maximal/maximum** element denoted $\max(S)$ if it contains an element larger than all other elements, that is an [[Boundedness of Sets#^49715c|upperbound]] $b$ which is an element of $S$. 

$\max(S)$ is an upperbound of $S$ that is an element of $S$ i.e.

$$\max(S) \in S \ \ \ \ \ \ \text{and} \ \ \ \ \ \ \ x \leq \max(S) \ \ \ \ \ \forall x \in S$$
```


```ad-Definition
TItle: **Minimum/Minimal Element**

Suppose $S \subseteq \mathbb{K}$. We say that $S$ is has a **minimal/minimum** element denoted $\min(S)$ if it contains an element smaller than all other elements, that is an [[Boundedness of Sets#^cbfd30|lowerbound]] $a$ which is an element of $S$. 

$\min(S)$ is a lowerbound of $S$ that is an element of $S$ i.e.

$$\min(S) \in S \ \ \ \ \ \ \text{and} \ \ \ \ \ \ \ x \geq \min(S) \ \ \ \ \ \forall x \in S$$
```

*Note:* Unlike [[Boundedness of Sets#^49715c|upperbound]] and [[Boundedness of Sets#^cbfd30|lowerbound]], maximum and minimum elements **ARE UNIQUE**, if they exist at all.

To see this, suppose that $b_{1}$ and $b_{2}$ are **maximal elements** of $S$. Then they are *both* **elements of** $S$ and both **upperbounds of** $S$. This means that 

```tikz
\begin{document}

\tikzset{every picture/.style={line width=0.75pt}} %set default line width to 0.75pt        

\begin{tikzpicture}[x=0.75pt,y=0.75pt,yscale=-1,xscale=1]
%uncomment if require: \path (0,402); %set diagram left start at 0, and has height of 402


% Text Node
\draw (120,148) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle b_{1} \ \ \ \ \ \ \leq \ \ \ \ \ \ b_{2}$};
% Text Node
\draw (70,173) node [anchor=north west][inner sep=0.75pt]  [color={rgb, 255:red, 74; green, 144; blue, 226 }  ,opacity=1 ] [align=left] {element of $\displaystyle S$};
% Text Node
\draw (184,170) node [anchor=north west][inner sep=0.75pt]  [color={rgb, 255:red, 74; green, 144; blue, 226 }  ,opacity=1 ] [align=left] {upperbound of $\displaystyle S$};
% Text Node
\draw (119,208) node [anchor=north west][inner sep=0.75pt]   [align=left] {$\displaystyle b_{2} \ \ \ \ \ \ \leq \ \ \ \ \ \ b_{1}$};
% Text Node
\draw (69,233) node [anchor=north west][inner sep=0.75pt]  [color={rgb, 255:red, 74; green, 144; blue, 226 }  ,opacity=1 ] [align=left] {element of $\displaystyle S$};
% Text Node
\draw (183,230) node [anchor=north west][inner sep=0.75pt]  [color={rgb, 255:red, 74; green, 144; blue, 226 }  ,opacity=1 ] [align=left] {upperbound of $\displaystyle S$};


\end{tikzpicture}

\end{document}
```
and therefore we can conclude that $b_{1} = b_{2}$. 
The argument for minimum element is similar

# Backlinks
---
- [[Review of Real Analysis]]