---
title:          "FIETA: Few-Shot Inductive Knowledge Graph Completion via Task-Aware Graph Neural Networks"
date:           2026-11-09 00:00:00 +0900
selected:       true
pub:            "ACM Conference on Information and Knowledge Management (CIKM)"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2026"

abstract: >-
  Few-shot knowledge graph completion aims to predict missing triplets involving few-shot relations, where each few-shot relation is associated with only a few examples of the relation, called support triplets. In few-shot knowledge graph completion, each few-shot task corresponds to predicting triplets for a few-shot relation. Most existing few-shot knowledge graph completion methods assume all entities and relations in knowledge graphs to be observed during training, making it challenging to deal with new entities and relations appearing at inference time. In this paper, we propose FIETA, a Few-shot InductivE knowledge graph completion method that introduces Task-Aware graph neural networks to handle few-shot tasks in knowledge graphs containing entities and relations unseen during training. Based on the local structures of support triplets, FIETA conducts task-centric modeling of relations to obtain relation representations reflecting relative positions to the few-shot relation, and performs task-guided message passing to compute entity representations optimized for each task by prioritizing triplets that are crucial in prediction. By learning to compute task-aware representations with structures, FIETA effectively handles few-shot relations on knowledge graphs with new entities and relations appearing at inference time. Experimental results show that FIETA outperforms 19 state-of-the-art baselines in various inductive scenarios.
cover:          /assets/images/covers/fieta.png
authors:
  - Chanyoung Chung
  - Minsung Hwang
  - Joyce Jiyoung Whang
links:
  Paper: https://dl.acm.org/doi/10.1145/3799682.3840780
  Code: https://github.com/bdi-lab/FIETA
---
