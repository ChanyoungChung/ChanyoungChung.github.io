---
title:          "Knowledge Graph Embedding via Metagraph Learning"
date:           2021-07-01 00:00:00 +0900
selected:       false
pub:            "International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR)"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2021"

abstract: >-
  Knowledge graph embedding aims to represent entities and relations in a continuous feature space while preserving the structure of a knowledge graph. Most existing knowledge graph embedding methods either focus only on a flat structure of the given knowledge graph or exploit the predefined types of entities to explore an enriched structure. In this paper, we define the metagraph of a knowledge graph by proposing a new affinity metric that measures the structural similarity between entities, and then grouping close entities by hypergraph clustering. Without any prior information about entity types, a set of semantically close entities is successfully merged into one super-entity in our metagraph representation. We propose the metagraph-based pre-training model of knowledge graph embedding where we first learn representations in the metagraph and initialize the entities and relations in the original knowledge graph with the learned representations. Experimental results show that our method is effective in improving the accuracy of state-of-the-art knowledge graph embedding methods.
cover:          /assets/images/covers/metakg.png
authors:
  - Chanyoung Chung
  - Joyce Jiyoung Whang
links:
  Paper: https://dl.acm.org/doi/abs/10.1145/3404835.3463072
  Code: https://github.com/bdi-lab/meta_kge
---
