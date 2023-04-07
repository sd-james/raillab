---
title:  "World Value Functions: Knowledge Representation for Multitask Reinforcement Learning"
authors:
  - Geraud Nangue Tasse
  - Benjamin Rosman
  - Steven James


author_notes: []

publication: "*The 5th Multi-disciplinary Conference on Reinforcement Learning and Decision Making*"

date: 2022-06-08T00:00:00Z
publishDate: 2022-10-05T00:00:00Z

# conf = 1, journal = 2, preprint = 3, report = 4, book = 5, book chapter = 6, thesis = 7, patent = 9
# workshop = 9, symposium = 10, extended abstract =11
publication_types:
  - "11"

abstract: An open problem in artificial intelligence is how to learn and represent knowledge that is sufficient for a 
  general agent that needs to solve multiple tasks in a given world. In this work we propose world value functions (WVFs), 
  which are a type of general value function with mastery of the world --- they represent not only how to solve a given task, 
  but also how to solve any other goal-reaching task. To achieve this, we equip the agent with an internal goal 
  space defined as all the world states where it experiences a terminal transition --- a task outcome. The agent can then 
  modify task rewards to define its own reward function, which provably drives it to learn how to achieve all achievable internal goals, 
  and the value of doing so in the current task. We demonstrate a number of benefits of WVFs. When the agent's internal goal space is
  the entire state space, we demonstrate that the transition function can be inferred from the learned WVF, which allows the 
  agent to plan using learned value functions. Additionally, we show that for tasks in the same world, a pretrained agent 
  that has learned any WVF can then infer the policy and value function for any new task directly from its rewards. Finally, an
  important property for long-lived agents is the ability to reuse existing knowledge to solve new tasks. Using WVFs as the
  knowledge representation for learned tasks, we show that an agent is able to solve their logical combination zero-shot, resulting in a 
  combinatorially increasing number of skills throughout their lifetime.

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

