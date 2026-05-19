---
title: "Sparse Inducing Points in Deep Gaussian Processes: Enhancing Modeling with Denoising Diffusion Variational Inference"
collection: publications
category: conferences
permalink: /publication/2024-icml-ddvi
excerpt: 'ICML 2024 (Oral). DDVI replaces the mean-field Gaussian posterior over inducing variables with the terminal of a reverse-time VP-SDE driven by a learned score network, jointly trained with denoising score matching.'
date: 2024-07-21
venue: 'Proceedings of the 41st International Conference on Machine Learning (ICML 2024)'
paperurl: 'https://proceedings.mlr.press/v235/xu24af.html'
codeurl: 'https://github.com/xujianscut/DDVI-DGP'
citation: 'Xu, J., Zeng, D. and Paisley, J. (2024). Sparse Inducing Points in Deep Gaussian Processes: Enhancing Modeling with Denoising Diffusion Variational Inference. ICML 2024, PMLR 235, pp.55490-55500. (Oral)'
---

The true posterior over Deep GP inducing variables is generally
non-Gaussian, but mean-field Gaussian VI is the standard approximation.
DDVI represents the variational posterior implicitly as the terminal state
of a reverse-time variance-preserving SDE driven by a learned score
network, jointly trained with a denoising score-matching regulariser. This
sidesteps the mean-field restriction and gives an explicit, optimisable
lower bound on the marginal likelihood.
