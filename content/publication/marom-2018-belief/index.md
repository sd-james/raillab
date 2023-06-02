---
title:  "Belief Reward Shaping in Reinforcement Learning"
authors:
  - Ofir Marom
  - Benjamin Rosman

author_notes: []

publication: "*Proceedings of the AAAI Conference on Artificial Intelligence*"

date: 2018-02-02T00:00:00Z
publishDate: 2022-10-05T00:00:00Z

# conf = 1, journal = 2, preprint = 3, report = 4, book = 5, book chapter = 6, thesis = 7, patent = 9
# workshop = 9, symposium = 10, extended abstract =11
publication_types:
  - "1"

abstract: "A key challenge in many reinforcement learning problems is
  delayed rewards, which can significantly slow down learning.
  Although reward shaping has previously been introduced to
  accelerate learning by bootstrapping an agent with additional
  information, this can lead to problems with convergence. We
  present a novel Bayesian reward shaping framework that augments
  the reward distribution with prior beliefs that decay
  with experience. Formally, we prove that under suitable conditions
  a Markov decision process augmented with our framework
  is consistent with the optimal policy of the original
  MDP when using the Q-learning algorithm. However, in general
  our method integrates seamlessly with any reinforcement
  learning algorithm that learns a value or action-value function
  through experience. Experiments are run on a gridworld and
  a more complex backgammon domain that show that we can
  learn tasks significantly faster when we specify intuitive priors
  on the reward distribution."

featured: true
tags:
  - Reinforcement Learning
  - Reward Shaping


image:
  focal_point: ''
  preview_only: false

slides: null

links:
  - name: Supplementary Material
    url: marom-2018-belief-supp.pdf

#url_dataset: "#"
#url_project: ""
#publication_short: ""
#url_source: "#"
#url_slides: ""
#url_poster: "#"
#url_code: "#"
# doi: ""



---


