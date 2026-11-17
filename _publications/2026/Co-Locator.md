---
title:          "Ask KG Agent: A Multi-Agent Framework for Code Localization Using Code and Knowledge Graphs"
date:           2026-12-08 00:00:00 +0900
selected:       true
pub:            "Annual Conference on Neural Information Processing Systems (NeurIPS)"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2026"

abstract: >-
  Mapping software issue descriptions to relevant code segments, a task known as code localization, is a primary bottleneck in automated software engineering. While recent attempts have automated it using code graphs that capture syntax-level dependencies among code elements, including functions and modules, their code-centric approaches often overlook the design rationales and prior fix patterns present in a codebase's development history, such as pull requests and commits. We propose Co-Locator, a collaborative multi-agent code localization framework that integrates code graphs reflecting functional dependencies and knowledge graphs constructed from triplets capturing design rationales and past code modifications scattered across the development history. During localization, a Code Graph (CG) agent explores functional hierarchies and consults a Knowledge Graph (KG) agent to gather insights into developer intents and prior bug fixes. Combined with a Retriever agent that assists CG and KG agents, Co-Locator leverages a holistic view of the code's functional and historical context, considering what the code implements and how it was changed, to identify locations to fix. Experiments show that Co-Locator significantly outperforms 12 state-of-the-art baseline methods.
cover:          /assets/images/covers/colocator.png
authors:
  - Chanyoung Chung
  - Jeemin Kim
  - Joyce Jiyoung Whang
links:
  Paper: https://neurips.cc/virtual/2026/loc/sydney/poster/155386
  Code: https://github.com/bdi-lab/Co-Locator
---
