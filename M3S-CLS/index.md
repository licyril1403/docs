---
layout: home
paginate: true
title: "Contrastive Learning and Physics Oriented Evaluation for Advanced Segmentation in Electron Tomography"
alt_title: "Contrastive Learning and Physics Oriented Evaluation for Advanced Segmentation in Electron Tomography"
sub_title: "Cyril Li, Christophe Ducottet, Maxime Moreaud, Sylvain Desroziers, Valentina Girelli Consolaro, Virgile Rouchon, Ovidiu Ersen"
introduction: M3S-CLS is a semi-supervised segmentation in the particular context of the assessment of zeolite catalytic properties. We provide an implementation of M3S-CLS and a dataset of five fully segmented ET volumes.

actions:
  - label: "Code"
    icon: github
    url: "https://github.com/licyril1403/M3S-CLS"
  - label: "Paper"
    icon: pdf
    url: "https://github.com/mmistakes/jekyll-theme-basically-basic"
  - label: "Database"
    icon: download
    url: "https://1drv.ms/u/c/a17cae2346a35cfe/EUt9HJ9ijm1PvhPsq9ZM-usBNz19eWNaObbBpeiUPhBXlw?e=pKKveJ"
---

![Semi supervised setup](/assets/images/semi_supervised_setup.png)

## Abstract

Deep learning methods are now achieving strong results for segmentation tasks, and the standard metric for evaluating methods is the Intersection over Union (IOU). However, we show in this paper that IOU is not efficient in evaluating the quality of segmentation for electron tomography (ET) images of zeolites. We perform a physics-oriented evaluation to ensure that the segmentation results yield coherent physical measures. We also formalize Mixed Supervised / Self-Supervised Contrastive Learning Segmentation (M3S-CLS), a semi-supervised approach using a contrastive learning approach that uses expert annotations to train the neural network model. A detailed comparison of this method with a standard cross-entry-based model is provided. In addition, we publish a database of five fully segmented ET volumes along with corresponding baseline results.
