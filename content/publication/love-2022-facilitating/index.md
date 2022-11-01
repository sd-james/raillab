---
title:  "Facilitating Safe Sim-to-Real through Simulator Abstraction and Zero-shot Task Composition"
authors:
  - Tamlin Love
  - Devon Jarvis
  - Geraud Nangue Tasse
  - Branden Ingram
  - Steven James
  - Benjamin Rosman
  
author_notes: [Equal contribution, Equal contribution, Equal contribution]

publication: "In *Lifelong Learning of High-level Cognitive and Reasoning Skills Workshop @ IROS 2022*"

date: 2022-10-23T00:00:00Z
publishDate: 2022-10-05T00:00:00Z

# conf = 1, journal = 2, preprint = 3, report = 4, book = 5, book chapter = 6, thesis = 7, patent = 9
# workshop = 9, symposium = 10, extended abstract =11
publication_types:
  - "9"

abstract: Simulators are a fundamental part of training
  robots to solve complex control and navigation tasks. This
  is due to the speed and safety they offer in comparison
  to training directly on a physical system, where exploration
  may drive the system towards dangerous action for itself
  and its environment. However, simulators have a fundamental
  drawback known as the *reality gap*, which describes the
  discrepancy in performance which occurs when a robot trained
  in simulation performs the same task in the real world. The
  reality gap is prohibitive as it means many of the most powerful
  recent advances in reinforcement learning (RL) cannot be
  used with robots due to their high sample complexity which
  makes physical training infeasible. In this work we introduce a
  framework for applying high sample complexity RL algorithms
  to robots by leveraging recent advances in hierarchical RL and
  skill composition. We demonstrate that adapting hierarchical
  RL techniques allows us to close the reality gap at multiple
  levels of abstraction. As a result we are able to train a
  robot to perform combinatorially many tasks within a domain
  with minimal training on a physical system or steps of error
  correction. We believe this work provides an important starting
  framework for applying hierarchical RL to perform sim-to-real
  generalisation at multiple levels of abstraction.

featured: true
tags:
  - Reinforcement Learning
  - Composition
  - Robotics

projects:
  - composition

image:
  focal_point: ''
  preview_only: false

slides: null
url_video: "https://youtu.be/Xyx4S--BUCIG"

#url_dataset: "#"
#url_project: ""
#publication_short: ""
#url_source: "#"
#url_slides: ""
#url_poster: "#"
#url_code: "#"
# doi: ""



---

