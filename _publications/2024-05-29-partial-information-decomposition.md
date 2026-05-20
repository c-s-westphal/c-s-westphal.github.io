---
title: "Partial Information Decomposition for Data Interpretability and Feature Selection"
collection: publications
category: conference
permalink: /publication/2024-05-29-partial-information-decomposition
excerpt: 'This paper introduces PIDF, a novel approach that simultaneously addresses data interpretability and feature selection by evaluating each feature using three metrics: mutual information, synergistic contribution, and redundancy.'
date: 2024-05-29
venue: 'AISTATS 2025'
authors: 'Charles Westphal, Stephen Hailes, Mirco Musolesi'
paperurl: 'https://arxiv.org/abs/2405.19212'
github: 'https://github.com/c-s-westphal/PIDF'
image: '/images/papers/pidf.png'
summary: 'PIDF replaces a single feature-importance score with three: how much information a feature shares with the target, how much arises only in combination with others (synergy), and how much is redundant with what other features already carry.'
citation: 'Westphal, C., Hailes, S., & Musolesi, M. (2024). Partial Information Decomposition for Data Interpretability and Feature Selection. arXiv preprint arXiv:2405.19212.'
---

## Abstract

The paper introduces PIDF, a novel approach that simultaneously addresses data interpretability and feature selection. Rather than assigning single importance scores, the method evaluates each feature using three metrics: the mutual information shared with the target variable, the feature's contribution to synergistic information, and the amount of this information that is redundant. The authors validate their framework using synthetic and real-world datasets, with applications in genetics and neuroscience research.

[Download paper here](https://arxiv.org/abs/2405.19212)
