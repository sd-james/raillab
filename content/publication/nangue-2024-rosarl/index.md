---
title:  "ROSARL: Reward-Only Safe Reinforcement Learning"
authors:
  - Geraud Nangue Tasse
  - Tamlin Love
  - Mark Nemecek
  - Steven James
  - Benjamin Rosman

author_notes: []

publication: "*Reinforcement Learning Safety Workshop at RLC*"

date: 2024-08-09T00:00:00Z
publishDate: 2022-10-05T00:00:00Z

# conf = 1, journal = 2, preprint = 3, report = 4, book = 5, book chapter = 6, thesis = 7, patent = 8
# workshop = 9, symposium = 10, extended abstract =11
publication_types:
- "9"

abstract: "An important problem in reinforcement learning is designing agents that learn to solve tasks safely in an
  environment. A common solution is to define either a penalty in the reward function or a cost to be minimised when 
  reaching unsafe states. However, designing reward or cost functions is non-trivial and can increase with the
  complexity of the problem. To address this, we investigate the concept of a Minmax penalty, the smallest 
  penalty for unsafe states that leads to safe optimal policies, regardless of task rewards. We derive an upper
  and lower bound on this penalty by considering both environment diameter and controllability. Additionally, 
  we propose a simple algorithm for agents to estimate this penalty while learning task policies. Our experiments
  demonstrate the effectiveness of this approach in enabling agents to learn safe policies in high-dimensional 
  continuous control environments."


featured: true
tags:
  - Reinforcement Learning
  - Safety

#projects:
#  - composition


image:
focal_point: ''
preview_only: false

slides: null
---
