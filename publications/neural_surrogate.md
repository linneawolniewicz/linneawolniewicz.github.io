---
layout: publication
type: publication
title: "Neural Surrogate HMC: Accelerated Hamiltonian Monte Carlo with a Neural Network Surrogate Likelihood"
# All dates must be YYYY-MM-DD format!
date: 2024-07-29
published: true
labels:
---

## Authors
Linnea M Wolniewicz, Peter Sadowski, Claudio Corti

## Abstract

Bayesian Inference with Markov Chain Monte Carlo requires efficient computation of the likelihood function. In some scientific applications, the likelihood must be computed by numerically solving a partial differential equation, which can be prohibitively expensive. We demonstrate that some such problems can be made tractable by amortizing the computation with a surrogate likelihood function implemented by a neural network. We show that this has two additional benefits: reducing noise in the likelihood evaluations and providing fast gradient calculations. In experiments, the approach is applied to a model of heliospheric transport of galactic cosmic rays, where it enables efficient sampling from the posterior of latent parameters in the Parker equation.

## Full Paper
[Read the full paper on arXiv](https://arxiv.org/abs/2407.20432)


