---
title:  "If Dropout Limits Trainable Depth, Does Critical Initialisation Still Matter?  A Large-scale Statistical Analysis on ReLU Networks"
authors:
  - Arnu Pretorius
  - Elan Van Biljon
  - Benjamin van Niekerk
  - Ryan Eloff
  - Matthew Reynard
  - Steven James
  - Benjamin Rosman
  - Herman Kamper
  - Steve Kroon 

author_notes: []

publication: "*Pattern Recognition Letters*"

date: 2020-06-28T00:00:00Z
publishDate: 2022-10-05T00:00:00Z

# conf = 1, journal = 2, preprint = 3, report = 4, book = 5, book chapter = 6, thesis = 7, patent = 9
# workshop = 9, symposium = 10, extended abstract =11
publication_types:
- "2"

abstract: "Recent work in signal propagation theory has shown that dropout limits the depth to which information can propagate 
  through a neural network. In this paper, we investigate the effect of initialisation on training speed and generalisation for 
  ReLU networks within this depth limit. We ask the following research question: given that critical initialisation is crucial
  for training at large depth, if dropout limits the depth at which networks are trainable, does initialising critically still
  matter? We conduct a large-scale controlled experiment, and perform a statistical analysis of over 12 000 trained networks. 
  We find that (1) trainable networks show no statistically significant difference in performance over a wide range
  of non-critical initialisations; (2) for initialisations that show a statistically significant difference, the net
  effect on performance is small; (3) only extreme initialisations (very small or very large) perform worse than criticality.
  These findings also apply to standard ReLU networks of moderate depth as a special case of zero dropout. Our results 
  therefore suggest that, in the shallow-to-moderate depth setting, critical initialisation provides zero performance gains
  when compared to off-critical initialisations and that searching for off-critical initialisations that might improve training
  speed or generalisation, is likely to be a fruitless endeavour."

featured: true
tags:
  - Deep Learning
  - Machine Learning
  
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
