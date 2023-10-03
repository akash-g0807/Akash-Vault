# Continuity on Open Sets Intro
---

``` ad-Definition

For $\mathcal{U} \subseteq \mathbb{R}^n$ [[Intro to Open Sets| open set]], a function 
$$\underline{f}: \mathcal{U} \rightarrow \mathbb{R}^m $$ 
is *continuous* if for any open set $\mathcal{V} \subseteq \mathbb{R}^m$, the subset 
$$\underline{f}^{-1}\ \mathcal{V} := \{\underline{x} \in \mathcal{U} \mid \underline{f}(\underline{x}) \in \mathcal{V}\} \subseteq \mathbb{R}^n$$

```

- A **continuous function** is also called a **map**.  ^7d419f
- The set of maps $\underline{f}: \mathcal{U} \rightarrow \mathbb{R}^m$ is denoted 
$$\mathcal{C}(\ \mathcal{U}, \mathbb{R}^{n} \ )$$

*Note*: As with functions of a single variable, the idea of continuity is that if $\underline{x}$ and $\underline{y}$ are *sufficiently close* together, then $\underline{f}(\underline{x})$ and $\underline{f}(\underline{y})$ will be *sufficiently close* together. There are no sudden jumps in the values of $\underline{f}$.