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
- **Check out R for Data Science** (Garrett Grolemund and Hadley Wickham, 2016) is a free online book that 
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

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Notation Table</title>
    <style>
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 8px;
            text-align: left;
        }
        th {
            background-color: #f4f4f4;
            font-weight: bold;
        }
        tr:nth-child(even) {
            background-color: #f9f9f9;
        }
    </style>
</head>

<body>
    <table>
        <tr>
            <th>Variable</th>
            <th>Scalar</th>
            <th>Vector</th>
            <th>Matrix</th>
        </tr>
        <tr>
            <td>Response variable</td>
            <td>$$y$$ (e.g., $$y = 4$$)</td>
            <td>$$\mathbf{y} \equiv (y_1, y_2, ..., y_n)'$$</td>
            <td>$$\mathbf{y}_{n\times1}$$</td>
        </tr>
        <tr>
            <td>Predictor variable</td>
            <td>$$x_{1 i}$$, $$x_{2 i}$$, etc.</td>
            <td>
                $$\mathbf{x}_1 \equiv (x_{1,1}, x_{1,2}, ..., x_{1,n})$$ <br>
                $$\mathbf{x}_2 \equiv (x_{2,1}, x_{2,2}, ..., x_{2,n})$$
            </td>
            <td>$$\mathbf{X}_{n\times p}$$</td>
        </tr>
        <tr>
            <td>Effect parameters</td>
            <td>$$\beta_0$$, $$\beta_1$$, etc.</td>
            <td>$$\boldsymbol{\beta} \equiv (\beta_0, \beta_1, ..., \beta_p)'$$</td>
            <td>$$\boldsymbol{\beta}_{p\times1}$$</td>
        </tr>
        <tr>
            <td>Variance</td>
            <td>$$\sigma^2$$</td>
            <td></td>
            <td>$$\Sigma$$ (very often we assume $$\Sigma = \sigma^2 \mathbf{I}$$)</td>
        </tr>
    </table>
</body>

{% endcapture %}
{% include alert.html text=text color=secondary %}  


