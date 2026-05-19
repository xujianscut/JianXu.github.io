---
title: "Sparse Variational Student-t Processes for Heavy-Tailed Modeling"
collection: publications
category: manuscripts
permalink: /publication/2026-tnnls-svtp-heavy
excerpt: 'Journal extension of the AAAI 2024 SVTP paper. Closed-form Fisher information matrix for the multivariate Student-t variational distribution via the "beta link", enabling tractable natural-gradient optimisation at scale.'
date: 2026-03-09
venue: 'IEEE Transactions on Neural Networks and Learning Systems (TNNLS)'
paperurl: 'https://doi.org/10.1109/TNNLS.2026.3673350'
codeurl: 'https://github.com/xujianscut/svtp'
citation: 'Xu, J., Zeng, D. and Paisley, J. (2026). Sparse Variational Student-t Processes for Heavy-Tailed Modeling. IEEE Transactions on Neural Networks and Learning Systems, pp.1-14, doi:10.1109/TNNLS.2026.3673350.'
---

A principled sparse framework for Student-t Processes (TPs) extending SVTP
(AAAI 2024). We derive the Fisher information matrix of the multivariate
Student-t variational distribution and show its components have a compact
expression in terms of the beta function (the "beta link"), giving the first
tractable method for natural-gradient learning of sparse TPs. The result is
substantially faster convergence and lower prediction error on UCI and
Kaggle datasets, and the framework scales to datasets with over 200,000
samples while preserving TP's outlier robustness.
