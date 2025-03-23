---
title: Workshop Prep
nav: Prep
topics: Software; Optional Readings
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
-   vectors: lowercase bold, e.g., $$\mathbf{y} \equiv [y_1, y_2, ..., y_n]'$, $\boldsymbol{\beta} \equiv [\beta_1, \beta_2, ..., \beta_p]'$$, $$\boldsymbol{u}  \equiv [u_1, u_2, ..., u_k]'$$ (note that their elements may be scalars)  
-   matrices: uppercase bold, e.g., $$\mathbf{X}$$, $$\Sigma$$ (note that their elements may be vectors)  

*Examples:*  
| Variable | Scalar | Vector | Matrix |
|------------------|------------------|------------------|------------------|
| Response variable | $$y$$ (e.g., $$y = 4$$) | $$\mathbf{y} \equiv (y_1, y_2, ..., y_n)'$$ | $$\mathbf{y}_{n\times1}$$ |
| Predictor variable | $$x_{1 i}$$, $$x_{2 i}$$, etc. | $$\mathbf{x}_1 \equiv (x_{1,1}, x_{1, 2}, ..., x_{1, n})$$ $$\mathbf{x}_2 \equiv (x_{2,1}, x_{2, 2}, ..., x_{2, n})$$ | $$\mathbf{X}_{n\times p} \equiv \begin{bmatrix} \end{bmatrix}$$ |
| Effect parameters | $$\beta_0$$, $$\beta_1$$, etc. | $$\boldsymbol{\beta} \equiv (\beta_0, \beta_1, ..., \beta_p)'$$ | $$\boldsymbol{\beta}_{p\times1}$$ |
| Variance | $$\sigma^2$$ |  | $$\Sigma$$ (very often we assume $$\Sigma = \sigma^2 \mathbf{I}$$ ) |
|  |  |  |  |{% endcapture %}
{% include alert.html text=text color=secondary %}  


