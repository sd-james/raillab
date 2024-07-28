---
title:  "Optimal Task Generalisation in Cooperative Multi-Agent Reinforcement Learning"
authors:
  - Simon Rosen
  - Abdel Mfougouon Njupoun
  - Geraud Nangue Tasse
  - Steven James
  - Benjamin Rosman

author_notes: []

publication: "*Coordination and Cooperation in Multi-Agent Reinforcement Learning Workshop at RLC*"

date: 2024-08-09T00:00:00Z
publishDate: 2022-10-05T00:00:00Z

# conf = 1, journal = 2, preprint = 3, report = 4, book = 5, book chapter = 6, thesis = 7, patent = 8
# workshop = 9, symposium = 10, extended abstract =11
publication_types:
- "9"

abstract: "While task generalisation is widely studied in the context of single-agent reinforcement learning (RL), 
  little research exists in the context of multi-agent RL. The research that does exist usually considers task
  generalisation implicitly as a part of the environment, and when it is considered explicitly there are no theoretical 
  guarantees. We propose Goal-Oriented Learning for Multi-Task Multi-Agent RL (GOLeMM), a method that achieves provably 
  optimal task generalisation that, to the best of our knowledge, has not been achieved before in MARL. After learning 
  an optimal goal-oriented value function for a single arbitrary task, our method can zero-shot infer the optimal 
  policy for any other task in the distribution given only knowledge of the terminal rewards for each agent for the 
  new task and learnt task. Empirically we show that our method is able to generalise over a full task distribution, 
  while representative baselines are only able to learn a small subset of the task distribution."


featured: true
tags:
  - Multi-agent Reinforcement Learning
  - Reinforcement Learning
  - Transfer Learning

projects:
  - composition


image:
focal_point: ''
preview_only: false

slides: null
---
