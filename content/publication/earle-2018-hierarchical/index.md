---
title:  "Hierarchical Subtask Discovery with Non-negative Matrix Factorization"
authors:
  - Adam Earle
  - Andrew Saxe
  - Benjamin Rosman
  
author_notes: []

publication: "*Proceedings of the Sixth International Conference on Learning Representations*"

date: 2018-04-30T00:00:00Z
publishDate: 2022-10-05T00:00:00Z

# conf = 1, journal = 2, preprint = 3, report = 4, book = 5, book chapter = 6, thesis = 7, patent = 9
# workshop = 9, symposium = 10, extended abstract =11
publication_types:
  - "1"

abstract: "Hierarchical reinforcement learning methods offer a powerful means of planning
  flexible behavior in complicated domains. However, learning an appropriate hierarchical
  decomposition of a domain into subtasks remains a substantial challenge. We
  present a novel algorithm for subtask discovery, based on the recently introduced
  multitask linearly-solvable Markov decision process (MLMDP) framework. The
  MLMDP can perform never-before-seen tasks by representing them as a linear
  combination of a previously learned basis set of tasks. In this setting, the subtask
  discovery problem can naturally be posed as finding an optimal low-rank approximation
  of the set of tasks the agent will face in a domain. We use non-negative
  matrix factorization to discover this minimal basis set of tasks, and show that the
  technique learns intuitive decompositions in a variety of domains. Our method has
  several qualitatively desirable features: it is not limited to learning subtasks with
  single goal states, instead learning distributed patterns of preferred states; it learns
  qualitatively different hierarchical decompositions in the same domain depending
  on the ensemble of tasks the agent will face; and it may be straightforwardly
  iterated to obtain deeper hierarchical decompositions."

featured: true
tags:
  - Reinforcement Learning
  - Subtask Discovery
  - Linearly-solvable Markov Decision Processes

image:
  focal_point: ''
  preview_only: false

projects:
  - composition


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
