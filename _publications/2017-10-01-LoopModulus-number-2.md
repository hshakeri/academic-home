---
title: "Network clustering and community detection using modulus of families of loops"
collection: publications
permalink: /publication/LoopModulus
excerpt: 'Modulus tries to minimize the expected overlap among loops by spreading the expected link usage optimally. We propose weighting networks using these expected link usages to improve classical community detection algorithms.'
author_profile: false
date: 2017-01-17
venue: 'Physical Review E'
paperurl: 'https://journals.aps.org/pre/abstract/10.1103/PhysRevE.95.012316'
---
We study the structure of loops in networks using the notion of modulus of loop families. We introduce an alternate measure of network clustering by quantifying the richness of families of (simple) loops. Modulus tries to minimize the expected overlap among loops by spreading the expected link usage optimally. We propose weighting networks using these expected link usages to improve classical community detection algorithms. We show that the proposed method enhances the performance of certain algorithms, such as spectral partitioning and modularity maximization heuristics, on standard benchmarks.

[Download paper here](https://journals.aps.org/pre/pdf/10.1103/PhysRevE.95.012316)

![](/images/LoopModulus1.png)

(a) Zachary's karate club network; (b) Spectral partitioning of Zachary's karate club network; node 3 is wrongly partitioned. (c) Spectral partitioning of the same network weighted by loop modulus where nodes are correctly partitioned.

![](/images/LoopMod2.png)

(a)–(c) Networks are produced by LFR benchmark with size $400$ nodes, mean degree $5$, maximum degree $10$, and community sizes ranging from $20$ to $40$. The mixing rates $\mu$, for adjusting ratio of intracommunities links over all links, are $0.1$, $0.2$, and $0.3$. (d) The plot depicts the normalized mutual information for community memberships found by greedy modularity optimization (CNM) and the Louvian method. Both the CNW and Louvian methods perform better on reweighted networks.

```
@article{shakeri2017network,
  title={Network clustering and community detection using modulus of families of loops},
  author={Shakeri, Heman and Poggi-Corradini, Pietro and Albin, Nathan and Scoglio, Caterina},
  journal={Physical Review E},
  volume={95},
  number={1},
  pages={012316},
  year={2017},
  publisher={American Physical Society}
}
```