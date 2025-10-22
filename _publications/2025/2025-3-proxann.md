---
title:          "ProxAnn: Use-Oriented Evaluations of Topic Models and Document Clustering"
date:           2025-07-1 00:01:00 +0800
selected:       true
pub:            "ACL"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Oral</span>'
pub_date:       "2025"

abstract: >-
  Topic model and document-clustering evaluations either use automated metrics that align poorly with human preferences or require expert labels that are intractable to scale. We design a scalable human evaluation protocol and a corresponding automated approximation that reflect practitioners' real-world usage of models. Annotators -- or an LLM-based proxy -- review text items assigned to a topic or cluster, infer a category for the group, then apply that category to other documents. Using this protocol, we collect extensive crowdworker annotations of outputs from a diverse set of topic models on two datasets. We then use these annotations to validate automated proxies, finding that the best LLM proxies are statistically indistinguishable from a human annotator and can therefore serve as a reasonable substitute in automated evaluations. Package, web interface, and data are at https://github.com/ahoho/proxann

cover:          /assets/images/covers/proxann.png

authors:
  - Alexander Hoyle
  - Lorena Calvo-Bartolomé
  - Jordan Boyd-Graber
  - Philip Resnik

links:
  Paper: https://aclanthology.org/2025.acl-long.772/
  Code: https://github.com/ahoho/proxann
---