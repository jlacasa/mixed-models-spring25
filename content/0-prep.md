---
title: Workshop Prep
nav: Prep
topics: Software; Notation
---

Welcome!  

Although preparing for this workshop is only optional, here are some points for those who just can't wait to learn more about mixed models. 

-------------

- **Install R and RStudio:** Install [R](https://cran.r-project.org/){:target="_blank" rel="noopener"} and [RStudio](https://posit.co/download/rstudio-desktop/){:target="_blank" rel="noopener"}.
- **Install these R packages:** We'll need `tidyverse`, `glmmTMB`, `emmeans`, and `multcomp`.

-------------

{% capture text %}
**Notation we will use in this workshop**

-   scalars: lowercase italic and non-bold faced, e.g., $$y$$, $$\sigma$$, $$\beta_0$$  
-   vectors: lowercase bold, e.g., $$\mathbf{y} \equiv [y_1, y_2, ..., y_n]'$$, $$\boldsymbol{\beta} \equiv [\beta_1, \beta_2, ..., \beta_p]'$$, $$\boldsymbol{u}  \equiv [u_1, u_2, ..., u_k]'$$ (note that their elements may be scalars)  
-   matrices: uppercase bold, e.g., $$\mathbf{X}$$, $$\Sigma$$ (note that their elements may be vectors)  

*Examples:*   

<table style="border-collapse: collapse; width: 100%; text-align: center;">
  <tr style="border-bottom: 2px solid black;">
    <th>Variable</th>
    <th>Scalar</th>
    <th>Vector</th>
    <th>Matrix</th>
  </tr>
  <tr style="border-bottom: 1px solid black;">
    <td>Response variable</td>
    <td>$$y$$ (e.g., $$y = 4$$)</td>
    <td>$$\mathbf{y} \equiv (y_1, y_2, ..., y_n)'$$</td>
    <td>$$\mathbf{y}_{n\times1}$$</td>
  </tr>
  <tr style="border-bottom: 1px solid black;">
    <td>Predictor variable</td>
    <td>$$x_{1 i}$$, $$x_{2 i}$$, etc.</td>
    <td>$$\mathbf{x}_1 \equiv (x_{1,1}, x_{1, 2}, ..., x_{1, n})$$<br>
        $$\mathbf{x}_2 \equiv (x_{2,1}, x_{2, 2}, ..., x_{2, n})$$</td>
    <td>$$\mathbf{X}_{n\times p} \equiv \begin{bmatrix} \end{bmatrix}$$</td>
  </tr>
  <tr style="border-bottom: 1px solid black;">
    <td>Effect parameters</td>
    <td>$$\beta_0$$, $$\beta_1$$, etc.</td>
    <td>$$\boldsymbol{\beta} \equiv (\beta_0, \beta_1, ..., \beta_p)'$$</td>
    <td>$$\boldsymbol{\beta}_{p\times1}$$</td>
  </tr>
  <tr style="border-bottom: 1px solid black;">
    <td>Variance</td>
    <td>$$\sigma^2$$</td>
    <td></td>
    <td>$$\Sigma$$ (very often we assume $$\Sigma = \sigma^2 \mathbf{I}$$ )</td>
  </tr>
</table>

{% endcapture %}
{% include alert.html text=text color=secondary %}  



| title | title {% newline %}
|--------|------- {% newline %}
| content | content {% newline %}
|^^Total^^|^^Total^^{% newline %}
