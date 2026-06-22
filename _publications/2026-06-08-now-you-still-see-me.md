---
title: "Now You (Still) See Me: Detecting Evasive Steganographic Payloads in LLMs"
collection: publications
category: preprint
permalink: /publication/2026-06-08-now-you-still-see-me
excerpt: 'Shows that activation-based steganography detection in LLMs can be evaded via adversarial fine-tuning, and proposes a data-level intervention using recontextualization datasets that restores detectability.'
date: 2026-06-08
venue: 'arXiv preprint, 2026'
authors: 'Charles Westphal, Timothy Douglas, Keivan Navaie, Tiago Pimentel, Fernando E. Rosas'
paperurl: 'https://arxiv.org/abs/2606.09411'
github: ''
image: ''
summary: 'Linear-probe detectors for LLM steganography can be evaded by adversarial fine-tuning (58–79% covert recovery preserved). A theory-guided recontextualization intervention restores detection where activation-only methods fail.'
citation: 'Westphal, C., Douglas, T., Navaie, K., Pimentel, T., & Rosas, F. E. (2026). Now You (Still) See Me: Detecting Evasive Steganographic Payloads in LLMs. arXiv preprint arXiv:2606.09411.'
---

## Abstract

The paper examines how large language models can be fine-tuned to conceal secret information within seemingly ordinary outputs. The authors demonstrate that existing detection mechanisms using linear probes on model activations can be circumvented through adversarial fine-tuning across five model variants — the evasive trojans maintain 58–79% secret recovery rates while evading detection, with minimal impact on model performance. They then propose a data-level intervention using recontextualization datasets that successfully restores detectability. The findings reveal that activation-based steganography detection is vulnerable to adaptive evasion, but theory-guided evaluation distributions can expose otherwise hidden payloads.

[Download paper here](https://arxiv.org/abs/2606.09411)
