---
title:          "InGram: Inductive Knowledge Graph Embedding via Relation Graphs"
date:           2023-07-01 00:00:00 +0900
selected:       false
pub:            "International Conference on Machine Learning (ICML)"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2023"

abstract: >-
  Inductive knowledge graph completion has been considered as the task of predicting missing triplets between new entities that are not observed during training. While most inductive knowledge graph completion methods assume that all entities can be new, they do not allow new relations to appear at inference time. This restriction prohibits the existing methods from appropriately handling real-world knowledge graphs where new entities accompany new relations. In this paper, we propose an INductive knowledge GRAph eMbedding method, InGram, that can generate embeddings of new relations as well as new entities at inference time. Given a knowledge graph, we define a relation graph as a weighted graph consisting of relations and the affinity weights between them. Based on the relation graph and the original knowledge graph, InGram learns how to aggregate neighboring embeddings to generate relation and entity embeddings using an attention mechanism. Experimental results show that InGram outperforms 14 different state-of-the-art methods on varied inductive learning scenarios.
cover:          /assets/images/covers/cover3.jpg
authors:
  - Jaejun Lee
  - Chanyoung Chung
  - Joyce Jiyoung Whang
links:
  Paper: https://proceedings.mlr.press/v202/lee23c.html
  Code: https://github.com/bdi-lab/InGram
---
