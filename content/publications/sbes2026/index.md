---
title: "The Impact of Static Analysis Depth Limit on Semantic Conflict Detection"
authors:
  - Pedro Patriota
  - admin
  - Paulo Borba
date: "2026-09-09T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2026-09-09T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "XL Simpósio Brasileiro de Engenharia de Software (SBES 2026), Research Track"
publication_short: "SBES 2026"

abstract: "Collaborative software development requires periodic code integration of independent contributions into a shared codebase, a process that may introduce dynamic semantic conflicts (behavioral interference between changes not captured by textual merge tools). Static-analysis-based approaches for detecting such conflicts rely on configuration parameters that affect both detectability accuracy and computational cost. A key parameter is the method traversal depth limit, which determines how deeply chains of method calls are followed when tracking interference. In this paper, we analyze how varying the depth limit affects both the number of reported interferences and the execution performance of the Overriding Assignment (OA) analysis for interference detection. We evaluate it on two datasets from previous studies: the MergeDataset, a manually curated benchmark, and the RefDataset, a broader and more diverse dataset covering a wider range of project sizes and merge patterns. Both datasets comprise Java open-source projects from GitHub, and our findings are consistent across them. We execute the analyses limiting the depth to 5, 10, and 20 method calls. Our results show that increasing the depth limit does not consistently improve detection: the relationship is non-monotonic. The gain is most notable when moving from depth 5 to 10, where the number of newly reported scenarios increases. Beyond depth 10, however, the number of detected scenarios and total interferences both decrease considerably. These gains come at a measurable cost: average analysis time and memory consumption increase noticeably at greater depths, with diminishing returns. Nevertheless, accuracy and precision tend to improve from depth 5 to 10, but degrade when moving further to depth 20."

tags:
  - merge tools
  - semantic conflict
  - static analysis
  - depth tuning
  - pointer analysis

featured: true

links:
  - type: pdf
    url: "https://cbsoft.sbc.org.br/2026/data/papers/sbes/The%20Impact%20of%20Static%20Analysis%20Depth%20Limit%20on%20Semantic%20Conflict%20Detection.pdf"
  - type: dataset
    url: https://doi.org/10.17605/OSF.IO/BAXRP
  - type: custom
    label: Conference Page
    url: https://cbsoft.sbc.org.br/2026/pt/symposiums/sbes/pesquisa/papers/

projects:
  - semantic-merge-tool

slides: ""
---

Artifact badges: **Available** and **Functional** (SBES 2026 Artifact Evaluation).
