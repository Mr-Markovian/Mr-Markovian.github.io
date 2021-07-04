---
date: 2017-04-14T11:25:05-04:00
description: "Inference"
featured_image: "/images/esmeralda.jpg"
tags: ["Graphical model","Machine Learning"]
title: "Chapter VI: Tensor networks for Machine Learning"
disable_share: false
markup: mmark
---

## Tensor Networks
Graphical models are powerful methods which simplifies the statistical dependence of a set of random variables.

* Bayesian networks
* Markov Random Fields
* factor graph model
 
A factor graphical model descibes a fucntion of the random variables in temrs of the products of fuction of this random variables. when all the factors are non ngative fucntion, the global fucntion can be used to represent a multivariate probability distribution. they capture and can model a lot of problems in fiels of economics, machine learning, statistical modeling and so on.

## Ising Model

## $$\mathcal H =\sum_{i}w_{ij} s_i s_j-B\sum_i s_i$$
where,

## Belief Propagation


A generic probability distribution over n-bits require $$2^n-1$$ real parameters, which becomes $$2^n-1$$ complex parameters in case of qbits.  

Often in real problems comes with special symetries and constraints, which when exploited can reduce the number of such parameters and lead to a succint description of the system.

## References :
* [Tensor network contraction and belief propagaton algorithm.](https://journals.aps.org/prresearch/pdf/10.1103/PhysRevResearch.3.023073)
* [Tensor network basics](https://iopscience.iop.org/article/10.1088/1751-8121/aa6dc3/pdf)

## Belief Propagation Algorithm
