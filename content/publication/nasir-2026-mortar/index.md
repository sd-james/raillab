---
title:  "Mortar: Evolving Mechanics for Automatic Game Design"
authors:
  - Muhammad Nasir
  - Yuchen Li
  - Steven James
  - Julian Togelius
  
author_notes: []

publication: In *Proceedings of the Genetic and Evolutionary Computation Conference*

date: 2026-07-13T00:00:00Z
publishDate: 2022-10-05T00:00:00Z

# conf = 1, journal = 2, preprint = 3, report = 4, book = 5, book chapter = 6, thesis = 7, patent = 9
# workshop = 9, symposium = 10, extended abstract =11
publication_types:
  - "1"

abstract: "We present Mortar, a system for autonomously evolving game mechanics for automatic game design. 
  Game mechanics define the rules and interactions that govern gameplay, and designing them manually is a time-consuming 
  and expert-driven process. Mortar combines a quality-diversity algorithm with a large language model to explore a
   diverse set of mechanics, which are evaluated by synthesising complete games that incorporate both evolved mechanics 
   and those drawn from an archive. The mechanics are evaluated by composing complete games through a tree search procedure,
    where the resulting games are evaluated by their ability to preserve a skill-based ordering over players - that is,
     whether stronger players consistently outperform weaker ones. We assess the mechanics based on their contribution 
     towards the skill-based ordering score in the game. We demonstrate that Mortar produces games that appear diverse 
     and playable, and mechanics that contribute more towards the skill-based ordering score in the game. We 
     perform ablation studies to assess the role of each system component and a user study to evaluate the 
     games based on human feedback."

featured: true
tags:
  - Evolutionary Strategies
  - Large Language Models
  - Game Design
  - Procedural Content Generation
  - Games

projects:
  - ai-in-games


image:
  focal_point: ''
  preview_only: false

#url_dataset: "#"
#url_project: ""
#publication_short: ""
#url_source: "#"
#url_slides: ""
#url_poster: "#"
#url_code: "#"
# doi: ""

---

