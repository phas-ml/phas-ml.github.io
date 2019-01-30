---
layout: post
title:  "Uncertainty in Neural Networks: Bayesian Ensembling"
date:   2019-01-11
categories: paper
speaker: Michael Williams
---

At this journal club we discussed a paper that proposes a version of neural network ensembling that has a Bayesian basis. 

The authors dicuss the pros and cons of Bayesian neural networks and show that regular neural network ensembling is not reliable form of uncertainty. They propose a form of regularization that keeps parameters around values drawn from a prior distribution. They use a modified version Randomised Maximum a Posterior sampling to justify this regularization.

# Abstract

> Understanding the uncertainty of a neural network's (NN) predictions is essential for many applications. The Bayesian framework provides a principled approach to this, however applying it to NNs is challenging due to the large number of parameters and data. Ensembling NNs provides an easily implementable, scalable method for uncertainty quantification, however, it has been criticised for not being Bayesian. In this work we propose one modification to the usual ensembling process that does result in Bayesian behaviour: regularising parameters about values drawn from a prior distribution. We provide theoretical support for this procedure as well as empirical evaluations on regression, image classification, and reinforcement learning problems. 

The paper can be found [here] and a snippet of the [code] used is available.

[here]: https://arxiv.org/abs/1810.05546
[code]: https://github.com/TeaPearce/Bayesian_NN_Ensembles
