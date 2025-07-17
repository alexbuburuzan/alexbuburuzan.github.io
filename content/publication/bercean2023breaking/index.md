---
title: "Breaking Down Covariate Shift on Pneumothorax Chest X-Ray Classification"
publication_types:
  - "1"
authors:
  - Bogdan Bercean
  - Alexandru Buburuzan
  - Andreea Birhala
  - Cristian Avramescu
  - Andrei Tenescu
  - Marius Marcu
doi: http://dx.doi.org/10.1007/978-3-031-44336-7_16
url_code: https://github.com/RayscapeAI/LISA-topK
publication: MICCAI UNSURE
abstract: 
  MICCAI 2023 UNSURE

  Domain shift poses significant problems to computer-aided diagnostic (CAD) systems when deployed in clinical scenarios. There’s still no definite fix nor an in-depth understanding of the exact factors driving domain shifts in medical X-rays. Here, we conduct an exploratory study on three covariate shift factors in X-ray classification by controlling for different variables. This is possible by leveraging a homogenously-relabelled mix of public and private X-ray data spanning 23 medical institutions over four continents and 17 classes of pathologies. We show that the acquisition parameter, device manufacturer and geographical shifts degrade out-of-distribution (OOD) F1 by 6%, 3.2% and 3.3%, respectively. Pneumothorax was found to be the most impaired pathology, suffering a mean F1 generalisation gap of 13.3%, despite being one of the most clinically-consequential radiological findings. To this end, we introduced LISA-topK, a multi-label adaptation of Learning Invariant Predictors with Selective Augmentation (LISA), that we showed to narrow down the OOD gap, surpassing other methods consistently. These pragmatic results shed light on some of the elements of OOD generalisation in X-ray classification, which are essential to researching, understanding and deploying CAD systems.
draft: false
featured: false
image:
  filename: figure.png
  focal_point: Smart
  preview_only: false
  caption: ""
date: 2023-10-07
---
