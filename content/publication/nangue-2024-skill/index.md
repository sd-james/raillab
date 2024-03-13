---
title:  "Skill Machines: Temporal Logic Skill Composition in Reinforcement Learning"
authors:
  - Geraud Nangue Tasse
  - Devon Jarvis  
  - Steven James
  - Benjamin Rosman


author_notes: []

publication: "In *Proceedings of the Twelfth International Conference on Learning Representations*"

date: 2024-05-07T00:00:00Z
publishDate: 2022-06-13T00:00:00Z

# conf = 1, journal = 2, preprint = 3, report = 4, book = 5, book chapter = 6, thesis = 7, patent = 9
# workshop = 9, symposium = 10, extended abstract =11
publication_types:
- "1"

abstract: It is desirable for an agent to be able to solve a rich variety of problems that can be specified through language
  in the same environment. A popular approach towards obtaining such agents is to reuse skills learned in prior tasks to 
  generalise compositionally to new ones. However, this is a challenging problem due to the curse of dimensionality induced
  by the combinatorially large number of ways high-level goals can be combined both logically and temporally in language.
  To address this problem, we propose a framework where an agent first learns a sufficient set of skill primitives to achieve
  all high-level goals in its environment. The agent can then flexibly compose them both logically and temporally to provably
  achieve temporal logic specifications in any regular language, such as regular fragments of linear temporal logic. This provides
  the agent with the ability to map from complex temporal logic task specifications to near-optimal behaviours zero-shot. 
  We demonstrate this experimentally in a tabular setting, as well as in a high-dimensional video game and continuous control environment.
  Finally, we also demonstrate that the performance of skill machines can be improved with regular off-policy reinforcement learning algorithms
  when optimal behaviours are desired.
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
