---
title:  "Dynamics Generalisation in Reinforcement Learning via Adaptive Context-Aware Policies"
authors:
  - Michael Beukman
  - Devon Jarvis
  - Richard Klein
  - Benjamin Rosman
  - Steven James

author_notes: []

publication: "In *Advances in Neural Information Processing Systems*"

date: 2023-12-04T00:00:00Z
publishDate: 2022-12-04T00:00:00Z

# conf = 1, journal = 2, preprint = 3, report = 4, book = 5, book chapter = 6, thesis = 7, patent = 9
# workshop = 9, symposium = 10, extended abstract =11
publication_types:
- "1"

abstract: While reinforcement learning has achieved remarkable successes in several domains, its real-world application
  is limited due to many methods failing to generalise to unfamiliar conditions. In this work, we consider the problem
  of generalising to new transition dynamics, corresponding to cases in which the environment's response to the agent's
  actions differs. For example, the gravitational force exerted on a robot depends on its mass and changes the robot's
  mobility. Consequently, in such cases, it is necessary to condition an agent's actions on extrinsic state information
  and pertinent contextual information reflecting how the environment responds. While the need for context-sensitive
  policies has been established, the manner in which context is incorporated architecturally has received less attention.
  Thus, in this work, we present an investigation into how context information should be incorporated into behaviour
  learning to improve generalisation. To this end, we introduce a neural network architecture, the Decision Adapter,
  which generates the weights of an adapter module and conditions the behaviour of an agent on the context information.
  We show that the Decision Adapter is a useful generalisation of a previously proposed architecture and empirically
  demonstrate that it results in superior generalisation performance compared to previous approaches in several environments.
  Beyond this, the Decision Adapter is more robust to irrelevant distractor variables than several alternative methods.


featured: true
tags:
  - Reinforcement Learning
  - Transfer Learning
  - Generalisation

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
