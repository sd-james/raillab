---
title:  "Skill Machines: Temporal Logic Composition in Reinforcement Learning"
authors:
  - Geraud Nangue Tasse
  - Devon Jarvis
  - Steven James
  - Benjamin Rosman


author_notes: []

publication: "In *Lifelong Learning of High-level Cognitive and Reasoning Skills Workshop @ IROS 2022*"

date: 2022-10-23T00:00:00Z
publishDate: 2022-10-05T00:00:00Z

# conf = 1, journal = 2, preprint = 3, report = 4, book = 5, book chapter = 6, thesis = 7, patent = 9
# workshop = 9, symposium = 10, extended abstract =11
publication_types:
  - "9"

abstract: A major challenge in reinforcement learning is
  specifying tasks in a manner that is both interpretable and
  verifiable. One common approach is to specify tasks through
  reward machines --- finite state machines that encode the task to
  be solved. We introduce skill machines, a representation that can
  be learned directly from these reward machines that encode the
  solution to such tasks. We propose a framework where an agent
  first learns a set of base skills in a reward-free setting, and then
  combines these skills with the learned skill machine to produce
  composite behaviours specified by any regular language, such as
  linear temporal logics. This provides the agent with the ability
  to map from complex logical task specifications to near-optimal
  behaviours zero-shot. We demonstrate our approach in both a
  tabular and high-dimensional video game environment, where
  an agent is faced with several of these complex, long-horizon
  tasks. Our results indicate that the agent is capable of satisfying
  extremely complex task specifications, producing near optimal
  performance with no further learning. Finally, we demonstrate
  that the performance of skill machines can be improved with
  regular off-policy reinforcement learning algorithms when optimal
  behaviours are desired.

featured: true
tags:
  - Reinforcement Learning
  - Composition
  - Reward Machine
  - Linear Temporal Logic

image:
  focal_point: ''
  preview_only: false

projects:
  - composition

url_video: "https://www.youtube.com/watch?v=J8PyRw83C4s"


---

