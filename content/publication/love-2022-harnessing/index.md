---
title:  "Harnessing the Wisdom of an Unreliable Crowd for Autonomous Decision Making"
authors:
  - Tamlin Love
  - Ritesh Ajoodha
  - Benjamin Rosman

author_notes: []

publication: "*The 5th Multi-disciplinary Conference on Reinforcement Learning and Decision Making*"

date: 2022-06-08T00:00:00Z
publishDate: 2022-10-05T00:00:00Z

# conf = 1, journal = 2, preprint = 3, report = 4, book = 5, book chapter = 6, thesis = 7, patent = 9
# workshop = 9, symposium = 10, extended abstract =11
publication_types:
  - "11"

abstract: In Reinforcement Learning there is often a need for greater sample efficiency when learning an optimal policy,
  whether due to the complexity of the problem or the difficulty in obtaining data. One approach to tackling this problem 
  is to introduce external information to the agent in the form of domain expert advice. Indeed, it has been shown 
  that giving an agent advice in the form of state-action pairs during learning can greatly improve the rate at which
  the agent converges to an optimal policy. These approaches typically assume a single, infallible expert. However, 
  it may be desirable to collect advice from multiple experts to further improve sample efficiency. This may introduce 
  the problem of multiple experts offering conflicting advice. In general, experts (especially humans) can give incorrect 
  advice. The problem of incorporating advice from multiple, potentially unreliable experts is considered an open problem 
  in the field of Assisted Reinforcement Learning. 

  Contextual bandits are an important class of problems with a broad range 
  of applications such as in medicine, finance and recommendation systems. To address the problem of learning with expert advice 
  from multiple, unreliable experts, we present CLUE (Cautiously Learning with Unreliable Experts), a framework which allows any
  contextual bandit algorithm to benefit from incorporating expert advice into its decision making. It does so by modelling the
  unreliability of each expert, and using this model to pool advice together to determine the probability of each action being 
  optimal. 
  
  We perform a number of experiments with simulated experts over randomly generated environments. Our results show 
  that CLUE benefits from improved sample efficiency when advised by reliable experts, but is robust to the presence of 
  unreliable experts, and is able to benefit from multiple experts. This research provides an approach to incorporating the 
  advice of humans of varying levels of expertise in the learning process.

featured: true
tags:
  - Reinforcement Learning
  - Human-Computer Interaction



image:
  focal_point: ''
  preview_only: false

slides: null

#url_dataset: "#"
#url_project: ""
#publication_short: ""
#url_source: "#"
#url_video: "#"
#url_slides: ""
#url_poster: "#"
#url_code: "#"
# doi: ""

---

