---
layout: post
title:  "Being Bayesian, Even Just a Bit, Fixes Overconfidence in ReLU Networks"
date:   2020-11-02
categories: paper
speaker: Michael Williams
---

At this meeting we discussed *Being Bayesian, Even Just a Bit, Fixes Overconfidence in ReLU Networks*. We used this opportunity to discuss uncertaining in the neural networks. This paper provides a simple approach to reduce overconfidence without using a complete Bayesian Neural Network.


# Abstract

> The point estimates of ReLU classification networks---arguably the most widely used neural network architecture---have been shown to yield arbitrarily high confidence far away from the training data. This architecture, in conjunction with a maximum a posteriori estimation scheme, is thus not calibrated nor robust. Approximate Bayesian inference has been empirically demonstrated to improve predictive uncertainty in neural networks, although the theoretical analysis of such Bayesian approximations is limited. We theoretically analyze approximate Gaussian distributions on the weights of ReLU networks and show that they fix the overconfidence problem. Furthermore, we show that even a simplistic, thus cheap, Bayesian approximation, also fixes these issues. This indicates that a sufficient condition for a calibrated uncertainty on a ReLU network is "to be a bit Bayesian". These theoretical results validate the usage of last-layer Bayesian approximation and motivate a range of a fidelity-cost trade-off. We further validate these findings empirically via various standard experiments using common deep ReLU networks and Laplace approximations.

Paper link [here](https://arxiv.org/abs/2002.10118v2)
