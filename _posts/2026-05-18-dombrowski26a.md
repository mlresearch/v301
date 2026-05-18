---
title: Can Diffusion Models Generalize? Privacy and Fairness Trade-offs for Medical
  Data Sharing.
abstract: The recent surge in options for diffusion model-based synthetic data sharing
  offers significant benefits for medical research, provided privacy and fairness
  concerns are addressed.Generative models risk memorizing sensitive training samples,
  potentially exposing identifiable information.Simultaneously, underrepresented features
  – such as rare diseases, uncommon medical devices, or infrequent patient ethnicities
  – are often not learned well, creating unfair biases in downstream applications.Our
  work unifies these challenges by leveraging artificially generated fingerprints
  (SAFs) in the training data as a controllable test for memorization and fairness.Specifically,
  we measure whether a diffusion model reproduces these fingerprints verbatim (a privacy
  breach) or ignores them entirely (a fairness violation) and introduce an indicator
  t\’{to} quantify finished models for the likelihood of reproducing training samples.Extensive
  experiments on real and synthetic medical imaging datasets reveal that na{ï}ve diffusion
  model training can lead to privacy leaks or unfair coverage.By systematically incorporating
  SAFs and monitoring t\’, we demonstrate how to balance privacy and fairness objectives.Our
  evaluation framework provides actionable guidance for designing generative models
  that preserve patient anonymity without excluding underrepresented patient subgroups.
  Code is available at https://github.com/MischaD/Privacy.
year: '2025'
booktitle: Proceedings of The 8th International Conference on Medical Imaging with
  Deep Learning
publisher: PMLR
series: Proceedings of Machine Learning Research
volume: '301'
layout: inproceedings
issn: 2640-3498
id: dombrowski26a
month: 0
tex_title: Can Diffusion Models Generalize? Privacy and Fairness Trade-offs for Medical
  Data Sharing.
firstpage: 366
lastpage: 392
page: 366-392
order: 366
cycles: false
bibtex_author: Dombrowski, Mischa and Kainz, Bernhard
author:
- given: Mischa
  family: Dombrowski
- given: Bernhard
  family: Kainz
date: 2026-05-18
address:
container-title: Proceedings of The 8th International Conference on Medical Imaging
  with Deep Learning
genre: inproceedings
issued:
  date-parts:
  - 2026
  - 5
  - 18
pdf: https://raw.githubusercontent.com/mlresearch/v301/main/assets/dombrowski26a/dombrowski26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
