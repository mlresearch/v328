---
title: 'LLMQ: Efficient Lower-Precision LLM Training for Consumer GPUs'
openreview: nEev1u9Kzm
abstract: We present LLMQ, an end-to-end CUDA/C++ implementation for medium-sized
  language-model training, e.g. 3B to 32B parameters, on affordable, commodity GPUs.
  These devices are characterized by low memory availability and slow communication
  compared to datacentre-grade GPUs. Consequently, we showcase a range of optimizations
  that target these bottlenecks, including activation checkpointing, offloading, and
  copy-engine based collectives. LLMQ is  able to train or fine-tune a 7B model on
  a single 16GB mid-range gaming card, or a 32B model on a workstation equipped with
  4 RTX 4090s. This is achieved while executing a standard 8-bit training pipeline,
  without additional algorithmic approximations, and maintaining FLOP utilization
  of around 50%. The efficiency of LLMQ rivals that of production-scale systems on
  much more expensive cloud-grade GPUs.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: schultheis26a
month: 0
tex_title: 'LLMQ: Efficient Lower-Precision LLM Training for Consumer GPUs'
firstpage: 265
lastpage: 284
page: 265-284
order: 265
cycles: false
bibtex_author: Schultheis, Erik and Alistarh, Dan
author:
- given: Erik
  family: Schultheis
- given: Dan
  family: Alistarh
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
pdf: https://raw.githubusercontent.com/mlresearch/v328/main/assets/schultheis26a/schultheis26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
