---
title:  "Action Priors for Learning Domain Invariances"
authors:
  - Benjamin Rosman
  - Subramanian Ramamoorthy

author_notes: []

publication: "*IEEE Transactions on Autonomous Mental Development*"

date: 2015-06-02T00:00:00Z
publishDate: 2022-10-05T00:00:00Z

# conf = 1, journal = 2, preprint = 3, report = 4, book = 5, book chapter = 6, thesis = 7, patent = 9
# workshop = 9, symposium = 10, extended abstract =11
publication_types:
  - "2"

abstract: "An agent tasked with solving a number of different
  decision making problems in similar environments has an opportunity
  to learn over a longer timescale than each individual
  task. Through examining solutions to different tasks, it can
  uncover behavioural invariances in the domain, by identifying
  actions to be prioritised in local contexts, invariant to task
  details. This information has the effect of greatly increasing
  the speed of solving new problems. We formalise this notion
  as action priors, defined as distributions over the action space,
  conditioned on environment state, and show how these can be
  learnt from a set of value functions. We apply action priors in
  the setting of reinforcement learning, to bias action selection
  during exploration. Aggressive use of action priors performs
  context based pruning of the available actions, thus reducing
  the complexity of lookahead during search. We additionally
  define action priors over observation features, rather than states,
  which provides further flexibility and generalisability, with the
  additional benefit of enabling feature selection. Action priors are
  demonstrated in experiments in a simulated factory environment
  and a large random graph domain, and show significant speed
  ups in learning new tasks. Furthermore, we argue that this
  mechanism is cognitively plausible, and is compatible with
  findings from cognitive psychology."

featured: true
tags:
  - Reinforcement Learning
  - Transfer Learning
  - Action Priors


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



---
