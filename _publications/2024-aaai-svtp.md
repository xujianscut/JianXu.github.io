---
title: "Sparse Variational Student-t Processes"
collection: publications
category: conferences
permalink: /publication/2024-aaai-svtp
excerpt: 'Extends sparse inducing-point inference from GPs to Student-t Processes, giving robustness to outliers and heavy-tailed observations while preserving SVGP-level computational complexity.'
date: 2024-02-22
venue: 'Proceedings of the AAAI Conference on Artificial Intelligence, 38(14)'
paperurl: 'https://doi.org/10.1609/aaai.v38i14.29547'
codeurl: 'https://github.com/xujianscut/svtp'
citation: 'Xu, J. and Zeng, D. (2024). Sparse variational student-t processes. Proceedings of the AAAI Conference on Artificial Intelligence, 38(14), pp.16156-16163.'
---

SVTP extends the sparse inducing-point framework from Gaussian Processes to
Student-t Processes (TPs). We derive a tractable evidence lower bound using
the conditional Student-t distribution at inducing points and propose two
inference algorithms — SVTP-UB (Jensen's inequality upper bound) and
SVTP-MC (Monte Carlo) — together with a theoretical analysis of when SVTP
out-performs SVGP. Empirically, SVTP delivers substantial gains on
outlier-contaminated and heavy-tailed datasets.
