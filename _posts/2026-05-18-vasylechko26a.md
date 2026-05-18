---
title: Enhancing Wrist Fracture Detection through LLM-Powered Data Extraction and
  Knowledge-Based Ensemble Learning
abstract: The accuracy and generalization of deep learning models for fracture detection
  and classification in wrist radiographs is often limited by the scarcity of high-quality
  annotated data and class imbalances. Traditional annotation methods are time-consuming,
  expensive and prone to inter-observer variability \cite{rajpurkar2017mura}.  To
  address these challenges, we developed an automated, cost-free approach to extract
  structured information from radiology reports, such as fracture type, location and
  severity. Our technique incorporates methods introduced by MedPrompt \cite{nori2023can},
  and leverages domain expertise for group based sampling \cite{khan2024knowledge}.
  Using these structured language labels alongside a pre-trained YOLO v7 backbone
  \cite{nagy2022pediatric, ciri2023bonefracture}, which initially demonstrated low
  accuracy scores on our clinical data, we were able to selectively finetune the model
  in pseudo-blind manner. This approach utilized the extracted language labels without
  requiring expert annotations for training. We curated a large dataset of almost
  3,000 pediatric wrist X-ray images and their corresponding radiology reports. Validation
  and testing were conducted on a smaller subset of 300 expert-annotated images.Our
  findings indicate that this pseudo-blind training strategy significantly enhances
  the base accuracy of the pre-trained model, achieving performance comparable to
  models fine-tuned with meticulously labeled expert annotations. Specifically, we
  improved the mean Average Precision (mAP) detection score for true positives related
  to fractures from 76% to 83%. Additionally, we observed improvements in precision
  and recall metrics for fracture detection. By integrating prompt-based information
  extraction with knowledge-based grouping, we achieved a robust and effective model
  for fracture detection.
year: '2025'
booktitle: Proceedings of The 8th International Conference on Medical Imaging with
  Deep Learning
publisher: PMLR
series: Proceedings of Machine Learning Research
volume: '301'
layout: inproceedings
issn: 2640-3498
id: vasylechko26a
month: 0
tex_title: Enhancing Wrist Fracture Detection through LLM-Powered Data Extraction
  and Knowledge-Based Ensemble Learning
firstpage: 1627
lastpage: 1637
page: 1627-1637
order: 1627
cycles: false
bibtex_author: Vasylechko, Serge Didenko and Tsai, Andy and Afacan, Onur and Kurugol,
  Sila
author:
- given: Serge Didenko
  family: Vasylechko
- given: Andy
  family: Tsai
- given: Onur
  family: Afacan
- given: Sila
  family: Kurugol
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
pdf: https://raw.githubusercontent.com/mlresearch/v301/main/assets/vasylechko26a/vasylechko26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
