---
title: Emergence of Auditory Receptive Fields based on Surprise
openreview: 992xgvrxDK
abstract: Understanding how sensory systems efficiently encode natural stimuli is
  a fundamental challenge in neuroscience. While the efficient coding hypothesis explains
  many aspects of sensory processing, its role in processing surprising auditory inputs
  remains unclear. We present two computational frameworks modeling the development
  of auditory neural receptive fields via unsupervised learning to address this challenge.
  In the first framework, a single-layer network’s synaptic weights adapt to auditory
  inputs to maximize activations for surprising events while minimizing overall activity.
  The weights are adjusted using three factors $(\alpha, \beta, \gamma)$ and the gradient
  of the $l1$ norm of activations. An autoregressive generative model (CochleaNet),
  trained on LibriSpeech, provides the joint probability distribution to calculate
  surprise, defined as the negative log probability of time-frequency bin energy conditioned
  on previous time steps and other frequency channels. We find learning to be fast,
  with robust convergence of weights using random speech samples. This approach yields
  spectrotemporal receptive fields (STRFs) whose tuning properties closely match neurophysiological
  observations. Second, we propose a principled Kalman-MI formulation in which the
  generative prior, latent auditory state, and synaptic weights are jointly updated
  online. Mutual-information gradients, serving as a normative proxy for expected
  surprise reduction, drive adaptation in a linear-Gaussian state-space model, producing
  deviant-selective receptive fields in an oddball paradigm. Together, these approaches
  aim to refine the interplay between sparse coding and surprise-driven learning,
  offering new insights into efficient sensory encoding.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: yashaswini26a
month: 0
tex_title: Emergence of Auditory Receptive Fields based on Surprise
firstpage: 968
lastpage: 988
page: 968-988
order: 968
cycles: false
bibtex_author: Yashaswini, Yashaswin and Dash, Sneha and Bandyopadhyay, Sharba
author:
- given: Yashaswin
  family: Yashaswini
- given: Sneha
  family: Dash
- given: Sharba
  family: Bandyopadhyay
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
pdf: https://raw.githubusercontent.com/mlresearch/v328/main/assets/yashaswini26a/yashaswini26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
