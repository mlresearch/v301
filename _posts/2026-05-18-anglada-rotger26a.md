---
title: 'Two Heads Are Enough: DualU-Net, a Fast and Efficient Architecture for Nuclei
  Instance Segmentation'
abstract: 'Accurate detection and classification of cell nuclei in histopathological
  images are critical for both clinical diagnostics and large-scale digital pathology
  workflows. In this work, we introduce DualU-Net, a fully convolutional, multi-task
  architecture designed to streamline nuclei classification and segmentation. Unlike
  the widely adopted three-decoder paradigm of HoVer-Net, DualU-Net employs only two
  output heads: a segmentation decoder that predicts pixel-wise classification maps
  and a detection decoder that estimates Gaussian-based centroid density maps. By
  leveraging these two outputs, our model effectively reconstructs instance-level
  segmentations. The proposed architecture results in significantly faster inference,
  reducing processing time by up to x5 compared to HoVer-Net, while achieving classification
  and detection performance comparable to State-of-the-Art models. Additionally, our
  approach demonstrates greater computational efficiency than CellViT and NuLite.
  We further show that DualU-Net is more robust to staining variations, a common challenge
  in digital pathology workflows. The model has been successfully deployed in clinical
  settings as part of the DigiPatICS initiative, operating across eight hospitals
  within the Institut Catal{à} de la Salut (ICS) network, highlighting the practical
  viability of DualU-Net as an efficient and scalable solution for nuclei segmentation
  and classification in real-world pathology applications. The code and pretrained
  model weights are publicly available on https://github.com/davidanglada/DualU-Net.'
year: '2025'
booktitle: Proceedings of The 8th International Conference on Medical Imaging with
  Deep Learning
publisher: PMLR
series: Proceedings of Machine Learning Research
volume: '301'
layout: inproceedings
issn: 2640-3498
id: anglada-rotger26a
month: 0
tex_title: 'Two Heads Are Enough: DualU-Net, a Fast and Efficient Architecture for
  Nuclei Instance Segmentation'
firstpage: 15
lastpage: 29
page: 15-29
order: 15
cycles: false
bibtex_author: Anglada-Rotger, David and Jansat, Berta and Marques, Ferran and Pard\`as,
  Montse
author:
- given: David
  family: Anglada-Rotger
- given: Berta
  family: Jansat
- given: Ferran
  family: Marques
- given: Montse
  family: Pardàs
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
pdf: https://raw.githubusercontent.com/mlresearch/v301/main/assets/anglada-rotger26a/anglada-rotger26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
