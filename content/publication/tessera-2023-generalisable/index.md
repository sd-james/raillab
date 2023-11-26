---
title:  "Generalisable Agents for Neural Network Optimisation"
authors:
  - Kale-ab Tessera
  - Callum Tilbury
  - Sasha Abramowitz
  - Ruan de Kock
  - Omayma Mahjoub
  - Benjamin Rosman
  - Sara Hooker
  - Arnu Pretorius 

author_notes: []

publication: "*Workshop on Advancing Neural Network Training: Computational Efficiency, Scalability, and Resource Optimization at NeurIPS*"

date: 2023-12-03T00:00:00Z
publishDate: 2022-10-05T00:00:00Z

# conf = 1, journal = 2, preprint = 3, report = 4, book = 5, book chapter = 6, thesis = 7, patent = 8
# workshop = 9, symposium = 10, extended abstract =11
publication_types:
- "9"

abstract: Optimising deep neural networks is a challenging task due to complex training dynamics, high computational
  requirements, and long training times. To address this difficulty, we propose the framework of Generalisable Agents
  for Neural Network Optimisation (GANNO)---a multi-agent reinforcement learning (MARL) approach that learns to improve
  neural network optimisation by dynamically and responsively scheduling hyperparameters during training. GANNO 
  utilises an agent per layer that observes localised network dynamics and accordingly takes actions to adjust these 
  dynamics at a layerwise level to collectively improve global performance. In this paper, we use GANNO to control the
  layerwise learning rate and show that the framework can yield useful and responsive schedules that are competitive with
  handcrafted heuristics. Furthermore, GANNO is shown to perform robustly across a wide variety of unseen initial 
  conditions, and can successfully generalise to harder problems than it was trained on. Our work presents an overview 
  of the opportunities that this paradigm offers for training neural networks, along with key challenges that remain 
  to be overcome.



featured: true
tags:
  - Neural Networks
  - Hyperparameter Optimisation
  - Deep Learning
  - Reinforcement Learning

image:
focal_point: ''
preview_only: false

slides: null
---
