---
title: Density of standard normal given sum larger than zero
author: Anthony Li
date: 2021-10-13 14:21:00 -0600
categories: [Statistics]
tags: [Probability]
math: true
---

# Question

Given two i.i.d. standard normal random variables $X, Y$. What is the density of $X$ given $X+Y>0$?

# Answer

Find the probability of $X\le c$ given $X+Y>0$.

$$\begin{align}P(X\le c\vert X+Y>0)&=\frac{P(X\le c,Y>-X)}{P(X+Y>0)}\\&=2\int_{-\infty}^c\int_{-X}^{+\infty}YdYdX\\&=2\int_{-\infty}^c\Phi(X)dX\\&=2\Phi(X)\phi(X)\end{align}$$

Thus the density of $X$ given $X+Y>0$ is:

$$P(X\le c\vert X+Y>0)=2\Phi(X)\phi(X)$$

\[\varphi\]

\\[\varphi\\]
