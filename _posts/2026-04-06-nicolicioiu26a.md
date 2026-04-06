---
title: 'Panza: Investigating the Feasibility of Fully-Local Personalized Text Generation'
openreview: soFWnTqd23
abstract: The availability of powerful open-source large language models (LLMs) opens
  exciting use cases, such as using personal data to fine-tune these models to imitate
  a user’s unique writing style. Two key requirements for this functionality are personalization–in
  the sense that the output should recognizably reflect the user’s own writing style—and
  privacy–users may justifiably be wary of uploading extremely personal data, such
  as their email archive, to a third-party service. In this paper, we demonstrate
  the feasibility of training and running such an assistant, which we call Panza,
  on commodity hardware, for the specific use case of email generation. Panza’s personalization
  features are based on a combination of parameter-efficient fine-tuning using a variant
  of the Reverse Instructions technique and Retrieval-Augmented Generation (RAG).
  We demonstrate that this combination allows us to fine-tune an LLM to reflect a
  user’s writing style using limited data, while executing on extremely limited resources,
  e.g. on a free Google Colab instance. Our key methodological contribution is the
  first detailed study of evaluation metrics for this task, and of how different choices
  of system components–the use of RAG and of different fine-tuning approaches–impact
  the system’s performance. Additionally, we demonstrate that very little data - under
  100 email samples - are sufficient to create models that convincingly imitate humans,
  showcasing a previously unknown attack vector in language models. We are releasing
  the full Panza code as well as three new email datasets licensed for research use.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: nicolicioiu26a
month: 0
tex_title: 'Panza: Investigating the Feasibility of Fully-Local Personalized Text
  Generation'
firstpage: 104
lastpage: 130
page: 104-130
order: 104
cycles: false
bibtex_author: Nicolicioiu, Armand Mihai and Iofinova, Eugenia and Jovanovic, Andrej
  and Kurtic, Eldar and Nikdan, Mahdi and Panferov, Andrei and Markov, Ilia and Shavit,
  Nir N and Alistarh, Dan
author:
- given: Armand Mihai
  family: Nicolicioiu
- given: Eugenia
  family: Iofinova
- given: Andrej
  family: Jovanovic
- given: Eldar
  family: Kurtic
- given: Mahdi
  family: Nikdan
- given: Andrei
  family: Panferov
- given: Ilia
  family: Markov
- given: Nir N
  family: Shavit
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
pdf: https://raw.githubusercontent.com/mlresearch/v328/main/assets/nicolicioiu26a/nicolicioiu26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
