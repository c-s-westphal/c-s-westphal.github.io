---
title: "Mutual Information Preserving Neural Network Pruning"
collection: publications
category: preprint
permalink: /publication/2024-10-31-mutual-information-pruning
excerpt: 'This paper proposes Mutual Information Preserving Pruning (MIPP), a structured activation-based pruning method that selects nodes to conserve mutual information shared between activations of adjacent layers.'
date: 2024-10-31
venue: 'arXiv preprint, 2024'
authors: 'Charles Westphal, Stephen Hailes, Mirco Musolesi'
paperurl: 'https://arxiv.org/abs/2411.00147'
github: ''
image: '/images/papers/mipp.png'
summary: 'A structured pruning method that keeps the nodes carrying mutual information between adjacent layers, with a guarantee that the pruned upstream activations can still be mapped to the downstream layer — so the network remains retrainable.'
citation: 'Westphal, C., Hailes, S., & Musolesi, M. (2024). Mutual Information Preserving Neural Network Pruning. arXiv preprint arXiv:2411.00147.'
---

## Abstract

The authors propose Mutual Information Preserving Pruning (MIPP), a structured activation-based pruning method. Their approach selects nodes in a way that conserves MI shared between the activations of adjacent layers to improve model efficiency. The technique applies to pruning either before or after training and demonstrates improved performance compared to existing methods. A key theoretical contribution is proving there exists a function that can map the pruned upstream layer's activations to the downstream layer's, implying re-trainability.

[Download paper here](https://arxiv.org/abs/2411.00147)
