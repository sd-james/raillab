---
title:  "LLMatic: Neural Architecture Search via Large Language Models
and Quality Diversity Optimization"
authors:
  - Muhammad Nasir
  - Sam Earle
  - Christopher Cleghorn
  - Steven James
  - Julian Togelius
  
author_notes: []

publication: In *Proceedings of the Genetic and Evolutionary Computation Conference*

date: 2024-07-14T00:00:00Z
publishDate: 2022-10-05T00:00:00Z

# conf = 1, journal = 2, preprint = 3, report = 4, book = 5, book chapter = 6, thesis = 7, patent = 9
# workshop = 9, symposium = 10, extended abstract =11
publication_types:
  - "1"

abstract: "Large language models (LLMs) have emerged as powerful tools capable of accomplishing a broad spectrum of tasks. 
  Their abilities span numerous areas, and one area where they have made a significant impact is in the domain of code 
  generation. Here, we propose to use the coding abilities of LLMs to introduce meaningful variations to code defining
  neural networks. Meanwhile, Quality-Diversity (QD) algorithms are known to discover diverse and robust solutions. 
  By merging the code-generating abilities of LLMs with the diversity and robustness of QD solutions, we introduce LLMatic,
  a Neural Architecture Search (NAS) algorithm. While LLMs struggle to conduct NAS directly through prompts, LLMatic uses a
  procedural approach, leveraging QD for prompts and network architecture to create diverse and high-performing networks. We 
  test LLMatic on the CIFAR-10 and NAS-bench-201 benchmark, demonstrating that it can produce competitive networks while evaluating
  just 2,000 candidates, even without prior knowledge of the benchmark domain or exposure to any previous top-performing models 
  for the benchmark. The open-sourced code is available at https://github.com/umair-nasir14/LLMatic."

featured: true
tags:
  - Neural Architecture Search
  - Large Language Models
  - Evolutionary Strategies
  - Neuroevolution

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

url_code: "https://github.com/umair-nasir14/LLMatic"

---

