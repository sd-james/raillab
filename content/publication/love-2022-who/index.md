---
title:  "Who should I trust? Cautiously learning with unreliable experts"
authors:
  - Tamlin Love
  - Ritesh Ajoodha
  - Benjamin Rosman

author_notes: []

publication: "*Neural Computing and Applications*"

date: 2022-09-01T00:00:00Z
publishDate: 2022-10-05T00:00:00Z

# conf = 1, journal = 2, preprint = 3, report = 4, book = 5, book chapter = 6, thesis = 7, patent = 9
# workshop = 9, symposium = 10, extended abstract =11
publication_types:
  - "2"

abstract: An important problem in reinforcement learning is the need for greater sample efficiency. One approach to dealing with this problem is to incorporate external information elicited from a domain expert in the learning process. Indeed, it has been shown that incorporating expert advice in the learning process can improve the rate at which an agent’s policy converges. However, these approaches typically assume a single, infallible expert; learning from multiple and/or unreliable experts is considered an open problem in assisted reinforcement learning. We present CLUE (cautiously learning with unreliable experts), a framework for learning single-stage decision problems with action advice from multiple, potentially unreliable experts that augments an unassisted learning with a model of expert reliability and a Bayesian method of pooling advice to select actions during exploration. Our results show that CLUE maintains the benefits of traditional approaches when advised by reliable experts, but is robust to the presence of unreliable experts. When learning with multiple experts, CLUE is able to rank experts by their reliability and differentiate experts based on their reliability.

featured: true
tags:
  - Reinforcement Learning
  - Human-Computer Interaction



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

