---
title: "Bayesian Gaussian Process ODEs via Double Normalizing Flows"
collection: publications
category: conferences
permalink: /publication/2025-aistats-gpode-dnf
excerpt: 'Two normalizing flows for Bayesian GP-ODEs: one reparameterises the ODE vector field into a data-driven prior, the other relaxes the mean-field assumption on the inducing-variable posterior. Improves accuracy and uncertainty on dynamical systems and CMU MoCap.'
date: 2025-05-04
venue: 'Proceedings of the 28th International Conference on Artificial Intelligence and Statistics (AISTATS 2025)'
paperurl: 'https://proceedings.mlr.press/v258/xu25b.html'
codeurl: 'https://github.com/xujianscut/GPODE-DNF'
citation: 'Xu, J., Du, S., Yang, J., Ding, X., Zeng, D. and Paisley, J. (2025). Bayesian Gaussian Process ODEs via Double Normalizing Flows. AISTATS 2025, PMLR 258, pp.235-243.'
---

Standard GP-ODEs use a Gaussian process vector field with an RBF kernel,
limiting expressiveness on complex dynamics. We introduce normalizing flows
in two places — to reparameterise the ODE vector field (a data-driven prior)
and to enrich the inducing-variable posterior (a non-mean-field
approximation). The analytically tractable density of planar flows makes
both transformations compatible with variational inference. Validated on
simulated dynamical systems and CMU MoCap with improved accuracy and
uncertainty calibration over GP-ODE / npODE / ODE2VAE / Latent SDE.
