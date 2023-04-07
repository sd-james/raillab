---
title:  "Diverse Partner Creation with Partner Prediction for Robust K-Level Reasoning"
authors:
  - Jarrod Shipton
  - Benjamin Rosman


author_notes: []

publication: "*The 5th Multi-disciplinary Conference on Reinforcement Learning and Decision Making*"

date: 2022-06-08T00:00:00Z
publishDate: 2022-10-05T00:00:00Z

# conf = 1, journal = 2, preprint = 3, report = 4, book = 5, book chapter = 6, thesis = 7, patent = 9
# workshop = 9, symposium = 10, extended abstract =11
publication_types:
  - "11"

abstract: In Multi-agent Reinforcement Learning (MARL) there has been a substantial move towards creating algorithms which
  can be trained to work cooperatively with partners. In general this is done in a self play (SP) setting, where the agents
  are set to play and train with copies of themselves in a Decentralized Partially Observable Markov Decision Process
  setting. Agents trained with SP often result in behaviour such that arbitrary conventions, or "handshakes", will be
  formed in order to more efficiently achieve their goal. These arbitrary handshakes can be seen as unwanted behaviours
  as they creates the issue that when agents are paired with novel agents they will often not be able to complete a task
  cooperatively, even when paired with different training runs of the same algorithm. A valuable architecture to help
  tackle this problem is synchronous K-level reasoning with a best response (SyKLRBR), which creates agents that have
  policies based on grounded information which are robust to various handshakes. Weaknesses are still shown in that
  certain agents with specific handshakes still outperform this agent when paired with one another as compared with
  the SyKLRBR agent. This work expands on the SyKLRBR framework by factorizing the action-observation histories to
  fit a belief over a diverse set of agents created with multiple different runs of a modified SyKLRBR algorithm. These
  modifications allow the algorithm to create and identify a robust set of agents with various handshakes that could exist
  in potential novel partners, ultimately allowing it to take advantage of these handshakes for better results.

featured: true
tags:
  - Multi-agent Reinforcement Learning
  - Theory of Mind 


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

