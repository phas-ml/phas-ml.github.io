---
layout: post
title:  "Deep Leaning for Sampling from Arbitrary Probability Distributions"
date:   2018-08-17
categories: paper
---

At this reading group we discussed a proposed alternative to existing sampling methods based on a fully connected neural network.
After discussing the paper we concluded that some explanation is lacking and more details of the implementation would improve the
paper.

# Abstract

> Accurate noise modelling is important for training of deep learning reconstruction 
> algorithms. While noise models are well known for traditional imaging techniques,
> the noise distribution of a novel sensor may be difficult to determine a priori.
> Therefore, we propose learning arbitrary noise distributions. To do so, this paper 
> proposes a fully connected neural network model to map samples from a uniform distribution
> to samples of any explicitly known probability density function. During the training, 
> the Jensen-Shannon divergence between the distribution of the model's output and the target
> distribution is minimized. We experimentally demonstrate that our model converges towards 
> the desired state. It provides an alternative to existing sampling methods such as inversion 
> sampling, rejection sampling, Gaussian mixture models and Markov-Chain-Monte-Carlo. Our 
> model has high sampling efficiency and is easily applied to any probability distribution, 
> without the need of further analytical or numerical calculations. 

Link to the [paper].

[One of the references][other-paper] was interesting, it proposes a version of MCMC that incorporates a generative adversarial network (GAN). It may be worth discussing at a following meeting.

[paper]: https://arxiv.org/abs/1801.04211
[other-paper]: https://arxiv.org/abs/1706.07561
