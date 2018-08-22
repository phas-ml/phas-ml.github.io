---
layout: post
title:  "Neural Processes"
date:   2018-08-03
categories: paper
---

At this reading group we discussed a proposed combination of neural networks and gaussian processes.
# Abstract

> A neural network (NN) is a parameterised function that can be tuned via gradient descent to approximate a labelled collection of data with high precision. A Gaussian process (GP), on the other hand, is a probabilistic model that defines a distribution over possible functions, and is updated in light of data via the rules of probabilistic inference. GPs are probabilistic, data-efficient and flexible, however they are also computationally intensive and thus limited in their applicability. We introduce a class of neural latent variable models which we call Neural Processes (NPs), combining the best of both worlds. Like GPs, NPs define distributions over functions, are capable of rapid adaptation to new observations, and can estimate the uncertainty in their predictions. Like NNs, NPs are computationally efficient during training and evaluation but also learn to adapt their priors to data. We demonstrate the performance of NPs on a range of learning tasks, including regression and optimisation, and compare and contrast with related models in the literature. 


Here is the link to the [paper].

For those looking for quick introduction or refresher on gaussain processes, have a look at this [blog-post]


[paper]: https://arxiv.org/abs/1807.01622
[blog-post]: http://katbailey.github.io/post/gaussian-processes-for-dummies/
