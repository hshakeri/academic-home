---
title: "Generalization of effective conductance centrality for egonetworks"
collection: publications
permalink: /publication/GenDeg
excerpt: 'In this paper, effective conductance centrality is generalized using modulus of families of walks and we extend effective conductance measures to directed and ego networks.'
author_profile: false
date: 2018-01-17
venue: 'Physica A: Statistical Mechanics and its Applications'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S0378437118309117'
---
We study the popular centrality measure known as effective conductance or in some circles as information centrality. This is an important notion of centrality for undirected networks, with many applications, e.g., for random walks, electrical resistor networks, epidemic spreading, etc. In this paper, we first reinterpret this measure in terms of modulus (energy) of families of walks on the network. This modulus centrality measure coincides with the effective conductance measure on simple undirected networks, and extends it to much more general situations, e.g.,directed networks as well. Secondly, we study a variation of this modulus approach in the egocentric network paradigm. Egonetworks are networks formed around a focal node (ego) with a specific order of neighborhoods. We propose efficient analytical and approximate methods for computing these measures on both undirected and directed networks. Finally, we describe a simple method inspired by the modulus point-of-view, called shell degree, which proved to be a useful tool for network science.

[Download paper here](https://www.sciencedirect.com/science/article/pii/S0378437118309117)

![](/images/GenDeg1.jpg)

Interpreting Mod$_2(a, S(a,r))$ as finding effective conductance between grounded node $a$ and nodes with the same potential $c$ in $S(a,r)$ in an electrical network. Solution follows from the corresponding Laplacian system.

![](/images/GenDeg2.jpg)

Comparing the value of the Ahlfors upper bound, Tree modulus lower bound, Shell degree, and Shell modulus in simulated random network models (a) Erdos–Renyi networks with $p=2\log n/n$, (b) Scale free network by Barabasi and Albert model [20] with  edges preferential attachment. (c) Spatial network (random geometric network) with distance threshold value $r=\sqrt{2 \log n/n}$ and small world network by Watts–Strogatz model with initial degree of $2\log n$ and rewiring probability $0.3$. Shell degree is providing a fair estimate of shell modulus in these networks.

```
@article{shakeri2018generalization,
  title={Generalization of effective conductance centrality for egonetworks},
  author={Shakeri, Heman and Moradi-Jamei, Behnaz and Poggi-Corradini, Pietro and Albin, Nathan and Scoglio, Caterina},
  journal={Physica A: Statistical Mechanics and its Applications},
  volume={511},
  pages={127--138},
  year={2018},
  publisher={North-Holland}
}
```