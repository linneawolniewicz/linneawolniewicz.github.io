---
layout: publication
type: publication
title: "Neural Surrogate HMC: On Using Neural Likelihoods for Hamiltonian Monte Carlo in Simulation-Based Inference"
# All dates must be YYYY-MM-DD format!
date: 2026-09-12
published: true
labels:
---

## Abstract

Bayesian inference methods such as Markov Chain Monte Carlo (MCMC) typically require repeated computations of the likelihood function, but in some scenarios this is infeasible and alternative methods are needed. Simulation-based inference (SBI) methods address this problem by using machine learning to amortize computations. In this work, we highlight a particular synergy between the SBI method of neural likelihood estimation and the classic MCMC method of Hamiltonian Monte Carlo. We show that approximating the likelihood function with a neural network model can provide three distinct advantages: (1) amortizing the computations for MCMC; (2) providing gradients for Hamiltonian Monte Carlo, and (3) smoothing over noisy simulations resulting from numerical instabilities. We provide practical guidelines for defining a prior, sampling a training set, and evaluating convergence. The method is demonstrated in an application modeling the heliospheric transport of galactic cosmic rays, where it enables efficient inference of latent parameters in the Parker equation.

### Authors
Linnea M Wolniewicz, Peter Sadowski, Claudio Corti

Published September 12, 2026 in *Journal of Geophysical Research: Machine Learning and Computation*, **3**(5), e2025JH001164.

[Read the published paper](https://doi.org/10.1029/2025JH001164)

[Read the preprint on arXiv](https://arxiv.org/abs/2407.20432v2)


