---
title: "A new method for quantifying network cyclic structure to improve community detection"
collection: publications
permalink: /publication/RNBRW
excerpt: 'In this paper, we introduce renewal non-backtracking random walks (RNBRW) as a way of quantifying this structure. RNBRW gives a weight to each edge equal to the probability that a non-backtracking random walk completes a cycle with that edge.'
author_profile: false
date: 2019-01-17
venue: 'arxiv'
paperurl: 'https://arxiv.org/abs/1910.01921'
---
A distinguishing property of communities in networks is that cycles are more prevalent within communities than across communities. Thus, the detection of these communities may be aided through the incorporation of measures of the local ”rich- ness” of the cyclic structure. In this paper, we introduce renewal non-backtracking random walks (RNBRW) as a way of quantifying this structure. RNBRW gives a weight to each edge equal to the probability that a non-backtracking random walk completes a cycle with that edge. Hence, edges with larger weights may be thought of as more important to the formation of cycles. Of note, since separate random walks can be performed in parallel, RNBRW weights can be estimated very quickly, even for large graphs. We give simulation results showing that pre-weighting edges through RNBRW may substantially improve the performance of common community detection algorithms. Our results suggest that RNBRW is especially efficient for the challenging case of detecting communities in sparse graphs.

[Download paper here](https://arxiv.org/abs/1910.01921)



![](/images/RNBRW_w.png)

(a) An LFR benchmark graph. (b) The same graph weighted by RNBRW. Observe that within-community edges have larger weights than across-community edges.


```
@article{moradi2019new,
  title={A new method for quantifying network cyclic structure to improve community detection},
  author={Moradi-Jamei, Behnaz and Shakeri, Heman and Poggi-Corradini, Pietro and Higgins, Michael J},
  journal={arXiv preprint arXiv:1910.01921},
  year={2019}
}
```