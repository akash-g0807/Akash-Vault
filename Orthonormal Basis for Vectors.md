# Orthonormal Basis For Vectors
---

The standard **orthonormal basis vectors** for $\mathbb{E}^3$ is a collection of 3 **unit** vectors denoted:

$$\{\underline{i}, \space \underline{j}, \space \underline{k}\}$$
with the following properties:

$$\begin{equation*}
\underline{i} = \begin{bmatrix} 1\\0\\0\end{bmatrix} \ \ \ \ \ \ \ \ \ \ \ \ \
\underline{j} = \begin{bmatrix} 0\\1\\0\end{bmatrix} \ \ \ \ \ \ \ \ \ \ \ \ \
\underline{k} = \begin{bmatrix} 0\\0\\1\end{bmatrix}
\end{equation*}$$

```tikz
\usepackage{tikz-3dplot}

\begin{document}
\tdplotsetmaincoords{70}{110} % Set the viewing angle

\begin{tikzpicture}[tdplot_main_coords, scale=1.25]
    % Axes
    \coordinate (O) at (0,0,0);
    \draw[thick,->] (O) -- (2,0,0) node[anchor=north east]{$x$};
    \draw[thick,->] (O) -- (0,2,0) node[anchor=north west]{$y$};
    \draw[thick,->] (O) -- (0,0,2) node[anchor=south]{$z$};

    % Unit vectors
    \draw[thick,red,->] (O) -- (1,0,0) node[anchor=north]{$\hat{i}$};
    \draw[thick,blue,->] (O) -- (0,1,0) node[anchor=east]{$\hat{j}$};
    \draw[thick,green,->] (O) -- (0,0,1) node[anchor=south]{$\hat{k}$};
\end{tikzpicture}
\end{document}
```

Any vector can be *represented* by the standard unit vectors. From the following diagram:

```tikz
\usepackage{tikz-3dplot} 
\usetikzlibrary{calc} 
\begin{document} 
\tdplotsetmaincoords{70}{110} 
% Set the viewing angle 
\begin{tikzpicture}[tdplot_main_coords, scale=2] 
% Axes 
\coordinate (O) at (0,0,0); 
\draw[thick,->] (O) -- (2,0,0) node[anchor=north east]{$x$}; 
\draw[thick,->] (O) -- (0,2,0) node[anchor=north west]{$y$}; 
\draw[thick,->] (O) -- (0,0,2) node[anchor=south]{$z$}; 

% Random vector 'a' 
\coordinate (A) at ({5*rand},{5*rand},{5*rand}); % Random vector 'a' 
\draw[thick,orange,->] (O) -- (A) node[anchor=south]{$\mathbf{\underline{a}}$}; 

% Unit vectors 
\draw[thick,red,->] (O) -- (1,0,0) node[anchor=north]{$\hat{i}$}; 
\draw[thick,blue,->] (O) -- (0,1,0) node[anchor=east]{$\hat{j}$}; 
\draw[thick,green,->] (O) -- (0,0,1) node[anchor=south]{$\hat{k}$}; 
\end{tikzpicture}
\end{document}
```
The vector $\underline{a}$ can be written as:
$$\underline{a} = a_{1}\space\underline{i} \space  + \space a_{2}\space\underline{j} \space + \space a_{3}\space\underline{k}$$
where the ***components*** of vector $\underline{a}$ can be written in terms of [[Scalar Product]]

$$\begin{equation*}
a_{1}= \underline{a} \cdot\underline{i} \ \ \ \ \ \ \ \ \ \ \ \ \
a_{2}= \underline{a} \cdot\underline{j} \ \ \ \ \ \ \ \ \ \ \ \ \
a_{3}= \underline{a} \cdot\underline{k} \ \ \ \ \ \ \ \ \ \ \ \ \
\end{equation*}$$


### Alternative Notation for Basis vectors

We can change the notation slightly by setting:

$$\begin{equation*}
\underline{e_{1}} = \underline{i} \ \ \ \ \ \ \ \ \ \ \ \ \
\underline{e_{2}}= \underline{j} \ \ \ \ \ \ \ \ \ \ \ \ \
\underline{e_{3}}= \underline{k} \ \ \ \ \ \ \ \ \ \ \ \ \
\end{equation*}$$


