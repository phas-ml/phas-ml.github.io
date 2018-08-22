---
layout: post
title:  "Dropout as a Bayesian Approximation: Representing Model Uncertainty in Deep Learning"
date:   2018-02-23
categories: paper
---

At this meeting we addressed a recurring topic about neural networks: uncertainty. This papers argues that the normalization technique Dropout can be considered a bayesian approximation under the correct circumstances.

# Abstract

> Deep learning tools have gained tremendous attention in applied machine learning. However such tools for regression and classification do not capture model uncertainty. In comparison, Bayesian models offer a mathematically grounded framework to reason about model uncertainty, but usually come with a prohibitive computational cost. In this paper we develop a new theoretical framework casting dropout training in deep neural networks (NNs) as approximate Bayesian inference in deep Gaussian processes. A direct result of this theory gives us tools to model uncertainty with dropout NNs -- extracting information from existing models that has been thrown away so far. This mitigates the problem of representing uncertainty in deep learning without sacrificing either computational complexity or test accuracy. We perform an extensive study of the properties of dropout's uncertainty. Various network architectures and non-linearities are assessed on tasks of regression and classification, using MNIST as an example. We show a considerable improvement in predictive log-likelihood and RMSE compared to existing state-of-the-art methods, and finish by using dropout's uncertainty in deep reinforcement learning. 

Here is a link to the [paper]. A [git repository][git-repo] was released after the paper and is still beging actively maintained.

[paper]: https://arxiv.org/abs/1506.02142
[git-repo]: https://github.com/yaringal/DropoutUncertaintyExps
