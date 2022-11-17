---
title:  "Accounting for the Sequential Nature of States to Learn Representations in Reinforcement Learning"
authors:
  - Nathan Michlo
  - Devon Jarvis
  - Richard Klein
  - Steven James

author_notes: []

publication: "*The 5th Multi-disciplinary Conference on Reinforcement Learning and Decision Making*"

date: 2022-06-08T00:00:00Z
publishDate: 2022-10-05T00:00:00Z

# conf = 1, journal = 2, preprint = 3, report = 4, book = 5, book chapter = 6, thesis = 7, patent = 9
# workshop = 9, symposium = 10, extended abstract =11
publication_types:
  - "11"

abstract: In this work, we investigate the properties of data that cause popular representation learning approaches to fail. In particular, we find that in environments where states do not significantly overlap, variational autoencoders (VAEs) fail to learn useful features. We demonstrate this failure in a simple gridworld domain, and then provide a solution in the form of metric learning. However, metric learning requires supervision in the form of a distance function, which is absent in reinforcement learning. To overcome this, we leverage the sequential nature of states in a replay buffer to approximate a distance metric and provide a weak supervision signal, under the assumption that temporally close states are also semantically similar. We modify a VAE with triplet loss and demonstrate that this approach is able to learn useful features for downstream tasks, without additional supervision, in environments where standard VAEs fail.

featured: true
tags:
  - Representation Learning
  - Metric Learning
  - Reinforcement Learning



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

