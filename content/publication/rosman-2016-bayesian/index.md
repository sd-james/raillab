---
title:  "Bayesian Policy Reuse"
authors:
  - Benjamin Rosman
  - Majd Hawasly
  - Subramanian Ramamoorthy
  
author_notes: []

publication: "*Machine Learning Journal*"

date: 2016-02-22T00:00:00Z
publishDate: 2022-10-05T00:00:00Z

# conf = 1, journal = 2, preprint = 3, report = 4, book = 5, book chapter = 6, thesis = 7, patent = 9
# workshop = 9, symposium = 10, extended abstract =11
publication_types:
  - "2"

abstract: "A long-lived autonomous agent should be able to respond online to novel instances of tasks from a familiar 
  domain. Acting online requires 'fast' responses, in terms of rapid convergence, especially when the task instance has a
  short duration, such as in applications involving interactions with humans. These requirements can be problematic for 
  many established methods for learning to act. In domains where the agent knows that the task instance is drawn from a family
  of related tasks, albeit without access to the label of any given instance, it can choose to act through a process of
  policy reuse from a library, rather than policy learning from scratch. In policy reuse, the agent has prior knowledge of 
  the class of tasks in the form of a library of policies that were learnt from sample task instances during an offline 
  training phase. We formalise the problem of policy reuse, and present an algorithm for efficiently responding to a novel
  task instance by reusing a policy from the library of existing policies, where the choice is based on observed 'signals'
  which correlate to policy performance. We achieve this by posing the problem as a Bayesian choice problem with a corresponding 
  notion of an optimal response, but the computation of that response is in many cases intractable. Therefore, to reduce the
  computation cost of the posterior, we follow a Bayesian optimisation approach and define a set of policy selection functions,
  which balance exploration in the policy library against exploitation of previously tried policies, together with a model 
  of expected performance of the policy library on their corresponding task instances. We validate our method in several simulated
  domains of interactive, short-duration episodic tasks, showing rapid convergence in unknown task variations."

featured: true
tags:
  - Reinforcement Learning
  - Transfer Learning

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


