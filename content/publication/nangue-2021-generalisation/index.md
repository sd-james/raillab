---
title:  "Generalisation in Lifelong Reinforcement Learning through Logical Composition"
authors:
  - Geraud Nangue Tasse
  - Steven James
  - Benjamin Rosman

author_notes: []

publication: "*NeurIPS Deep Reinforcement Learning Workshop*"

date: 2021-12-06T00:00:00Z
publishDate: 2022-10-05T00:00:00Z

# conf = 1, journal = 2, preprint = 3, report = 4, book = 5, book chapter = 6, thesis = 7, patent = 9
# workshop = 9, symposium = 10, extended abstract =11
publication_types:
  - "9"

abstract: "We leverage logical composition in reinforcement learning to create a framework
  that enables an agent to autonomously determine whether a new task can be
  immediately solved using its existing abilities, or whether a task-specific skill
  should be learned. In the latter case, the proposed algorithm also enables the
  agent to learn the new task faster by generating an estimate of the optimal policy.
  Importantly, we provide two main theoretical results: we give bounds on the
  performance of the transferred policy on a new task, and we give bounds on the
  necessary and sufficient number of tasks that need to be learned throughout an
  agent’s lifetime to generalise over a distribution. We verify our approach in a
  series of experiments, where we perform transfer learning both after learning a
  set of base tasks, and after learning an arbitrary set of tasks. We also demonstrate
  that as a side effect of our transfer learning approach, an agent can produce an
  interpretable Boolean expression of its understanding of the current task. Finally,
  we demonstrate our approach in the full lifelong setting where an agent receives
  tasks from an unknown distribution and, starting from zero skills, is able to quickly
  generalise over the task distribution after learning only a few tasks—which are
  sub-logarithmic in the size of the task space."


featured: true
tags:
  - Reinforcement Learning
  - Lifelong Learning
  - Transfer Learning

projects:
  - composition

image:
  focal_point: ''
  preview_only: false

slides: null


---
