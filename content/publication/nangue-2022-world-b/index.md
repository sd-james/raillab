---
title:  "World Value Functions: Knowledge Representation for Learning and Planning"
authors:
  - Geraud Nangue Tasse
  - Benjamin Rosman
  - Steven James

author_notes: []

publication: "*Bridging the Gap Between AI Planning and Reinforcement Learning Workshop at ICAPS*"

date: 2022-06-13T00:00:00Z
publishDate: 2022-10-05T00:00:00Z

# conf = 1, journal = 2, preprint = 3, report = 4, book = 5, book chapter = 6, thesis = 7, patent = 9
# workshop = 9, symposium = 10, extended abstract =11
publication_types:
- "9"

abstract: We propose world value functions (WVFs), a type of goaloriented general value function that represents 
  how to solve not just a given task, but any other goal-reaching task in an agent's environment. This is achieved by 
  equipping an agent with an internal goal space defined as all the world states where it experiences a terminal transition. 
  The agent can then modify the standard task rewards to define its own reward function, which provably drives it to learn how 
  to achieve all reachable internal goals, and the value of doing so in the current task. We demonstrate two key benefits of WVFs 
  in the context of learning and planning. In particular, given a learned WVF, an agent can compute the optimal policy in 
  a new task by simply estimating the task's reward function. Furthermore, we show that WVFs also implicitly encode the 
  transition dynamics of the environment, and so can be used to perform planning. Experimental results show that WVFs can be
  learned faster than regular value functions, while their ability to infer the environment's dynamics can be used to
  integrate learning and planning methods to further improve sample efficiency.

featured: true
tags:
  - Reinforcement Learning
  - Planning
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
