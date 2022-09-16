---
abstract: In this work, we consider the problem of procedural content generation for video game levels. 
  Prior approaches have relied on evolutionary search (ES) methods capable of generating diverse levels, 
  but this generation procedure is slow, which is problematic in real-time settings. Reinforcement learning
  (RL) has also been proposed to tackle the same problem, and while level generation is fast, training time 
  can be prohibitively expensive. We propose a framework to tackle the procedural content generation 
  problem that combines the best of ES and RL. In particular, our approach first uses ES to generate a 
  sequence of levels evolved over time, and then uses behaviour cloning to distil these levels into a policy, 
  which can then be queried to produce new levels quickly. We apply our approach to a maze game and 
  *Super Mario Bros*, with our results indicating that our approach does in fact decrease the time required 
  for level generation, especially when an increasing number of valid levels are required.
publication_types:
  - "1"
authors:
  - Nicholas Muir
  - Steven James
author_notes: []
publication: In *Proceedings of 43rd Conference of the South African Institute of Computer Scientists and Information Technologists*
title: Combining Evolutionary Search with Behaviour Cloning for Procedurally Generated Content
featured: true
tags:
  - Reinforcement Learning
  - Evolutionary Strategies
  - Procedural Content Generation
  - Games
date: 2022-07-18T00:00:00Z
projects:
  - ai-in-games
publishDate: 2022-08-11T00:00:00Z
---
