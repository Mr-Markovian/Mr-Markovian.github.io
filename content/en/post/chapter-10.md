---
date: 2021-06-13T11:15:58-04:00
description: "Physics Informed Machine Learning"
featured_image: ""
tags: ["Machine Learning","Geoscience"]
title: "Machine Learning for Weather and Climate Science"
---

It's a remarkable time for us for application of AI to solve the hardest of real world problems. Climate and weather prediction is one such task which impacts billions of people all over the world.

Of possible areas, some are as follows:
* Downscale data
* Accelerate Simulations
* Improve forecasts
* Emulate complex processes

1. Pattern recognition for extreme weather phenomenon. Tracking extreme events is critical for our climate if one is to prepare and avoid their devastations. How do we detect them from datasets. We must be aiming to understand some features which are encoded into the algorithm. 

Challenges of machine learning in Climate related problems:
* Multivariate nature of the system.
* myriad of spatio-temporal scales of dynamics and interactions.
* multi-modality of probability distributions.
* missing and sparse data.
* noise and artifacts.
* unavailability of high-quality datasets.

Events which are of interest to the model. Tropical cyclones, hurricanes, etc.
The models must be robust enough not be senstive of missing data.
Quantify uncerstainities: Probabilistic segmentation of events.

## Models in climate and weather predictions


2. Downscaling data: Physics Informed ML( Custom deep neural networks) have been applied to models with turbulent convection.
High resoution simulation are expensive( space and time). But which is necessary for many purposes for planning and events. Deeplearning can produce high-resolution of low resolution.

eg. an ideal model is Rayleigh-Benard Convection.
## RANS 

A lot of invariance is needed to be built into the architecture
### Closure models

Closure problem: the mean flow profile depends on the turbulent fluctuations.

## LES 
Low-pass filter Navier-Stokes,
there is a nonlinear cupling between arge and small scales. We need to account for tiniest scales while modeling corase grained models. 

Learn better closure models using neural networks.

MeshfreeFLowNet is an example to look at for understanding what kind of work is being done. This is a very useful model to get the perspective.

Couple super-resolution models with tranitional PDE solver.
neural PDE solvers. How much information of the smaller scales be inf

We need to build models which are physically consistent. What are the ways to do this? How to implement concepts like conservation laws, symmetries, local correlations stochasticity, multiscale properties etc.

Ensemble neural network. 

## References
### Papers
0. [Using Machine Learning for Model Physics](https://arxiv.org/pdf/2002.00416.pdf)
1. Assessing sesnitivities in algorithmic detection of tropical cyclones in climate data.
2. GMD 2020, NeurIPS 2020.
3. [Machine Learning for fluid mechanics](link)
4. [Turbulence modeling in age of data](link)
5. [Subgrid modelling for two-dimensional turbulence using neural networks](link)
6. [Automating turbulence modelling by multi-agent reinforecement learning](link)
7. [Super resolution methods](link)
8. [Reynolds avegraged turbulence modelling using deep neural networks with embedded invariance]()

