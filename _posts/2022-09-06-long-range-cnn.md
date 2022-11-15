---
layout: post
title:  "Towards a General Purpose CNN for Long Range Dependencies in ND"
date:   2022-09-06
categories: paper
speaker: Joe Bayley
---

## Abstract

> The use of Convolutional Neural Networks (CNNs) is widespread in Deep Learning due to a range of desirable model properties which result in an efficient and effective machine learning framework. However, performant CNN architectures must be tailored to specific tasks in order to incorporate considerations such as the input length, resolution, and dimentionality. In this work, we overcome the need for problem-specific CNN architectures with our Continuous Convolutional Neural Network (CCNN): a single CNN architecture equipped with continuous convolutional kernels that can be used for tasks on data of arbitrary resolution, dimensionality and length without structural changes. Continuous convolutional kernels model long range dependencies at every layer, and remove the need for downsampling layers and task-dependent depths needed in current CNN architectures. We show the generality of our approach by applying the same CCNN to a wide set of tasks on sequential (1D) and visual data (2D). Our CCNN performs competitively and often outperforms the current state-of-the-art across all tasks considered.  

## Links

* Towards a General Purpose CNN for Long Range Dependencies in ND - [arXiv](https://arxiv.org/abs/2206.03398)
* Official implementation - [GitHub](https://github.com/david-knigge/ccnn)
