---
title:  "Combining Primitive DQNs for Improved Reinforcement Learning in Minecraft"
authors:
  - Matthew Reynard
  - Herman Kamper
  - Herman A Engelbrecht
  - Benjamin Rosman

author_notes: []

publication: "*International SAUPEC/RobMech/PRASA Conference*"

date: 2020-01-29T00:00:00Z
publishDate: 2022-10-05T00:00:00Z

# conf = 1, journal = 2, preprint = 3, report = 4, book = 5, book chapter = 6, thesis = 7, patent = 9
# workshop = 9, symposium = 10, extended abstract =11
publication_types:
- "1"

abstract: "We ask whether a reinforcement learning agent
  learns better by first learning the skills to perform smaller tasks
  in a complex environment or by learning the skills in the complex
  environment from the start. This is investigated empirically in a
  non-trivial game environment. We use the premise of curriculum
  learning where an agent learns different skills in independent
  and isolated environments referred to as dojos in this paper. The
  skills learned in the dojos are then used as different actions as
  the agent decides which skill to perform that best applies to the
  current game state. We evaluate this with experiments conducted
  in the Minecraft gaming environment. We find that dojo learning
  is able to achieve better performance with faster training time
  in certain environments. The main benefit of this approach is
  that the reward functions can be finely tuned in the dojos for
  each action as compared to the traditional methods. However, the
  skills learned in the individual dojos become the limiting factor
  in performance as the agent is unable to combine these skills
  effectively when put in certain complex environments. This can
  be mitigated if the dojo modules are further trained to result in
  similar results as the standard method."

featured: true
tags:
  - Reinforcement Learning
  - Curriculum Learning

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

