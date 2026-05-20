---
title: "Hide and Seek in Embedding Space: Geometry-based Steganography and Detection in Large Language Models"
collection: publications
category: conference
permalink: /publication/2026-01-30-hide-and-seek-embedding-space
excerpt: 'This paper introduces geometry-based steganography in fine-tuned LLMs using embedding-space-derived mappings, and proposes mechanistic-interpretability-based detection via linear probes on model activations. Accepted to ICML 2026.'
date: 2026-01-30
venue: 'ICML 2026'
authors: 'Charles Westphal, Keivan Navaie, Fernando E. Rosas'
paperurl: 'https://arxiv.org/abs/2601.22818'
github: ''
image: '/images/papers/hide-and-seek.png'
summary: 'A geometry-based steganography scheme that hides secrets in fine-tuned LLM outputs via embedding-space hyperplanes, together with a linear-probe detector that exposes it more reliably than traditional steganalysis.'
citation: 'Westphal, C., Navaie, K., & Rosas, F. E. (2026). Hide and Seek in Embedding Space: Geometry-based Steganography and Detection in Large Language Models. To appear in Proceedings of the International Conference on Machine Learning (ICML).'
---

## Abstract

The paper examines how fine-tuned language models can covertly encode information in their outputs through steganographic methods. The authors introduce an improved steganographic scheme with reduced recoverability by using mappings derived from the model's embedding space rather than arbitrary ones. Empirically, on models such as Llama-8B and Ministral-8B, this yields significant increases in secret recovery rates (+78% to +123%). On the detection side, they propose using mechanistic interpretability with linear probes on model activations, achieving up to 33% higher accuracy than traditional steganalysis approaches in identifying malicious fine-tuning signatures.

**Accepted at the International Conference on Machine Learning (ICML), 2026.**

[Download paper here](https://arxiv.org/abs/2601.22818)
