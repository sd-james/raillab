---
title:  "Accelerating Model Learning with Inter-robot Knowledge Transfer"
authors:
  - Ndivhuwo Makondo
  - Benjamin Rosman
  - Osamu Hasegawa

author_notes: []

publication: "*IEEE International Conference on Robotics and Automation*"

date: 2018-05-21T00:00:00Z
publishDate: 2022-10-05T00:00:00Z

# conf = 1, journal = 2, preprint = 3, report = 4, book = 5, book chapter = 6, thesis = 7, patent = 9
# workshop = 9, symposium = 10, extended abstract =11
publication_types:
  - "1"

abstract: "Online learning of a robot’s inverse dynamics
  model for trajectory tracking necessitates an interaction between
  the robot and its environment to collect training data.
  This is challenging for physical robots in the real world,
  especially for humanoids and manipulators due to their large
  and high dimensional state and action spaces, as a large amount
  of data must be collected over time. This can put the robot
  in danger when learning tabula rasa and can also be a time-intensive
  process especially in a multi-robot setting, where
  each robot is learning its model from scratch. We propose
  accelerating learning of the inverse dynamics model for trajectory
  tracking tasks in this multi-robot setting using knowledge
  transfer, where robots share and re-use data collected by pre-existing
  robots, in order to speed up learning for new robots.
  We propose a scheme for collecting a sample of correspondences
  from the robots for training transfer models, and demonstrate,
  in simulations, the benefit of knowledge transfer in accelerating
  online learning of the inverse dynamics model between several
  robots, including between a low-cost Interbotix PhantomX
  Pincher arm, and a more expensive and relatively heavier Kuka
  youBot arm. We show that knowledge transfer can save up to
  63% of training time of the youBot arm compared to learning
  from scratch, and about 58% for the lighter Pincher arm."

featured: true
tags:
  - Robotics
  - Transfer Learning
  - Robot Kinematics


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
