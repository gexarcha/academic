---
title: Dissecting Self-Supervised Learning Methods for Surgical Computer Vision
publication_types:
  - "2"
authors:
  - Sanat Ramesh
  - Vinkle Srivastav
  - Deepak Alapatt
  - Tong Yu
  - Aditya Murali
  - Luca Sestini
  - Chinedu Innocent Nwoye
  - Idris Hamoud
  - Antoine Fleurentin
  - Georgios Exarchakis
  - Alexandros Karargyris
  - Nicolas Padoy
publication: Pre-Print
publication_short: Pre-Print
abstract: >
 The field of surgical computer vision has undergone considerable breakthroughs in recent years with the rising popularity of deep neural network-based methods. However, standard fully-supervised approaches for training such models require vast amounts of annotated data, imposing a prohibitively high cost; especially in the clinical domain. Self-Supervised Learning (SSL) methods, which have begun to gain traction in the general computer vision community, represent a potential solution to these annotation costs, allowing to learn useful representations from only unlabeled data. Still, the effectiveness of SSL methods in more complex and impactful domains, such as medicine and surgery, remains limited and unexplored. In this work, we address this critical need by investigating four state-of-the-art SSL methods (MoCo v2, SimCLR, DINO, SwAV) in the context of surgical computer vision. We present an extensive analysis of the performance of these methods on the Cholec80 dataset for two fundamental and popular tasks in surgical context understanding, phase recognition and tool presence detection. We examine their parameterization, then their behavior with respect to training data quantities in semi-supervised settings. Correct transfer of these methods to surgery, as described and conducted in this work, leads to substantial performance gains over generic uses of SSL - up to 7% on phase recognition and 20% on tool presence detection - as well as state-of-the-art semi-supervised phase recognition approaches by up to 14%. The code will be made available at this [https url](https://github.com/CAMMA-public/SelfSupSurg).

draft: false
featured: false
url_pdf : "https://arxiv.org/pdf/2207.00449.pdf"
image:
  filename: ""
  focal_point: ""
  preview_only: false
date: 2022-07-05T08:59:06.058Z
---
