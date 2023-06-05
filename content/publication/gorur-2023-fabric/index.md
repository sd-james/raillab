---
title:  "FABRIC: A Framework for the Design and Evaluation of Collaborative Robots with Extended Human Adaptation"
authors:
  - Orhan Can Görür
  - Benjamin Rosman
  - Fikret Sivrikaya
  - Sahin Albayrak
  
author_notes: []

publication: "*ACM Transactions on Human-Robot Interaction*"

date: 2023-05-23T00:00:00Z
publishDate: 2022-10-05T00:00:00Z

# conf = 1, journal = 2, preprint = 3, report = 4, book = 5, book chapter = 6, thesis = 7, patent = 9
# workshop = 9, symposium = 10, extended abstract =11
publication_types:
  - "2"

abstract: "A limitation for collaborative robots (cobots) is their lack of ability to adapt to human partners, who typically
  exhibit an immense diversity of behaviors. We present an autonomous framework as a cobot's real-time decision-making 
  mechanism to anticipate a variety of human characteristics and behaviors, including human errors, toward a personalized
  collaboration. Our framework handles such behaviors in two levels: 1) short-term human behaviors are adapted through our
  novel Anticipatory Partially Observable Markov Decision Process (A-POMDP) models, covering a human's changing intent
  (motivation), availability, and capability; 2) long-term changing human characteristics are adapted by our novel Adaptive
  Bayesian Policy Selection (ABPS) mechanism that selects a short-term decision model, e.g., an A-POMDP, according to an
  estimate of a human's workplace characteristics, such as her expertise and collaboration preferences. To design and evaluate
  our framework over a diversity of human behaviors, we propose a pipeline where we first train and rigorously test the
  framework in simulation over novel human models. Then, we deploy and evaluate it on our novel physical experiment setup 
  that induces cognitive load on humans to observe their dynamic behaviors, including their mistakes, and their changing 
  characteristics such as their expertise. We conduct user studies and show that our framework effectively collaborates non-stop 
  for hours and adapts to various changing human behaviors and characteristics in real-time. That increases the efficiency and 
  naturalness of the collaboration with a higher perceived collaboration, positive teammate traits, and human trust. We believe
  that such an extended human adaptation is key to the long-term use of cobots."

featured: true
tags:
  - Human-Robot Collaboration
  - Intent Inference
  - Socially Collaborative Robots

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

url_pdf: https://dl.acm.org/doi/10.1145/3585276


---
