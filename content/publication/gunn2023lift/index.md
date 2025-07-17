---
title: "Lift-Attend-Splat: Bird's-eye-view camera-lidar fusion using transformers"
publication_types:
  - "1"
authors:
  - James Gunn
  - Zygmunt Lenyk
  - Anuj Sharma
  - Andrea Donati
  - Alexandru Buburuzan
  - John Redford
  - Romain Mueller
doi: https://doi.org/10.48550/arXiv.2312.14919
publication: CVPR Workshop on Autonomous Driving (WAD)
abstract: |
  CVPR 2024 WAD

  Combining complementary sensor modalities is crucial to providing robust perception for safety-critical robotics applications such as autonomous driving (AD). Recent state-of-the-art camera-lidar fusion methods for AD rely on monocular depth estimation which is a notoriously difficult task compared to using depth information from the lidar directly. Here, we find that this approach does not leverage depth as expected and show that naively improving depth estimation does not lead to improvements in object detection performance and that, strikingly, removing depth estimation altogether does not degrade object detection performance. This suggests that relying on monocular depth could be an unnecessary architectural bottleneck during camera-lidar fusion. In this work, we introduce a novel fusion method that bypasses monocular depth estimation altogether and instead selects and fuses camera and lidar features in a bird's-eye-view grid using a simple attention mechanism. We show that our model can modulate its use of camera features based on the availability of lidar features and that it yields better 3D object detection on the nuScenes dataset than baselines relying on monocular depth estimation.
draft: false
featured: false
image:
  filename: figure.png
  focal_point: Smart
  preview_only: false
  caption: ""
date: 2024-06-15
---
