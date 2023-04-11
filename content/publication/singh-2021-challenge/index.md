---
title:  "The Challenge of Redundancy on Multi-Agent Value Factorisation"
authors:
  - Siddarth Singh
  - Benjamin Rosman

author_notes: []

publication: "*NeurIPS Workshop on Cooperative AI*"

date: 2021-12-06T00:00:00Z
publishDate: 2022-10-05T00:00:00Z

# conf = 1, journal = 2, preprint = 3, report = 4, book = 5, book chapter = 6, thesis = 7, patent = 9
# workshop = 9, symposium = 10, extended abstract =11
publication_types:
  - "9"

abstract: "Recently there has been great development in the field of multi-agent reinforcement
  learning (MARL). In the cooperative partially observable multi-agent setting
  central value functions have been used to perform multi-agent credit assignment
  for joint global rewards. The standard solution is the use of centralised training
  and decentralised execution where a central critic conditions the polices of the
  cooperative agents based on a central observation. Simulated training environments
  designed using video games typically only contain exactly the number of agents
  required to solve the tasks based on preexisting knowledge of the game dynamics
  and human player solutions. In a more general case, there is likely to be a larger
  number of agents in an environment than is required to solve the task. These
  redundant agents reduce overall performance by enlarging the dimensionality of
  the ground truth state if available and increasing the size of the joint policy used
  to solve the environment. In the case where no ground truth state is available a
  concatenation of all local observations is used which scales in size with the number
  of agents and becomes insufficient to condition the centralised critic in large spaces.
  We propose leveraging layerwise relevance propagation (LRP) to instead separate
  the learning of the joint value function and generation of local reward signals and
  create a new MARL algorithm: relevance decomposition network (RDN). We
  compare our method to other state of the art MARL algorithms in challenging
  StarCraft2 and simpler matrix game environments. We show that decomposition
  algorithms' performance and the usefulness of the state space degrades as the
  number of redundant agents increases"


featured: true
tags:
  - Multi-agent Reinforcement Learning
  - Credit Assignment
  
image:
  focal_point: ''
  preview_only: false

slides: null


---
