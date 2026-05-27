---
title:  "Unsupervised Hierarchical Skill Discovery"
authors:
  - Damion Harvey
  - Geraud Nangue Tasse
  - Benjamin Rosman
  - Branden Ingram
  - Steven James 

author_notes: []

publication: "In *International Conference on Machine Learning*"

date: 2026-07-06T00:00:00Z
publishDate: 2022-12-04T00:00:00Z

# conf = 1, journal = 2, preprint = 3, report = 4, book = 5, book chapter = 6, thesis = 7, patent = 9
# workshop = 9, symposium = 10, extended abstract =11
publication_types:
- "1"

abstract: We consider the problem of unsupervised skill segmentation and hierarchical structure discovery in reinforcement learning.
  While recent approaches have sought to segment trajectories into reusable skills or options, most rely on action labels, 
  rewards, or handcrafted annotations, limiting their applicability. We propose a method that segments unlabelled trajectories
  into skills and induces a hierarchical structure over them using a grammar-based approach. The resulting hierarchy captures 
  both low-level behaviours and their composition into higher-level skills. We evaluate our approach in high-dimensional,
  pixel-based environments, including Craftax and the full, unmodified version of Minecraft. Using metrics for skill segmentation,
  reuse, and hierarchy quality, we find that our method consistently produces more structured and semantically meaningful 
  hierarchies than existing baselines. Furthermore, as a proof of concept, we demonstrate that these discovered hierarchies 
  accelerate and stabilise learning on downstream reinforcement learning tasks.


featured: true
tags:
  - Learning from Demonstration
  - Hierarchical Reinforcement Learning

projects:
  - symbols

image:
focal_point: ''
preview_only: false

slides: null

#url_dataset: "#"
#publication_short: ""
#url_source: "#"
#url_video: "#"
#url_slides: ""
#url_poster: "#"
url_code: "https://github.com/dami2106/Unsupervised-Hierarchical-Skill-Discovery"
# doi: ""



---
