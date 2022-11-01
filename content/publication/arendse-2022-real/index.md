---
abstract: In interactive digital media, such as video games, bringing about an adaptive or personalised
  experience requires a mechanism for correctly classifying or identifying the player style, before
  attempting to modify the experience in some way that improves player interest and immersion. 
  This work presents a framework for solving this problem of in-game real time playstyle classification. 
  We propose a hybrid probabilistic supervised learning approach, using Bayesian Inference informed by a
  K-Nearest Neighbors based likelihood, that is able to classify players in real time at every step within
  a given game level using only the latest player action or state observation. This improves on current 
  approaches dependent on previous episodic player action trajectories in order to classify the player. 
  Furthermore, we highlight the effect that this representation of the player state-action observation has
  on the in-game playstyle classification’s accuracy, prediction stability, and generalisability. We apply and
  test our framework using MiniDungeons, a rogue-like dungeon exploration game, and further evaluate our 
  framework using a natural dataset containing human player action data from the platforming game Super 
  Mario Bros. The experimental results obtained from our approach outperforms existing work in both domains.
  Furthermore, the evaluation results highlights the ability of our framework to generalise to unseen levels,
  without the need for additional retraining. Additionally, the Super Mario evaluation results illustrates 
  the scalability of our framework to a more complex game environment with human player data.
slides: null
publication_types:
  - "1"
authors:
  - Lindsay John Arendse
  - Branden Ingram
  - Benjamin Rosman
author_notes: []
publication: "In *Proceedings of the Third Southern African Conference for AI Research. Part of the book series: Communications in Computer and Information Science, Springer*"
#url_dataset: "#"
#url_project: ""
#publication_short: ""
#url_source: "#"
#url_video: "#"
title: Real Time In-Game Playstyle Classification Using A Hybrid Probabilistic Supervised Learning Approach
featured: true
tags:
  - Player Modelling
  - Games
date: 2022-12-05T00:00:00Z
publishDate: 2022-10-05T00:00:00Z
#url_slides: ""
projects:
  - ai-in-games

image:
  focal_point: ''
  preview_only: false
doi: ""
#url_poster: "#"
#url_code: "#"

---

