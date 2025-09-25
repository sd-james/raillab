---
title:  "Real-time Prediction of Dota 2 Match Outcomes using In-game Chat Logs"
authors:
  - Tshepiso Bapela
  - Pravesh Ranchod
  - Branden Ingram

author_notes: []

publication: "In *AAAI Conference on Artificial Intelligence and Interactive Digital Entertainment*"

date: 2025-10-12T00:00:00Z
publishDate: 2023-10-08T00:00:00Z

# conf = 1, journal = 2, preprint = 3, report = 4, book = 5, book chapter = 6, thesis = 7, patent = 9
# workshop = 9, symposium = 10, extended abstract =11
publication_types:
- "1"

abstract: "This paper investigates the application of supervised learning for the purpose of match outcome prediction 
  from Dota 2 in game chat logs. We analyze a dataset of 50,000 ranked matches, evaluating the predictive power of
  communication data alone and in combination with game events. Using LSTM and DistilBERT architectures, alongside 
   a logistic regression baseline, we demonstrate that chat logs alone enable accurate prediction (up to 81.4% accuracy),
  while incorporating game events substantially improves performance (up to 98.4% accuracy). Our temporal analysis reveals
  that prediction reliability increases significantly during the midgame phase (15-30 minutes), with models exhibiting 
  different strengths - LSTM achieves higher accuracy while Distil- BERT demonstrates greater prediction confidence. 
  This study contributes to esports analytics by establishing chat logs as a viable predictive data source."



featured: true
tags:
  - Games
  - Predictive Modelling
image:
focal_point: ''
preview_only: false

slides: null

projects:
  - ai-in-games

---
