---
title:  "Investigating Transfer Learning in Graph Neural Networks"
authors:
  - Nishai Kooverjee
  - Steven James
  - Terence Van Zyl

author_notes: []

publication: "*Electronics*"

date: 2022-04-09T00:00:00Z
publishDate: 2022-10-05T00:00:00Z

# conf = 1, journal = 2, preprint = 3, report = 4, book = 5, book chapter = 6, thesis = 7, patent = 9
# workshop = 9, symposium = 10, extended abstract =11
publication_types:
- "2"

abstract: Graph neural networks (GNNs) build on the success of deep learning models by extending them for use in graph 
  spaces. Transfer learning has proven extremely successful for traditional deep learning problems, resulting in faster 
  training and improved performance. Despite the increasing interest in GNNs and their use cases, there is little
  research on their transferability. This research demonstrates that transfer learning is effective with GNNs, and 
  describes how source tasks and the choice of GNN impact the ability to learn generalisable knowledge. We perform 
  experiments using real-world and synthetic data within the contexts of node classification and graph classification.
  To this end, we also provide a general methodology for transfer learning experimentation and present a novel algorithm
  for generating synthetic graph classification tasks. We compare the performance of GCN, GraphSAGE and GIN across both 
  synthetic and real-world datasets. Our results demonstrate empirically that GNNs with inductive operations yield 
  statistically significantly improved transfer. Further, we show that similarity in community structure between source
  and target tasks support statistically significant improvements in transfer over and above the use of only the node attributes.

featured: true
tags:
  - Graph Neural Networks
  - Transfer Learning
  
image:
focal_point: ''
preview_only: false

slides: null
---
