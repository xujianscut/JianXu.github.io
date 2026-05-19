---
title: "Fully Bayesian Differential Gaussian Processes through Stochastic Differential Equations"
collection: publications
category: manuscripts
permalink: /publication/2025-kbs-fb-diffgp
excerpt: 'Latent-state SDE driven by a sparse GP, where the GP kernel length scales themselves evolve via a second SDE — a fully Bayesian treatment of kernel hyperparameters instead of point estimation.'
date: 2025-03-01
venue: 'Knowledge-Based Systems'
paperurl: 'https://doi.org/10.1016/j.knosys.2025.113187'
codeurl: 'https://github.com/xujianscut/FB-DIFFGP'
citation: 'Xu, J., Lin, Z., Chen, M., Yang, J., Zeng, D. and Paisley, J. (2025). Fully Bayesian differential Gaussian processes through stochastic differential equations. Knowledge-Based Systems, 314, p.113187.'
---

FB-DiffGP couples two stochastic differential equations: a latent-state SDE
whose drift/diffusion are the posterior mean/std of a sparse GP layer, and a
length-scale SDE whose neural drift evolves the GP's ARD kernel parameters
over diffusion time. This realises a fully Bayesian treatment of the kernel
hyperparameters and produces calibrated uncertainty without sacrificing
sparse-GP scalability.
