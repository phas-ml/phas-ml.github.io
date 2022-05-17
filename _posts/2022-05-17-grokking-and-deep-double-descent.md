---
layout: post
title:  "Grokking & Deep Double Descent"
date:   2022-05-17
categories: paper
speaker: Joe Bayley
---

The focus of this meeting was on how to train neural networks, specifically how training past overfitting can sometimes lead to better performance. We discussed two papers: Grokking: Generalization Beyond Overfitting on Small Algorithmic Datasets and Deep Double Descent: Where Bigger Models and More Data Hurt.

## Abstract - Grokking: Generalization Beyond Overfitting on Small Algorithmic Datasets

> In this paper we propose to study generalization of neural networks on small algorithmically generated datasets. In this setting, questions about data efficiency, memorization, generalization, and speed of learning can be studied in great detail. In some situations we show that neural networks learn through a process of "grokking" a pattern in the data, improving generalization performance from random chance level to perfect generalization, and that this improvement in generalization can happen well past the point of overfitting. We also study generalization as a function of dataset size and find that smaller datasets require increasing amounts of optimization for generalization. We argue that these datasets provide a fertile ground for studying a poorly understood aspect of deep learning: generalization of overparametrized neural networks beyond memorization of the finite training dataset.

## Abstract - Deep Double Descent: Where Bigger Models and More Data Hurt

> We show that a variety of modern deep learning tasks exhibit a "double-descent" phenomenon where, as we increase model size, performance first gets worse and then gets better. Moreover, we show that double descent occurs not just as a function of model size, but also as a function of the number of training epochs. We unify the above phenomena by defining a new complexity measure we call the effective model complexity and conjecture a generalized double descent with respect to this measure. Furthermore, our notion of model complexity allows us to identify certain regimes where increasing (even quadrupling) the number of train samples actually hurts test performance.

## Links

* Improving Generalization Performance by Switching from Adam to SGDGrokking: Generalization Beyond Overfitting on Small Algorithmic Datasets - [arXiv](https://arxiv.org/abs/2201.02177)
* Deep Double Descent: Where Bigger Models and More Data Hurt - [arXiv](https://arxiv.org/abs/1912.02292)
