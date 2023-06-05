---
title:  "The Challenge of Redundancy on Multi-agent Value Factorisation"
authors:
  - Siddarth Singh
  - Benjamin Rosman
  
author_notes: []

publication: "*International Conference on Autonomous Agents and Multiagent Systems*"

date: 2023-05-29T00:00:00Z
publishDate: 2022-10-05T00:00:00Z

# conf = 1, journal = 2, preprint = 3, report = 4, book = 5, book chapter = 6, thesis = 7, patent = 9
# workshop = 9, symposium = 10, extended abstract =11
publication_types:
  - "11"

abstract: "In the field of cooperative multi-agent reinforcement learning (MARL),
  the standard paradigm is the use of centralised training and decentralised
  execution where a central critic conditions the policies of
  the cooperative agents based on a central state. It has been shown,
  that in cases with large numbers of redundant agents these methods
  become less effective. In a more general case, there is likely to be a
  larger number of agents in an environment than is required to solve
  the task. These redundant agents reduce performance by enlarging
  the dimensionality of both the state space and and increasing the
  size of the joint policy used to solve the environment. We propose
  leveraging layerwise relevance propagation (LRP) to instead separate
  the learning of the joint value function and generation of
  local reward signals and create a new MARL algorithm: relevance
  decomposition network (RDN). We find that although the performance
  of both baselines VDN and Qmix degrades with the number
  of redundant agents, RDN is unaffected."

featured: true
tags:
  - Multi-agent Reinforcement Learning
  - Reinforcement Learning

image:
  focal_point: ''
  preview_only: false

slides: null

#url_dataset: "#"
#url_project: ""
#publication_short: ""
#url_source: "#"
#url_slides: ""
#url_poster: "#"
#url_code: "#"
# doi: ""



---
