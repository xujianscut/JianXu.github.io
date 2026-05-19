---
title: "Neural Operator Variational Inference Based on Regularized Stein Discrepancy for Deep Gaussian Processes"
collection: publications
category: manuscripts
permalink: /publication/2024-tnnls-novi
excerpt: 'Replaces the mean-field Gaussian posterior over inducing variables in a Deep GP with a neural-network generator trained via a regularized Stein discrepancy — a neural operator that maps noise to inducing-variable samples.'
date: 2024-08-09
venue: 'IEEE Transactions on Neural Networks and Learning Systems (TNNLS), 36(4)'
paperurl: 'https://doi.org/10.1109/TNNLS.2024.3406635'
codeurl: 'https://github.com/xujianscut/NOVI-DGP'
citation: 'Xu, J., Du, S., Yang, J., Ma, Q. and Zeng, D. (2025). Neural Operator Variational Inference Based on Regularized Stein Discrepancy for Deep Gaussian Processes. IEEE Transactions on Neural Networks and Learning Systems, 36(4), pp.6723-6737.'
---

NOVI replaces the conventional mean-field Gaussian posterior over Deep GP
inducing variables with a neural-network generator optimised by minimising
a regularized Stein discrepancy rather than the KL term in the ELBO. The
generator behaves as a neural *operator* mapping noise to inducing-variable
samples, giving a substantially more expressive posterior while keeping
inference tractable. Demonstrated on regression and image classification
(CIFAR-10 conv-DGP).
