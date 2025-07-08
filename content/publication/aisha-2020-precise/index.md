---
title: "Precise Single-stage Detector"
authors:
- Aisha Chandio
- Gong Gui
- Teerath Kumar
- admin
- Ramin Ranjbarzadeh
- Arunabha M. Roy
- Akhtar Hussain
- Yao Shen
author_notes:
- 
- 
-
- "ORCID: 0000-0003-1659-6040"
- 
-
date: "2022-10-09T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-10-09T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Deep learning (DL) logarithms have shown an impressive performance in various tasks. Among them, Single-stage object detectors (SSD) mainly depends on classification network to extract features, multiple feature maps to predict, and classification confidence to guide the filtration of the overlapping prediction boxes. However, there are still two problems causing some inaccurate results. (1) In the process of feature extraction, with the layer-by-layer acquisition of semantic information, local information is gradually lost, resulting into less representative feature maps; (2) During the Non-Maximum Suppression (NMS) algorithm due to inconsistency in classification and regression tasks, the classification confidence and predicted detection position cannot accurately indicate the position of the prediction boxes. In order to address these aforementioned issues, we propose a new architecture, a modified version of Single Shot Multibox Detector (SSD), named Precise Single Stage Detector (PSSD). Firstly, we improve the features by adding extra layers to SSD. Secondly, we construct a simple and effective feature enhancement module to expand the receptive field step by step for each layer and enhance its local and semantic information. Finally, we design a more efficient loss function to predict the IOU between the prediction boxes and ground truth boxes, and the threshold IOU guides classification training and attenuates the scores, which are used by the NMS algorithm. Main Results. Benefiting from the above optimization, the proposed model PSSD achieves exciting performance in real-time. Specifically, with the hardware of Titan Xp and the input size of 320 pix, PSSD achieves 33.8 mAP at 45 FPS speed on MS COCO benchmark and 81.28 mAP at 66 FPS speed on Pascal VOC 2007 outperforming state-of-the-art object detection models. Besides, the proposed model performs significantly well with larger input size. Under 512 pix, PSSD can obtain 37.2 mAP with 27 FPS on MS COCO and 82.82 mAP with 40 FPS on Pascal VOC 2007. The experiment results prove that the proposed model has a better trade-off between speed and accuracy.

# Summary. An optional shortened abstract.
summary: PSSD augments the Single Shot Multibox Detector with extra layers, a progressive feature-enhancement module, and an IOU-guided loss for NMS, achieving state-of-the-art speed–accuracy trade-offs on MS COCO and Pascal VOC.

tags:
- Deep Learning
- Object Detection
- Single Shot Multibox Detector (SSD)
- Feature Enhancement Module
- IOU-Guided Loss

featured: true

links:
- name: ''
  url: ''
url_pdf: https://arxiv.org/pdf/2210.04252
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
