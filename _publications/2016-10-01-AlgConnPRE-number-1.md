---
title: "Maximizing algebraic connectivity in interconnected networks"
collection: publications
permalink: /publication/algConnPRE
excerpt: 'In this work, we solve the problem of finding an optimal weight distribution for one-to-one interlayer links in multiplex networks under budget constraint'
author_profile: false
date: 2016-3-21
venue: 'Physical Review E'
paperurl: 'https://journals.aps.org/pre/abstract/10.1103/PhysRevE.93.030301'
---
Algebraic connectivity, the second eigenvalue of the Laplacian matrix, is a measure of node and link connectivity on networks. When studying interconnected networks it is useful to consider a multiplex model, where the component networks operate together with interlayer links among them. In order to have a well-connected multilayer structure, it is necessary to optimally design these interlayer links considering realistic constraints. 

![A schematic of a multiplex network with two layers](/images/algConnPRE.png)

In this work, we solve the problem of finding an optimal weight distribution for one-to-one interlayer links under budget constraint. We show that for the special multiplex configurations with identical layers, the uniform weight distribution is always optimal. On the other hand, when the two layers are arbitrary, increasing the budget reveals the existence of two different regimes. Up to a certain threshold budget, the second eigenvalue of the supra-Laplacian is simple, the optimal weight distribution is uniform, and the Fiedler vector is constant on each layer. Increasing the budget past the threshold, the optimal weight distribution can be nonuniform. The interesting consequence of this result is that there is no need to solve the optimization problem when the available budget is less than the threshold, which can be easily found analytically.

![Plots of algebraic connectivity with different amount of available budget. ](/images/algConnPRE2.png)


```
@article{shakeri2016maximizing,
  title={Maximizing algebraic connectivity in interconnected networks},
  author={Shakeri, Heman and Albin, Nathan and Sahneh, Faryad Darabi and Poggi-Corradini, Pietro and Scoglio, Caterina},
  journal={Physical Review E},
  volume={93},
  number={3},
  pages={030301},
  year={2016},
  publisher={American Physical Society}
}
```