---
title:  "MiDaS: A Large-Scale Minecraft Dataset for Non-Natural Image Benchmarking"
authors:
  - David Torpey
  - Max Parkin
  - Jonah Alter
  - Richard Klein
  - Steven James

author_notes: []

publication: "*Journal of Electronic Imaging*"

date: 2024-02-05T00:00:00Z
publishDate: 2022-10-05T00:00:00Z

# conf = 1, journal = 2, preprint = 3, report = 4, book = 5, book chapter = 6, thesis = 7, patent = 9
# workshop = 9, symposium = 10, extended abstract =11
publication_types:
- "2"

abstract: "Reinforcement learning (RL) has recently made several significant advances using video games as a testbed. 
  While many of these games are relatively self-contained, there has been a recent push to develop agents capable of 
  tackling massive, open-ended environments that are more reminiscent of the real world. One of the most popular of these 
  platforms is Minecraft, but to attain human-level performance, agents must be able to learn, plan, and reason using 
  high-dimensional image input. Commonly, an agent will attempt to extract lower-dimensional features that assist with 
  downstream tasks. However, representation learning techniques have primarily been applied to real-world, natural image
  datasets, and it is unclear how these same methods might translate to an artificial world with non-natural images. 
  We therefore present MiDaS, a novel large-scale Minecraft dataset featuring 36,000 labeled images across 60 classes.
  MiDaS contains information about both the blocks in the image, critical to solving the game, as well as auxiliary 
  information such as time of day and biome. Further, we perform an evaluation of various models to benchmark performance
  on this new dataset. Since RL agents must be capable of learning features without labels, we include benchmarks of 
  various self-supervised learning approaches on the dataset. Our results indicate that self-supervised methods perform
  best in the linear evaluation paradigm, particularly in low-label settings with a ResNet-based backbone,
  whereas ImageNet-pretraining assists more in the fine-tuning setting. The full dataset is available at
  https://github.com/MinecraftDataset/MiDaS."

featured: true
tags:
  - Self-supervised Learning
  - Dataset
  - Benchmark

  
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
doi: "https://doi.org/10.1117/1.JEI.33.1.013035"
---


