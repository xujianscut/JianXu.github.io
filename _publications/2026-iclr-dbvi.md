---
title: "Diffusion Bridge Variational Inference for Deep Gaussian Processes"
collection: publications
category: conferences
permalink: /publication/2026-iclr-dbvi
excerpt: 'Doob-bridged variational inference for Deep GPs — score network is trained against the closed-form bridge marginal so the variational posterior interpolates between a data-anchored initial distribution and a fixed terminal noise.'
date: 2026-04-24
venue: 'The Fourteenth International Conference on Learning Representations (ICLR 2026)'
paperurl: 'https://openreview.net/forum?id=zyRmy0Ch9a'
codeurl: 'https://github.com/xujianscut/DBVI-DGP'
citation: 'Xu, J., Zeng, D., Zhao, Q. and Paisley, J. (2026). Diffusion Bridge Variational Inference for Deep Gaussian Processes. ICLR 2026.'
---

We extend score-based variational inference for Deep Gaussian Processes by
inserting a Doob h-transform into the forward noising SDE so the diffusion
interpolates between an amortized, data-anchored initial distribution and a
fixed terminal noise. The bridge marginal is Gaussian in closed form, so a
conditional score network can be trained against it via denoising score
matching, and posterior samples are produced by integrating the reverse-time
bridge SDE.
