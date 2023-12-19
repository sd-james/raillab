---
title:  "Counting Reward Automata: Sample Efficient Reinforcement Learning Through the Exploitation of Reward Function Structure"
authors:
  - Tristan Bester
  - Benjamin Rosman
  - Steven James
  - Geraud Nangue Tasse


author_notes: []

publication: "*Workshop on Neuro-Symbolic Learning and Reasoning in the Era of Large Language Models at AAAI*"

date: 2024-02-26T00:00:00Z
publishDate: 2022-10-05T00:00:00Z

# conf = 1, journal = 2, preprint = 3, report = 4, book = 5, book chapter = 6, thesis = 7, patent = 8
# workshop = 9, symposium = 10, extended abstract =11
publication_types:
- "9"

abstract: We present counting reward automata---a finite state machine variant capable of modelling any reward function 
  expressible as a formal language. Unlike previous approaches, which are limited to the expression of tasks as regular 
  languages, our framework allows for tasks described by unrestricted grammars. We prove that an agent equipped with 
  such an abstract machine is able to solve a larger set of tasks than those utilising current approaches. We show that
  this increase in expressive power does not come at the cost of increased automaton complexity. A selection of learning
  algorithms are presented which exploit automaton structure to improve sample efficiency. We show that the state machines 
  required in our formulation can be specified from natural language task descriptions using large language models.
  Empirical results demonstrate that our method outperforms competing approaches in terms of sample efficiency, automaton
  complexity, and task completion.

projects:
  - composition


featured: true
tags:
  - Reinforcement Learning
  - Hierarchical Reinforcement Learning
  - Language

image:
focal_point: ''
preview_only: false

slides: null
---
