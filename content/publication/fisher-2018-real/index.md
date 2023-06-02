---
title:  "Real-time Motion Planning in Changing Environments Using Topology-based Encoding of Past Knowledge"
authors:
  - Richard Fisher
  - Benjamin Rosman
  - Vladimir Ivan

author_notes: []

publication: "*IEEE/RSJ International Conference on Intelligent Robots and Systems*"

date: 2018-10-01T00:00:00Z
publishDate: 2022-10-05T00:00:00Z

# conf = 1, journal = 2, preprint = 3, report = 4, book = 5, book chapter = 6, thesis = 7, patent = 9
# workshop = 9, symposium = 10, extended abstract =11
publication_types:
  - "1"

abstract: "Trajectory planning and replanning in complex
  environments often reuses very little information from the previous
  solutions. This is particularly evident when the motion is
  repeated multiple times with only a limited amount of variation
  between each run. To address this issue, we propose the DRM-connect
  algorithm, a combination of dynamic reachability maps
  (DRM) with lazy collision checking and a fallback strategy
  based on the RRT-connect algorithm which is used to repair
  the roadmap through further exploration. This fallback allows
  us to use much sparser roadmaps. Furthermore, we investigate
  using an approximate Reeb graph to capture the topology-persistent
  features of the past solutions of the problem utilising
  this sparsity. We evaluate DRM-connect with a Reeb graph on
  reaching tasks, and we compare it to state-of-the-art methods.
  We show that the proposed method outperforms both RRT-connect
  and BKPIECE algorithms in the number of collision
  checks required and we show that our method has the potential
  to scale to systems with higher number degrees of freedom."

featured: true
tags:
  - Robotics
  - Motion Planning


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

