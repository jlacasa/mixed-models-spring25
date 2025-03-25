---
title: Workshop Prep
nav: Prep
topics: Software; Notation
---

Welcome!  

Getting ready for the workshop is entirely optional, 
but if you just can't wait to start learning more about mixed models, 
here are a few helpful resources. 
Whether you want to explore the software we’ll use or get familiar with key notation, 
this is optional, but a good starting point. 

-------------

- **Install R and RStudio:** Install [R](https://cran.r-project.org/){:target="_blank" rel="noopener"} and [RStudio](https://posit.co/download/rstudio-desktop/){:target="_blank" rel="noopener"}.
- **Install these R packages:** We'll need `tidyverse`, `glmmTMB`, `DHARMa`, `car`, `emmeans`, `multcomp`, and `agridat`.
- **Check out R for Data Science** [(Garrett Grolemund and Hadley Wickham, 2016)](https://r4ds.hadley.nz/) is a free online book that 
contains basic and advanced information about R programming. 

-------------

{% capture text %}
**Notation we will use in this workshop**
**DON'T PANIC** when you see the math notation. 
It is **not expected** that you walk out of this workshop as a math notation wizard! 

-   **scalars:** lowercase italic and non-bold faced, e.g., $$y$$, $$\sigma$$, $$\beta_0$$.  
-   **vectors:** lowercase bold, e.g., $$\mathbf{y} \equiv [y_1, y_2, ..., y_n]'$$, $$\boldsymbol{\beta} \equiv [\beta_1, \beta_2, ..., \beta_p]'$$, $$\boldsymbol{u}  \equiv [u_1, u_2, ..., u_k]'$$ (note that their elements may be scalars).  
-   **matrices:** uppercase bold, e.g., $$\mathbf{X}$$, $$\Sigma$$ (note that their elements may be vectors).  

*Examples:*   


| Variable | Scalar | Vector | Matrix |
|------------------|------------------|------------------|------------------|
| Response variable | $$y$$ (e.g., $$y = 4$$) | $$\mathbf{y} \equiv (y_1, y_2, ..., y_n)'$$ | $$\mathbf{y}_{n\times1}$$ |
| Predictor variable | $$x_{1 i}$$, $$x_{2 i}$$, etc. | $$\mathbf{x}_1 \equiv (x_{1,1}, x_{1, 2}, ..., x_{1, n})$$ $$\mathbf{x}_2 \equiv (x_{2,1}, x_{2, 2}, ..., x_{2, n})$$ | $$\mathbf{X}_{n\times p}$$ |
| Effect parameters | $$\beta_0$$, $$\beta_1$$, etc. | $$\boldsymbol{\beta} \equiv (\beta_0, \beta_1, ..., \beta_p)'$$ | $$\boldsymbol{\beta}_{p\times1}$$ |
| Variance | $$\sigma^2$$ |  | $$\Sigma$$ (very often we assume $$\Sigma = \sigma^2 \mathbf{I}$$ ) |

{% endcapture %}
{% include alert.html text=text color=secondary %}  


