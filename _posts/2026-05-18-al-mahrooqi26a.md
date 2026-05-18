---
title: Empirical Analysis of Scaling Vision Foundation Models for Chest X-rays
abstract: Recent advancements in multimodal transformers have shown remarkable success
  in computer vision and natural language tasks, yet their adaptation to the clinical
  world remains challenging. We introduce CXformer, a vision transformer adapted for
  chest X-ray analysis, through systematic investigation of architectural choices
  and training modifications from DINOv2. Our empirical results show that using registers
  in ViT training, centering the teacher modelś softmax outputs, and optimizing the
  number of heads leads to better performance. The small version of CXformer(S) (22M
  parameters) achieves 83.28% mean AUROC on CheXpert test set, surpassing the baseline
  of 80.46% achieved with vanilla DINOv2 settings. Contrary to common assumptions,
  our larger model CXformer(B) with 87M parameters shows similar performance at 84%
  mean AUROC on CheXpert, suggesting that training optimizations matter more than
  model size. Furthermore compared to the current state-of-the-art RAD-DINO, our CXformer(B),
  with 46% reduced pretraining compute (in FLOPs) achieves an average AUROC of 87.93%
  (vs 87.32% by RAD-DINO) on pathology image classification task evaluated across
  three widely used CXR datasets i.e. CheXpert, RSNA Pneumonia, and NIH CXR8. Beyond
  classification, CXformer also delivers competitive, and occasionally superior, performance
  in semantic segmentation and radiology report generation, underscoring its versatility.
  CXformer base and small models can be found at https://huggingface.co/m42-health
year: '2025'
booktitle: Proceedings of The 8th International Conference on Medical Imaging with
  Deep Learning
publisher: PMLR
series: Proceedings of Machine Learning Research
volume: '301'
layout: inproceedings
issn: 2640-3498
id: al-mahrooqi26a
month: 0
tex_title: Empirical Analysis of Scaling Vision Foundation Models for Chest X-rays
firstpage: 1074
lastpage: 1094
page: 1074-1094
order: 1074
cycles: false
bibtex_author: Al Mahrooqi, Ahmed and Munjal, Prateek and Rajan, Ronnie and Pimentel,
  Marco AF and Kanithi, Praveenkumar
author:
- given: Ahmed
  family: Al Mahrooqi
- given: Prateek
  family: Munjal
- given: Ronnie
  family: Rajan
- given: Marco AF
  family: Pimentel
- given: Praveenkumar
  family: Kanithi
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
pdf: https://raw.githubusercontent.com/mlresearch/v301/main/assets/al-mahrooqi26a/al-mahrooqi26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
