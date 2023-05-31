---
title:  "Multi-Pass Q-Networks for Deep Reinforcement Learning with Parameterised Action Spaces"
authors:
  - Craig Bester
  - Steven James
  - George Konidaris
  
author_notes: []

publication: "*Technical Report*"

date: 2019-05-10T00:00:00Z
publishDate: 2022-10-05T00:00:00Z

# conf = 1, journal = 2, preprint = 3, report = 4, book = 5, book chapter = 6, thesis = 7, patent = 9
# workshop = 9, symposium = 10, extended abstract =11
publication_types:
  - "3"

abstract: "Parameterised actions in reinforcement learning are composed of discrete actions with continuous action-parameters.
  This provides a framework for solving complex domains that require combining high-level actions with flexible control. 
  The recent P-DQN algorithm extends deep Q-networks to learn over such action spaces. However, it treats all action-parameters
  as a single joint input to the Q-network, invalidating its theoretical foundations. We analyse the issues with this 
  approach and propose a novel method, multi-pass deep Q-networks, or MP-DQN, to address them. We empirically demonstrate
  that MP-DQN significantly outperforms P-DQN and other previous algorithms in terms of data efficiency and converged policy
  performance on the Platform, Robot Soccer Goal, and Half Field Offense domains."

featured: true
tags:
  - Reinforcement Learning
  - Parameterised Actions

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
