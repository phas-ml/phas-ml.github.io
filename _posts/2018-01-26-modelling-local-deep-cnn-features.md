---
layout: post
title:  "Modelling Local Deep Convolutional Neural Network Features to Improve Fine-Grained Image Classification"
date:   2018-01-26
categories: paper
---

At this journal club we discussed an adaption to CNN training that aims to improve feature extraction.

# Abstract

> We propose a local modelling approach using deep convolutional neural networks (CNNs) for fine-grained image classification. Recently, deep CNNs trained from large datasets have considerably improved the performance of object recognition. However, to date there has been limited work using these deep CNNs as local feature extractors. This partly stems from CNNs having internal representations which are high dimensional, thereby making such representations difficult to model using stochastic models. To overcome this issue, we propose to reduce the dimensionality of one of the internal fully connected layers, in conjunction with layer-restricted retraining to avoid retraining the entire network. The distribution of low-dimensional features obtained from the modified layer is then modelled using a Gaussian mixture model. Comparative experiments show that considerable performance improvements can be achieved on the challenging Fish and UEC FOOD-100 datasets. 

Here is a link to the [paper].

[paper]: https://arxiv.org/abs/1502.07802
