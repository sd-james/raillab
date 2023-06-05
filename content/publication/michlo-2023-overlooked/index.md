---
title:  "Overlooked Implications of the Reconstruction Loss for VAE Disentanglement"
authors:
  - Nathan Michlo
  - Richard Klein
  - Steven James

author_notes: []

publication: "*Proceedings of the Thirty-second International Joint Conference on Artificial Intelligence*"

date: 2023-08-26T00:00:00Z
publishDate: 2022-10-05T00:00:00Z

# conf = 1, journal = 2, preprint = 3, report = 4, book = 5, book chapter = 6, thesis = 7, patent = 9
# workshop = 9, symposium = 10, extended abstract =11
publication_types:
  - "1"

abstract: "Learning disentangled representations with variational 
  autoencoders (VAEs) is often attributed to the regularisation component of the loss. In this work,
  we highlight the interaction between data and the reconstruction term of the loss as the main contributor to disentanglement in VAEs. We show that
  standard benchmark datasets have unintended correlations between their subjective ground-truth factors
  and perceived axes in the data according to typical VAE reconstruction losses. Our work exploits this
  relationship to provide a theory for what constitutes an adversarial dataset under a given reconstruction
  loss. We verify this by constructing an example dataset that prevents disentanglement in state-of-the-art frameworks while maintaining human-intuitive
  ground-truth factors. Finally, we re-enable disentanglement by designing an example reconstruction
  loss that is once again able to perceive the ground-truth factors. Our findings demonstrate the subjective nature of 
  disentanglement and the importance of considering the interaction between the ground-truth factors, data and notably, the reconstruction
  loss, which is under-recognised in the literature."

featured: true
tags:
  - Representation Learning
  - Unsupervised Learning

links:
  - name: Supplementary Material
    url: michlo-2023-overlooked-supp.pdf

image:
  focal_point: ''
  preview_only: false

slides: null


---

