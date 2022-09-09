---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Junior Data Scientist
    company: XVision
    company_url: 'https://xvision.app/'
    company_logo: org-x
    location: 
    date_start: '2021-07'
    date_end: ''
    description: |2-
        * Developed a CE-marked 3D Deep Learning algorithm for the segmentation of nodules on lung CT scans that helps radiologists better identify these abnormalities whilst providin precise measurements.
        * Decreased the error of the predicted measurements (L1) by a factor of 2 compared to the previous model by using a decoder-style sub-network which exploits pre-existing feature maps and implements a segmentation refinement mechanism.

  - title: Data Science Intern
    company: XVision
    company_url: 'https://xvision.app/'
    company_logo: org-x
    location:
    date_start: '2020-03'
    date_end: '2020-09'
    description: |2-
        * Conducted interdisciplinary work with radiologists towards building a robust and time-efficient AI model for the detection of intracranial haemorrhages meant for speeding up the triaging process.
        * Improved the generalization of the model by using a special data pre-processing technique and performed extensive data cleaning on anonymized brain CT scans of the order of terabytes.
        * Developed three Computer Vision algorithms as part of my initial training: lung segmentation (U-Net), pathology classification (CNN classifiers) and foreign objects detection (Faster R-CNN) on X-ray scans.

design:
  columns: '2'
---
