---
title:  "Hierarchical Reinforcement Learning with AI Planning Models"
authors:
  - Junkyu Lee
  - Michael Katz
  - Don Joven Agravante
  - Miao Liu
  - Geraud Nangue Tasse
  - Tim Klinger
  - Shirin Sohrabi


author_notes: []

publication: "*NeurIPS Workshop on Generalization in Planning*"

date: 2023-12-03T00:00:00Z
publishDate: 2022-10-05T00:00:00Z

# conf = 1, journal = 2, preprint = 3, report = 4, book = 5, book chapter = 6, thesis = 7, patent = 8
# workshop = 9, symposium = 10, extended abstract =11
publication_types:
- "9"

abstract: Deep Reinforcement Learning (DRL) has shown breakthroughs in solving challenging problems, such as pixel-based
  games and continuous control tasks. In complex environments, infusing prior domain knowledge is essential to achieve 
  sample efficiency and generalization.Neuro-symbolic AI seeks systematic domain knowledge infusion into neural network-based 
  learning, and existing neuro-symbolic approaches for sequential decision-making leverage hierarchical reinforcement learning
  (HRL) by infusing symbolically specified prior knowledge on desired trajectories.However, this requires finding 
  symbolic solutions in RL environments before learning, and it is difficult to handle the divergence between unknown
  RL dynamics and prior knowledge. Such shortcomings result in loose and manual neuro-symbolic integration and degrade
  the generalization capability.In this paper, we integrate the options framework in HRL with an AI planning model to resolve
  the shortcomings in earlier approaches and generalize beyond RL environments where pre-specified partial solutions are valid.
  Our approach defines options from AI planning operators by establishing the connection between the two transition systems in
  the options framework and the AI planning task. Then, we show an option policy learning method that integrates an AI planner
  and model-free DRL algorithms with intrinsic rewards, encouraging consistency between the two transition systems. We design 
  a suite of MiniGrid environments that cover the increasing levels of difficulties in exploration, where our empirical evaluation
  clearly shows the advantage of HRL with AI planning models.



featured: true
tags:
  - Reinforcement Learning
  - Hierarchical Reinforcement Learning
  - Planning

image:
focal_point: ''
preview_only: false

slides: null
---
