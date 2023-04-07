---
title:  "Analysing the Effects of Transfer Learning on Low-Resourced Named Entity Recognition Performance"
authors:
  - Michael Beukman

author_notes: []

publication: "*3rd Workshop on African Natural Language Processing*"

date: 2022-04-26T00:00:00Z
publishDate: 2022-10-05T00:00:00Z

# conf = 1, journal = 2, preprint = 3, report = 4, book = 5, book chapter = 6, thesis = 7, patent = 9
# workshop = 9, symposium = 10, extended abstract =11
publication_types:
- "9"

abstract: Transfer learning has led to large gains in performance for nearly all NLP tasks while making downstream models 
  easier and faster to train. This has also been extended to low-resourced languages, with some success. We investigate
  the properties of transfer learning between 10 low-resourced languages, from the perspective of a named entity recognition 
  task, specifically how much adaptive fine-tuning improves performance, the efficacy of zero-shot transfer as well as 
  the effect of learning on the contextual embeddings computed from the model. Our results give some insight into zero-shot
  performance as well as the impact of different training schemes and data overlap between the training and testing languages. 
  Particularly, we find that models with the best generalisation to other languages suffer in individual language performance, 
  while models that perform well on a single language often do so at the expense of generalising to others. In the interest 
  of reproducibility, we publicly release our source code and models.

featured: true
tags:
  - Natural Language Processing
  - Low-resource Languages
  - Named Entity Recognition
  
image:
focal_point: ''
preview_only: false

slides: null
---
