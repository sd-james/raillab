---
title:  "Utilising Uncertainty for Efficient Learning of Likely-Admissible Heuristics"
authors:
  - Ofir Marom
  - Benjamin Rosman

author_notes: []

publication: "In *International Conference on Automated Planning and Scheduling*"

date: 2020-10-19T00:00:00Z
publishDate: 2022-10-05T00:00:00Z

# conf = 1, journal = 2, preprint = 3, report = 4, book = 5, book chapter = 6, thesis = 7, patent = 9
# workshop = 9, symposium = 10, extended abstract =11
publication_types:
- "1"

abstract: "Likely-admissible heuristics have previously been introduced as heuristics that are admissible with some probability.
  While such heuristics only produce likely-optimal plans, they have the advantage that it is more feasible to learn such
  heuristics from training data using machine learning algorithms. Naturally, it is ideal if this training data consists of
  optimal plans, but such data is often prohibitive to produce. To overcome this, previous work introduced a bootstrap procedure
  that generates training data using random task generation that incrementally learns on more complex tasks. However, 1) using 
  random task generation is inefficient and; 2) the procedure generates non-optimal plans for training and this causes errors 
  to compound as learning progresses, resulting in high suboptimality. In this paper we introduce a framework that utilises 
  uncertainty to overcome the shortcomings of previous approaches. In particular, we show that we can use uncertainty to efficiently
  explore task-space when generating training tasks, and then learn likely-admissible heuristics that produce low suboptimality.
  We illustrate the advantages of our approach on the 15-puzzle, 24-puzzle, 24-pancake and 15-blocksworld domains using Bayesian 
  neural networks to model uncertainty."

featured: true
tags:
  - Planning
  - Uncertainty
  - Bayesian Learning
  
image:
focal_point: ''
preview_only: false

slides: null

links:
  - name: Supplementary Material
    url: marom-2020-utilising_supp.pdf

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


