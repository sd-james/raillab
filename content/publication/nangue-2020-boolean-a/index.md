---
title:  "A Boolean Task Algebra for Reinforcement Learning"
authors:
  - Geraud Nangue Tasse
  - Steven James
  - Benjamin Rosman

author_notes: []

publication: "In *Advances in Neural Information Processing Systems*"

date: 2020-12-06T00:00:00Z
publishDate: 2022-10-05T00:00:00Z

# conf = 1, journal = 2, preprint = 3, report = 4, book = 5, book chapter = 6, thesis = 7, patent = 9
# workshop = 9, symposium = 10, extended abstract =11
publication_types:
- "1"

abstract: "The ability to compose learned skills to solve new tasks is an important property for lifelong-learning agents.
  In this work we formalise the logical composition of tasks as a Boolean algebra. This allows us to formulate new tasks in
  terms of the negation, disjunction and conjunction of a set of base tasks. We then show that by learning goal-oriented 
  value functions and restricting the transition dynamics of the tasks, an agent can solve these new tasks with no further 
  learning. We prove that by composing these value functions in specific ways, we immediately recover the optimal policies
  for all tasks expressible under the Boolean algebra. We verify our approach in two domains---including a high-dimensional
  video game environment requiring function approximation---where an agent first learns a set of base skills, and then
  composes them to solve a super-exponential number of new tasks."

featured: true
tags:
  - Reinforcement Learning
  - Transfer Learning

projects:
  - composition

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
