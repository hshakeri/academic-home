---
title: "Designing Optimal Multiplex Networks for Certain Laplacian Spectral Properties"
collection: publications
permalink: /publication/LapEig
excerpt: 'We discuss the design of interlayer edges in a multiplex network, under a limited budget, with the goal of improving its overall performance.'
author_profile: false
date: 2019-12-12
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/1903.01073'
---
We discuss the design of interlayer edges in a multiplex network, under a limited budget, with the goal of improving its overall performance. We analyze the following three problems separately; first, we maximize the smallest nonzero eigenvalue, also known as the algebraic connectivity; secondly, we minimize the largest eigenvalue, also known as the spectral radius; and finally, we minimize the spectral width. Maximizing the algebraic connectivity requires identical weights on the interlayer edges for budgets less than a threshold value. However, for larger budgets, the optimal weights are generally non-uniform. The dual formulation transforms the problem into a graph realization (embedding) problem that allows us to give a fuller picture. Namely, before the threshold budget, the optimal realization is one-dimensional with nodes in the same layer embedded to a single point; while, beyond the threshold, the optimal embeddings generally unfold into spaces with dimension bounded by the multiplicity of the algebraic connectivity. Finally, for extremely large budgets the embeddings revert again to lower dimensions. Minimizing the largest eigenvalue is driven by the spectral radius of the individual networks and its corresponding eigenvector. Before a threshold, the total budget is distributed among interlayer edges corresponding to the nodal lines of this eigenvector, and the optimal largest eigenvalue of the Laplacian remains constant. For larger budgets, the weight distribution tends to be almost uniform. In the dual picture, the optimal graph embedding is one-dimensional and non-homogeneous at first and beyond this threshold, the optimal embedding expands to be multi-dimensional, and for larger values of the budget, the two layers fill the embedding space. Finally, we show how these two problems are connected to minimizing the spectral width.

[Download paper here](https://arxiv.org/abs/1903.01073)

![](/images/LapEig1.png)

Weight distribution for optimal algebraic connectivity: (a) uniform weights for $c < c^*$, (b) nonuniform weights for $c>c^*$.

![](/images/LapEig2.png)

Embeddings for different budgets of two 30-node Watts-Strogatz networks.


```
@article{shakeri2019designing,
  title={Designing Optimal Multiplex Networks for Certain Laplacian Spectral Properties},
  author={Shakeri, Heman and Tavassoli, Ali and Ardjmand, Ehsan and Poggi-Corradini, Pietro},
  journal={arXiv preprint arXiv:1903.01073},
  year={2019}
}
```