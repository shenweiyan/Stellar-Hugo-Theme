---
title: MathJax 支持
categories: [建站]
tags: [Hugo, MathJax]
date: 2023-02-12
description: 本篇教程收集了让 MathJax 在 Hugo 构建的网站上工作的一些的提示和技巧。
---

## Inline Math

``` mathjax {title=Example render = true}
$abc$ $e^{\pi i}=-1$ $\frac{3}{2}$
```

## Display Math

``` mathjax {title=Example render = true}
$$
\sum_{i=1}^{n}\int_{0}^{\pi}\log_2{e^n}
$$
```

## Using Latex Codeblock

    ``` latex
    f(n)=
    \begin{cases}
        f(n-1)+f(n-2) & n \ge 3 \\
        1 & n=1,2
    \end{cases}
    ```

``` latex
f(n)=
\begin{cases}
    f(n-1)+f(n-2) & n \ge 3 \\
    1 & n=1,2
\end{cases}
```
