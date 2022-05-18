---
layout: post
title: "MathJax link"
date: "2022-05-17 08:54:22"
categories: 
 - blog 
mathjax: true 
# key: false 
tags:
 - blog
 - math
 - no-style-please2
---

# mathjax $E=MC^2$

$$
\begin{bmatrix}
  F_n \\ 
  F_{n-1}
\end{bmatrix}
= A \begin{bmatrix}
  F_{n-1} \\ 
  F_{n-2}
\end{bmatrix}
$$

# link to other blog
{%post_link encrypt blog 2:123 %}

{%post_link BlogNotExist %}


```
{% raw %}
{%post_link encrypt blog 2:123   %}
{% endraw %}
```
# image
```
{% raw %}
{% asset_img nahan.png %}
{% endraw %}
```
{% asset_img nahan.png %}


 