---
layout: post
title:  "Latent distributions in normalisig flows"
date:   2022-06-14
categories: paper
speaker: Michael J. Williams
---

The focus of this meeting was the importance of the latent distribution in normalising flows and how the choice of distribution limits imposes certain theoretical limits on a flow. We discussed two papers on the topic: the first proposes using a Student-t distribution for the latent distribution and the second discusses how the tails of the latent distribution can limit what the flow can learn.

## Abstract - Robust model training and generalisation with Studentising flows

> Normalising flows are tractable probabilistic models that leverage the power of deep learning to describe a wide parametric family of distributions, all while remaining trainable using maximum likelihood. We discuss how these methods can be further improved based on insights from robust (in particular, resistant) statistics. Specifically, we propose to endow flow-based models with fat-tailed latent distributions such as multivariate Student's t, as a simple drop-in replacement for the Gaussian distribution used by conventional normalising flows. While robustness brings many advantages, this paper explores two of them: 1) We describe how using fatter-tailed base distributions can give benefits similar to gradient clipping, but without compromising the asymptotic consistency of the method. 2) We also discuss how robust ideas lead to models with reduced generalisation gap and improved held-out data likelihood. Experiments on several different datasets confirm the efficacy of the proposed approach in both regards.  

## Abstract - Tails of Lipschitz Triangular Flows

> We investigate the ability of popular flow based methods to capture tail-properties of a target density by studying the increasing triangular maps used in these flow methods acting on a tractable source density. We show that the density quantile functions of the source and target density provide a precise characterization of the slope of transformation required to capture tails in a target density. We further show that any Lipschitz-continuous transport map acting on a source density will result in a density with similar tail properties as the source, highlighting the trade-off between a complex source density and a sufficiently expressive transformation to capture desirable properties of a target density. Subsequently, we illustrate that flow models like Real-NVP, MAF, and Glow as implemented originally lack the ability to capture a distribution with non-Gaussian tails. We circumvent this problem by proposing tail-adaptive flows consisting of a source distribution that can be learned simultaneously with the triangular map to capture tail-properties of a target density. We perform several synthetic and real-world experiments to compliment our theoretical findings.  

## Links

* Robust model training and generalisation with Studentising flows - [arXiv](https://arxiv.org/abs/2006.06599)
* Tails of Lipschitz Triangular Flows - [arXiv](https://arxiv.org/abs/1907.04481)
