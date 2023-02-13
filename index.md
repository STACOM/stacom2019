---
layout: home
author_profile: false
classes:
  - wide
header:
  image: /images/shenzen.png
---

{: .text-justify}
The Statistical Atlases and Computational Modeling of the Heart (STACOM) workshop has been running annually at MICCAI since 2010. The 10th edition of STACOM workshop will be held in conjunction with the [MICCAI 2019](https://www.miccai2019.org/) on 13 October 2020 in Lima, Peru. The STACOM workshop is aiming to create a collaborative forum for young/senior researchers (engineers, biophysicists, mathematicians) and clinicians, working on: statistical analysis of cardiac morphology and dynamics, computational modelling of the heart and fluid dynamics, data/models sharing, personalisation of cardiac electro-mechanical models, quantitative image analysis and translational methods into clinical practice.

## Keynote speaker

[**Sotirios A. Tsaftaris**]({{ "keynote" | relative_url }})<br>Professor at University of Edinburgh, United Kingdom

*Disentangled representation learning in medical imaging*

<embed src="{{ '/assets/sotos_stacom2019_x.pdf' | relative_url }}" type="application/pdf"/>

## Challenges

STACOM 2019 is running three exciting challenges:

### Multi-Centre, Multi-Vendor, Multi-Disease Cardiac Image Segmentation Challenge

![]({{ "images/mms.jpg" | relative_url }})

We provide 45 multi-sequence CMR images from patients who underwent cardiomyopathy. Each patient had been scanned using the three CMR sequences, i.e. the LGE, T2 and bSSFP. The task of this challenge is to segment the ventricles and myocardium from LGE CMR, combing with other two sequences (T2 and bSSFP) from same patients, which can be used to assist the LGE CMR segmentation.

<div style="text-align: left;"><a href="https://zmiclab.github.io/zxh/0/mscmrseg19/" target="_blank" class="btn btn--info btn--large" style="padding-left: 50px; padding-right: 50px;">MSCMRSeg19 Website</a></div>

### LV Full Quantification Challenge

![]({{ "images/lvquan.jpg" | relative_url }})

The aim of this challenge is to learn effective machine learning models that can estimate a set of clinical significant LV indices (regional wall thicknesses, cavity dimensions, area of cavity and myocardium, cardiac phase) directly from MR images. No intermediate segmentation is required in the whole procedure. 

<div style="text-align: left;"><a href="https://lvquan19.github.io/" target="_blank" class="btn btn--info btn--large" style="padding-left: 50px; padding-right: 50px;">MSCMRSeg19 Website</a></div>

### CRT-EPIGGY19 Challenge

![]({{ "images/logo_v1-1.png" | relative_url }})

The main goal of the challenge is to assess the ability of cardiac computational models to predict the electrical outcome of pacemaker-based therapies. The challenge will be based on multi-modal data acquired at Hospital Clínic de Barcelona of a swine model of left bundle branch block for experimental studies of CRT. Biventricular finite-element meshes, including cardiomyocyte orientation from rule-based models and local activation times mapped from electro-anatomical data at LBBB and CRT stages, will be provided to the participants as training data (4 cases). After model personalization, participants will be asked to predict electrical response in the testing dataset (8 cases).

<div style="text-align: left;"><a href="http://crt-epiggy19.surge.sh/" target="_blank" class="btn btn--info btn--large" style="padding-left: 50px; padding-right: 50px;">MSCMRSeg19 Website</a></div>

