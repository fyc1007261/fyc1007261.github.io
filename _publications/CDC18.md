---
title: "Consensus-based Data Statistics in Distributed Network Systems"
collection: publications
permalink: /publication/CDC18/
excerpt: ''
date: 2018-12-16
venue: 'IEEE Conference on Decision and Control (CDC), 2018'
paperurl: 'http://fyc1007261.github.io/files/cdc18_main.pdf'
status: 'In'
authors: '<b>Yifan Cai</b>, Jianping He, Wenbin Yu, and Xinping Guan'
---


### Authors

**Yifan Cai**, Jianping He, Wenbin Yu and Xinping Guan



### Abstact

Data has become increasingly important in network systems because a lot of data is needed in new technologies such as machine learning. To obtain statistics (e.g. maximum, average, distribution) in a fully distributed way with low complexity is challenging. Existing research on consensus algorithms can successfully obtain the max/min, average and median in a distributed network, but little work has been done on how to compute other statistics, especially probability density function (PDF). In this paper, consensus-based algorithms are proposed to obtain PDF in a fully distributed way with low complexity. The key idea of our algorithms is to divide the range of nodes’ values into several sections and calculate the proportions of values in each section in a fully distributed way. If nodes have their unique identifications (IDs), repeatedly run max/min consensus algorithm to reach the partially max/min value and then erase them in order to reach all values exactly once. We prove that the algorithm converges in finite time. When nodes’ IDs are not available, the main challenge is to solve the conflicts when two or more nodes have the same value. We propose an asymptotically converged algorithm to solve the problem in this scenario.

[Download paper here](https://fyc1007261.github.io/files/cdc18_main.pdf)

