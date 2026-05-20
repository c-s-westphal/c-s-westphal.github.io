---
title: "Information-theoretic State Variable Selection for Reinforcement Learning"
collection: publications
category: preprint
permalink: /publication/2024-01-21-information-theoretic-state-selection
excerpt: 'This paper introduces the Transfer Entropy Redundancy Criterion (TERC), an information-theoretic approach for identifying optimal state variables in RL that provably excludes variables with no effect on agent performance.'
date: 2024-01-21
venue: 'arXiv preprint, 2024'
authors: 'Charles Westphal, Stephen Hailes, Mirco Musolesi'
paperurl: 'https://arxiv.org/abs/2401.11512'
github: ''
equation: '\mathcal{X}_* \in \Bigl\{ \mathcal{P} \in \mathscr{P}(\mathcal{X}) \;:\; |\mathcal{P}| = \min_{H(A \mid \mathcal{P}) = H(A \mid \mathcal{X})} |\mathcal{P}| \;\;\&\;\; H(A \mid \mathcal{P}) = H(A \mid \mathcal{X}) \Bigr\}'
summary: 'The Transfer Entropy Redundancy Criterion (TERC): an information-theoretic test that provably drops state variables with no effect on agent performance, improving sample efficiency across Q-learning, Actor-Critic, and PPO.'
citation: 'Westphal, C., Hailes, S., & Musolesi, M. (2024). Information-theoretic State Variable Selection for Reinforcement Learning. arXiv preprint arXiv:2401.11512.'
---

## Abstract

The paper introduces the Transfer Entropy Redundancy Criterion (TERC), an information-theoretic approach for identifying optimal state variables in RL. The method provably excludes variables from the state that have no effect on the final performance of the agent, improving sample efficiency. The authors test their approach across Q-learning, Actor-Critic, and PPO algorithms in various environments, using Bayesian networks to represent information flow from state variables to actions.

[Download paper here](https://arxiv.org/abs/2401.11512)
