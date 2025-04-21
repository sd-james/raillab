---
title:  "Composition and Zero-Shot Transfer with Lattice Structures in Reinforcement Learning"
authors:
  - Geraud Nangue Tasse
  - Steven James
  - Benjamin Rosman

author_notes: []

publication: "*Journal of Artificial Intelligence Research*"

date: 2025-04-17T00:00:00Z
publishDate: 2022-10-05T00:00:00Z

# conf = 1, journal = 2, preprint = 3, report = 4, book = 5, book chapter = 6, thesis = 7, patent = 9
# workshop = 9, symposium = 10, extended abstract =11
publication_types:
- "2"

abstract: "An important property of long-lived agents is the ability to reuse existing knowledge to solve new tasks.
 An appealing approach towards obtaining such agents is by leveraging logical composition over tasks, where new tasks are
 defined by applying logic operators to previously-solved ones. This composition is particularly powerful since it provides
 a human-understandable mechanism for task specification. However, no unifying formalism for applying logic operators 
 to tasks and generalising combinatorially over them has yet been developed. We address the problem by formally defining 
 logical composition as operators acting on a set of tasks in a lattice structure—the algebraic structure that generalises 
 the study of Boolean logic. This provides a theoretically rigorous method for composing tasks, allowing us to formulate 
 new tasks in terms of the negation, disjunction, and conjunction of a set of base tasks. We prove that by learning a new 
 type of goal-oriented value function model free, called the world value function, an agent can solve composite tasks 
 involving arbitrary logical operators with no further learning. We verify our approach in high-dimensional 
 domains---including a video game environment and continuous-control task---where an agent first learns to solve a set of base 
 tasks, and then composes these solutions to solve a super-exponential number of new tasks."

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
doi: "https://doi.org/10.1613/jair.1.16817"
---


