---
title: "MObI: Multimodal Object Inpainting Using Diffusion Models"
publication_types:
  - "1"
authors:
  - Alexandru Buburuzan
  - Anuj Sharma
  - John Redford
  - Puneet K. Dokania
  - Romain Mueller
doi: http://dx.doi.org/10.48550/arXiv.2501.03173
publication: CVPR Workshop on Data-Driven Autonomous Driving Simulation
abstract: |
  *CVPR 2025 DDADS |* MObI enables realistic, controllable insertion of objects, jointy, in both camera and lidar, using a single reference image. [Project page →](https://alexbubu.com/mobi)


  Safety-critical applications, such as autonomous driving, require extensive multimodal data for rigorous testing. Methods based on synthetic data are gaining prominence due to the cost and complexity of gathering real-world data but require a high degree of realism and controllability to be useful. This paper introduces MObI, a novel framework for Multimodal Object Inpainting that leverages a diffusion model to create realistic and controllable object inpaintings across perceptual modalities, demonstrated for both camera and lidar simultaneously. Using a single reference RGB image, MObI enables objects to be seamlessly inserted into existing multimodal scenes at a 3D location specified by a bounding box, while maintaining semantic consistency and multimodal coherence. Unlike traditional inpainting methods that rely solely on edit masks, our 3D bounding box conditioning gives objects accurate spatial positioning and realistic scaling. As a result, our approach can be used to insert novel objects flexibly into multimodal scenes, providing significant advantages for testing perception models.
url_code: https://github.com/alexbuburuzan/MObI
url_custom:
  - name: Project Page
    url: https://alexbubu.com/mobi
date: 2025-07-13
draft: false
featured: false
image:
  filename: figure.png
  focal_point: Smart
  preview_only: false
  caption: ""
---
