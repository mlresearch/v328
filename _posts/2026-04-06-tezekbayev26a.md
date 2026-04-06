---
title: Simplex Deep Linear Discriminant Analysis
openreview: 9CC0pqPq13
abstract: 'We revisit Deep Linear Discriminant Analysis (Deep LDA) from a likelihood-based
  perspective. While classical LDA is a simple Gaussian model with linear decision
  boundaries, attaching an LDA head to a neural encoder raises the question of how
  to train the resulting deep classifier by maximum likelihood estimation (MLE). We
  first show that end-to-end MLE training of an unconstrained Deep LDA model ignores
  discrimination: when both the LDA parameters and the encoder parameters are learned
  jointly, the likelihood admits a degenerate solution in which some of the class
  clusters may heavily overlap or even collapse, and classification performance deteriorates.
  Batchwise moment re-estimation of the LDA parameters does not remove this failure
  mode. We then propose a constrained Deep LDA formulation that fixes the class means
  to the vertices of a regular simplex in the latent space and restricts the shared
  covariance to be spherical, leaving only the priors and a single variance parameter
  to be learned along with the encoder. Under these geometric constraints, MLE becomes
  stable and yields well-separated class clusters in the latent space. On images (Fashion-MNIST,
  CIFAR-10, CIFAR-100) and texts (AG News, CLINC150), the resulting Deep LDA models
  achieve accuracy competitive with softmax baselines while offering a simple, interpretable
  latent geometry that is clearly visible in two-dimensional projections.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: tezekbayev26a
month: 0
tex_title: Simplex Deep Linear Discriminant Analysis
firstpage: 957
lastpage: 967
page: 957-967
order: 957
cycles: false
bibtex_author: Tezekbayev, Maxat and Bolatov, Arman and Assylbekov, Zhenisbek
author:
- given: Maxat
  family: Tezekbayev
- given: Arman
  family: Bolatov
- given: Zhenisbek
  family: Assylbekov
date: 2026-04-06
address:
container-title: Conference on Parsimony and Learning
volume: '328'
genre: inproceedings
issued:
  date-parts:
  - 2026
  - 4
  - 6
pdf: https://raw.githubusercontent.com/mlresearch/v328/main/assets/tezekbayev26a/tezekbayev26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
