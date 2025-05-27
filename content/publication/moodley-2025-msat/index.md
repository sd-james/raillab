---
title:  "M-SAT: Multi-State-Action Tokenisation in Decision Transformers for Multi-Discrete Actions"
authors:
  - Perusha Moodley
  - Dhillu Thambi
  - Mark Trovinger
  - Pramod Kaushik
  - Praveen Paruchuri
  - Xia Hong
  - Benjamin Rosman

author_notes: []

publication: "*International Joint Conference on Neural Networks*"

date: 2025-06-30T00:00:00Z
publishDate: 2022-10-05T00:00:00Z

# conf = 1, journal = 2, preprint = 3, report = 4, book = 5, book chapter = 6, thesis = 7, patent = 9
# workshop = 9, symposium = 10, extended abstract =11
publication_types:
- "1"

abstract: "Effective decision-making in complex environments with multi-discrete action spaces poses significant challenges for agent architectures, particularly in image-based settings. While Decision Transformers have shown promise in various domains, their performance often suffers in environments where agents must handle multi-discrete actions. Existing enhancements to Decision Transformer architectures have yet to address this critical issue, limiting their ability to support agents in learning robust policies in these environments. To address this gap, we propose Multi-State Action Tokenisation (M-SAT), a novel approach designed to improve agent decision-making by tokenising actions at the individual action level and incorporating auxiliary state information. This disentanglement of actions improves both the performance of agents and the interpretability of individual actions within attention layers, fostering better visibility into agent decision processes. Importantly, M-SAT facilitates the development of more interpretable and transparent agents capable of making complex decisions in dynamic environments involving multi-discrete action spaces. We evaluate M-SAT on the challenging ViZDoom environments, focusing on scenarios with multi-discrete action spaces and image-based observations, such as Deadly Corridor, My Way Home and Death Match. Our approach demonstrates superior performance compared to baseline Decision Transformers, with no additional data or significant computational overheads. Furthermore, we observe that M-SAT does not require positional encoding to achieve high performance, with its removal occasionally leading to further improvements. These findings suggest that M-SAT enables more efficient and interpretable agent-based decision-making in multi-discrete action spaces."

featured: true
tags:
  - Reinforcement Learning
  - Decision Transformers

image:
focal_point: ''
preview_only: false

slides: null

#url_dataset: "#"
#url_project: ""
#publication_short: ""
#url_source: "#"
#url_video: "#"
#url_slides: ""
#url_poster: "#"
#url_code: "#"
# doi: ""
---

