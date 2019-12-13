---
title: "GEMFsim: a stochastic simulator for the generalized epidemic modeling framework"
collection: publications
permalink: /publication/GEMF
excerpt: 'This article builds an algorithm for exact, continuous-time numerical simulation of GEMF-based processes. Moreover the implementation of this algorithm, GEMFsim, is available in popular scientific programming platforms such as MATLAB, R, Python, and C.'
author_profile: false
date: 2017-01-17
venue: 'Journal of computational science'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S1877750317305227GEMFcode'
---
The recently proposed generalized epidemic modeling framework (GEMF) [1] lays the groundwork for systematically constructing a broad spectrum of stochastic spreading processes over complex networks. This article builds an algorithm for exact, continuous-time numerical simulation of GEMF-based processes. Moreover the implementation of this algorithm, GEMFsim, is available in popular scientific programming platforms such as MATLAB, R, Python, and C; GEMFsim facilitates simulating stochastic spreading models that fit in GEMF framework. Using these simulations one can examine the accuracy of mean-field-type approximations that are commonly used for analytical study of spreading processes on complex networks.

[Download paper here](https://journals.aps.org/pre/pdf/10.1103/PhysRevE.95.012316)

[Download software here](https://www.ece.k-state.edu/netse/software/index.html)

GEMFsim algorithm:

![](/images/GEMFcode.jpg)


GEMF is suitable fo hypothesis testing, e.g.,


![](/images/GEMFcompetitive.jpg)

Fraction of nodes infected by virus type 2 (above) and virus type 1 (below) in the `SI1SI2S` competitive spreading model. Infection strength of $I_2$, $\tau_2$, was $5/\lambda_1(B)$, while the infection strength of I1, τ1, varied. If $2/\lambda_1(A) \le \tau_1 \le 5/\lambda_1(A)$, viruses coexist; only one virus survives outside this region.

```
@article{sahneh2017gemfsim,
  title={GEMFsim: a stochastic simulator for the generalized epidemic modeling framework},
  author={Sahneh, Faryad Darabi and Vajdi, Aram and Shakeri, Heman and Fan, Futing and Scoglio, Caterina},
  journal={Journal of computational science},
  volume={22},
  pages={36--44},
  year={2017},
  publisher={Elsevier}
}
```