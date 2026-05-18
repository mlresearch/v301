---
title: Evaluating Shortcut Utilization in Deep Learning Disease Classification through
  Counterfactual Analysis
abstract: 'Although deep learning models can surpass human performance in many medical
  image analysis tasks, they remain vulnerable to algorithmic shortcuts, where spurious
  correlations in the data are exploited, which may lead to reduced trust in their
  predictions/classifications. This issue is especially concerning when models rely
  on protected attributes (e.g., sex, race, or site) as shortcuts. Such shortcut reliance
  not only impairs their ability to generalize to unseen datasets but also raises
  fairness concerns, ultimately undermining their purpose for computer-aided diagnosis.
  Previous techniques for analyzing protected attributes, such as supervised prediction
  layer information tests, only highlight the presence of protected attributes in
  the feature space but do not confirm their role in solving the primary task. Determining
  the impact of protected attributes as shortcuts is particularly challenging, as
  it requires knowing how a model would perform without those attributes — a counterfactual
  scenario typically unattaiw:nable in real-world data. As a workaround, researchers
  have addressed the absence of counterfactuals by generating synthetic datasets with
  and without protected attributes. In this study, we propose a novel approach to
  evaluate real-world datasets and determine the extent to which each protected attribute
  is used as a shortcut in a classification task. Therefore, we define and train a
  causal generative model to produce causally-grounded counterfactuals, removing protected
  attributes from activations and allowing us to measure their impact on model performance.
  Employing T1-weighted MRI data from 9 sites (835 subjects: 426 with Parkinson’s
  disease (PD) and 409 healthy), we demonstrate that counterfactually removing the
  śite\’{attribute} from the penultimate layer of a trained classification model reduced
  the AUROC for PD classification from 0.74 to 0.65, indicating a 9% performance improvement
  achieved by using śite\’{as} a shortcut. In contrast, counterfactually removing
  the śex\’{attribute} had minimal impact on performance, with only a slight change
  of 0.004, indicating that śex\’{was} not utilized as a shortcut by the classification
  model. The proposed method offers a robust framework for assessing shortcut utilization
  in medical image classification, paving the way for improved bias detection and
  mitigation in medical imaging tasks. The code for this work is available on https://github.com/vibujithan/shortcut-analysis.'
year: '2025'
booktitle: Proceedings of The 8th International Conference on Medical Imaging with
  Deep Learning
publisher: PMLR
series: Proceedings of Machine Learning Research
volume: '301'
layout: inproceedings
issn: 2640-3498
id: vigneshwaran26a
month: 0
tex_title: Evaluating Shortcut Utilization in Deep Learning Disease Classification
  through Counterfactual Analysis
firstpage: 1653
lastpage: 1668
page: 1653-1668
order: 1653
cycles: false
bibtex_author: Vigneshwaran, Vibujithan and Stanley, Emma A.M. and Souza, Raissa and
  Ohara, Erik and Wilms, Matthias and Forkert, Nils
author:
- given: Vibujithan
  family: Vigneshwaran
- given: Emma A.M.
  family: Stanley
- given: Raissa
  family: Souza
- given: Erik
  family: Ohara
- given: Matthias
  family: Wilms
- given: Nils
  family: Forkert
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
pdf: https://raw.githubusercontent.com/mlresearch/v301/main/assets/vigneshwaran26a/vigneshwaran26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
