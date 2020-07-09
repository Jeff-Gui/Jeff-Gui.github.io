---
title: Journal club - cell cycle model and Gamma distribution
categories:
    - computational biology
tags:
    - modeling
    - probability distribution
    - cell cycle
---

Cell cycle is an awesome orchestration of colossal molecules in the elaborate cell machine. Analogous to the central theorem, genetic code to protein expression and phenotypes as molecular interactions to cell cycle progression, which means there can be two kinds of studies that meat each halfway:



1. The study of protein interaction dynamics during the cell cycle - to discuss how certain group of proteins contribute to an overall function. For example, <a href="https://dx.doi.org/10.1016/j.cell.2016.11.034">Nurse group, 2016</a> has provided proteomic evidence about the dependence of driving kinase - substrate interaction on substrate activity.
2. The study of cell cycle progression kinetics - to characterize key events (checkpoints, commitment points, etc.) and predict the existence of functional proteins.

If we are able to establish a working cell cycle model based on defined protein interactions, then we are confident that we have interpreted the protein function correctly. If the model cannot capture cell cycle features, commonly the case, a _refinement_ of the model with more parameters, different kinetic formulas i.e., modelling approaches may reveal undiscovered features. However, a formula with unresolved _biological meaning_ is exposed to critics (e.g. over-fitting).

[A recent research](https://doi.org/10.1016/j.cels.2017.09.015) has concluded unique DNA damage response kinetics in consecutive cell cycle phases (G1, S and G2/M) through modeling the time length of these phases. Two questions haunted me when reading through the paper:

1. How to characterize various differences concluded in a more statistical way? What are true differences and what can be artifacts.
2. How can we fathom the biological nature of model parameters?

## Binomial, Poisson, Exponential and Gamma distribution

The probability of obtaining $n$ binary outcomes from $n$ Bernoulli trials follows Binomial distribution.
<br/>

$$\begin{gather}
 PMF_{B(n, p)} = P(X = k) = \tbinom{n}{k}p^k(1-p)^{n-k}
\end{gather}$$



## A basic cell cycle model



## Model refinement



