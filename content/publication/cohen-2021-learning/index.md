---
title:  "Learning to Follow Language Instructions with Compositional Policies"
authors:
  - Vanya Cohen
  - Geraud Nangue Tasse
  - Nakul Gopalan
  - Steven James
  - Matthew Gombolay
  - Benjamin Rosman

author_notes: [Equal contribution, Equal contribution]

publication: "*AAAI Fall Symposium on AI for Human-Robot Interaction*"

date: 2021-11-04T00:00:00Z
publishDate: 2022-10-05T00:00:00Z

# conf = 1, journal = 2, preprint = 3, report = 4, book = 5, book chapter = 6, thesis = 7, patent = 9
# workshop = 9, symposium = 10, extended abstract =11
publication_types:
  - "10"

abstract: We propose a framework that learns to execute natural language
  instructions in an environment consisting of goal-reaching
  tasks that share components of their task descriptions.
  Our approach leverages the compositionality of both
  value functions and language, with the aim of reducing the
  sample complexity of learning novel tasks. First, we train a
  reinforcement learning agent to learn value functions that can
  be subsequently composed through a Boolean algebra to solve
  novel tasks. Second, we fine-tune a seq2seq model pretrained
  on web-scale corpora to map language to logical expressions
  that specify the required value function compositions. Evaluating
  our agent in the BabyAI domain, we observe a decrease of
  86% in the number of training steps needed to learn a second
  task after mastering a single task. Results from ablation studies
  further indicate that it is the combination of compositional
  value functions and language representations that allows the
  agent to quickly generalize to new tasks

featured: true
tags:
  - Instruction Following
  - Natural Language Processing
  - Reinforcement Learning
  - Composition

projects:
  - composition

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


