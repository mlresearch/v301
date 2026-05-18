---
title: 'PixelCAM: Pixel Class Activation Mapping for Histology Image Classification
  and ROI Localization'
abstract: Weakly supervised object localization (WSOL) methods allow training models
  to classifyimages and localize ROIs. WSOL only requires low-cost image-class annotations
  yet provides a visually interpretable classifier, which is important in histology
  image analysis.Standard WSOL methods rely on class activation mapping (CAM) methods
  to producespatial localization maps according to a single- or two-step strategy.
  While both strategies have made significant progress, they still face several limitations
  with histology images. Single-step methods can easily result in under- or over-activation
  due to the limitedvisual ROI saliency in histology images and scarce localization
  cues. They also face thewell-known issue of asynchronous convergence between classification
  and localization tasks.The two-step approach is sub-optimal because it is constrained
  to a frozen classifier, limiting the capacity for localization. Moreover, these
  methods also struggle when appliedto out-of-distribution (OOD) datasets. In this
  paper, a multi-task approach for WSOLis introduced for simultaneous training of
  both tasks to address the asynchronous convergence problem. In particular, localization
  is performed in the pixel-feature space of animage encoder that is shared with classification.
  This allows learning discriminant featuresand accurate delineation of foreground/background
  regions to support ROI localizationand image classification. We propose PixelCAM,
  a cost-effective foreground/backgroundpixel-wise classifier in the pixel-feature
  space that allows for spatial object localization.Using partial-cross entropy, PixelCAM
  is trained using pixel pseudo-labels collected from apretrained WSOL model. Both
  image and pixel-wise classifiers are trained simultaneouslyusing standard gradient
  descent. In addition, our pixel classifier can easily be integratedinto CNN- and
  transformer-based architectures without any modifications. Our extensiveexperiments1
  on GlaS and CAMELYON16 cancer datasets show that PixelCAM can improveclassification
  and localization performance when integrated with different WSOL methods.Most importantly,
  it provides robustness on both tasks for OOD data linked to differentcancer types,
  with large domain shifts between training and testing image data.
year: '2025'
booktitle: Proceedings of The 8th International Conference on Medical Imaging with
  Deep Learning
publisher: PMLR
series: Proceedings of Machine Learning Research
volume: '301'
layout: inproceedings
issn: 2640-3498
id: guichemerre26a
month: 0
tex_title: 'PixelCAM: Pixel Class Activation Mapping for Histology Image Classification
  and ROI Localization'
firstpage: 547
lastpage: 587
page: 547-587
order: 547
cycles: false
bibtex_author: Guichemerre, Alexis and Belharbi, Soufiane and Shateri, Mohammadhadi
  and McCaffrey, Luke and Granger, Eric
author:
- given: Alexis
  family: Guichemerre
- given: Soufiane
  family: Belharbi
- given: Mohammadhadi
  family: Shateri
- given: Luke
  family: McCaffrey
- given: Eric
  family: Granger
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
pdf: https://raw.githubusercontent.com/mlresearch/v301/main/assets/guichemerre26a/guichemerre26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
