---
layout: post
title:  "Photometric Classification of Supernovae"
date:   2020-10-19
categories: paper
speaker: Eve Chase
---

This meeting focused on the paper Supernova Photometric Classification Pipelines Trained on Spectroscopically Classified Supernovae from the Pan-STARRS1 Medium-Deep Survey. This paper discusses a range of commonly used feature extraction and classification algorithms and compares their performance on supernova data using different metrics. 

# Abstract

> Photometric classification of supernovae (SNe) is imperative as recent and upcoming optical time-domain surveys, such as the Large Synoptic Survey Telescope (LSST), overwhelm the available resources for spectrosopic follow-up. Here we develop a range of light curve classification pipelines, trained on 518 spectroscopically-classified SNe from the Pan-STARRS1 Medium-Deep Survey (PS1-MDS): 357 Type Ia, 93 Type II, 25 Type IIn, 21 Type Ibc, and 17 Type I SLSNe. We present a new parametric analytical model that can accommodate a broad range of SN light curve morphologies, including those with a plateau, and fit this model to data in four PS1 filters (griz). We test a number of feature extraction methods, data augmentation strategies, and machine learning algorithms to predict the class of each SN. Our best pipelines result in 90% average accuracy, 70% average purity, and 80% average completeness for all SN classes, with the highest success rates for Type Ia SNe and SLSNe and the lowest for Type Ibc SNe. Despite the greater complexity of our classification scheme, the purity of our Type Ia SN classification, 95%, is on par with methods developed specifically for Type Ia versus non-Type Ia binary classification. As the first of its kind, this study serves as a guide to developing and training classification algorithms for a wide range of SN types with a purely empirical training set, particularly one that is similar in its characteristics to the expected LSST main survey strategy. Future work will implement this classification pipeline on ~3000 PS1/MDS light curves that lack spectroscopic classification. 

The paper is available [here].

[here]: https://arxiv.org/abs/1905.07422
