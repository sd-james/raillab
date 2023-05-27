---
title:  "Confident in the Crowd: Bayesian Inference to Improve Data Labelling in Crowdsourcing"
authors:
  - Pierce Burke
  - Richard Klein

author_notes: []

publication: "*International SAUPEC/RobMech/PRASA Conference*"

date: 2020-01-29T00:00:00Z
publishDate: 2022-10-05T00:00:00Z

# conf = 1, journal = 2, preprint = 3, report = 4, book = 5, book chapter = 6, thesis = 7, patent = 9
# workshop = 9, symposium = 10, extended abstract =11
publication_types:
- "1"

abstract: "With the increased interest in machine learning and big data problems, the need for large amounts of labelled 
  data has also grown. However, it is often infeasible to get experts to label all of this data, which leads many practitioners to
  crowdsourcing solutions. In this paper, we present new techniques to improve the quality of the labels while attempting to reduce 
  the cost. The naive approach to assigning labels is to adopt a majority vote method, however, in the context of data labelling,
  this is not always ideal as data labellers are not equally reliable. One might, instead, give higher priority to certain 
  labellers through some kind of weighted vote based on past performance. This paper investigates the use of more sophisticated methods,
  such as Bayesian inference, to measure the performance of the labellers as well as the confidence of each label. The methods
  we propose follow an iterative improvement algorithm which attempts to use the least amount of workers necessary to
  achieve the desired confidence in the inferred label. This paper explores simulated binary classification problems with
  simulated workers and questions to test the proposed methods. Our methods outperform the standard voting methods in both
  cost and accuracy while maintaining higher reliability when there is disagreement within the crowd."

featured: true
tags:
  - Crowdsourcing
  - Inter-rater Agreement
  - Bayesian Inference

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
