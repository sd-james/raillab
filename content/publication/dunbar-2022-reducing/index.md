---
abstract: Planning is a computationally expensive process, which can limit the reactivity of autonomous agents.
  Planning problems are usually solved in isolation, independently of similar, previously solved problems.
  The depth of search that a planner requires to find a solution, known as the planning horizon, is a critical
  factor when integrating planners into reactive agents. We consider the case of an agent repeatedly carrying 
  out a task from different initial states. We propose a combination of classical planning and model-free 
  reinforcement learning to reduce the planning horizon over time. Control is smoothly transferred from the 
  planner to the model-free policy as the agent compiles the planner’s policy into a value function. Local
  exploration of the model-free policy allows the agent to adapt to the environment and eventually overcome 
  model inaccuracies. We evaluate the efficacy of our framework on symbolic PDDL domains and a stochastic 
  grid world environment and show that we are able to significantly reduce the planning horizon while improving
  upon model inaccuracies.
slides: null
publication_types:
  - "1"
authors:
  - Logan Dunbar
  - Benjamin Rosman
  - Anthony G. Cohn
  - Matteo Leonetti
author_notes: []
publication: In *Proceedings of the European Conference on Machine Learning and Principles and Practice of Knowledge Discovery in Databases*
title: Reducing the Planning Horizon through Reinforcement Learning
featured: true
tags:
  - Planning
  - Reinforcement Learning
date: 2022-09-19T00:00:00Z
publishDate: 2022-08-10T00:00:00Z
doi: ""
---
