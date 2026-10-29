---
title: "A Quantitative Characterization of Semantic Conflicts in Open-Source Java Projects"
authors:
  - admin
  - Vinicius Resende
  - Ykaro dos Santos Silva
  - Paulo Borba
  - Rodrigo Bonifácio
  - Pedro Patriota
  - Maria Clara Araújo
date: "2026-09-15T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2026-09-15T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "26th IEEE International Conference on Source Code Analysis and Manipulation (SCAM 2026), Research Track"
publication_short: "SCAM 2026"

abstract: "Collaborative software development relies on automated merge tools, but parallel contributions can introduce dynamic semantic conflicts that alter program behavior without triggering textual merge conflicts. Different techniques can be used to detect these conflicts, including testing, dynamic analysis, and static analysis, which classifies them into three primary categories: Direct Flow (DF), Confluence Flow (CF), and Override Assignment (OA). However, the prevalence, structural characteristics, and distribution of these semantic conflicts remain largely unexplored at scale. To address this gap, we establish a comprehensive catalog of topological structures that define the structural characteristics of semantic conflicts. We conduct an empirical study to quantify the occurrence of these structures in practice, using interprocedural static analysis on a large benchmark comprising 907 real-world Java merge scenarios from open-source GitHub repositories. Our results reveal a structural dichotomy: while CF conflicts concentrate overwhelmingly in fully local topologies (90.4% start and end in the same file), DF and OA conflicts exhibit highly divergent behavior, with multi-file topologies accounting for 60.3% and 46.7% of their respective instances. These findings provide actionable guidance for configuring static analysis tools, demonstrating that fast intraprocedural analysis is sufficient to detect the vast majority of CF conflicts, whereas deeper interprocedural analysis is essential to uncover DF and OA conflicts."

tags:
  - merge tools
  - semantic conflict
  - static analysis
  - empirical study

featured: true

links:
  - type: custom
    label: Talk & Photos
    url: events/scam26/
  - type: custom
    label: Conference Page
    url: https://conf.researchr.org/details/scam-2026/scam-2026-research-track/6/A-Quantitative-Characterization-of-Semantic-Conflicts-in-Open-Source-Java-Projects

projects:
  - semantic-merge-tool

slides: ""
---
