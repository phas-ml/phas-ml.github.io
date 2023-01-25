---
layout: post
title:  "Deep Residual Networks for Gravitational Wave Detection"
date:   2023-01-25
categories: paper
speaker: Narenraju Nagarajan
---

## Abstract

> Traditionally, gravitational waves are detected with techniques such as matched  ltering or unmodeled
searches based on wavelets. However, in the case of generic black hole binaries with
non-aligned spins, if one wants to explore the whole parameter space, matched  ltering can become
impractical, which sets severe restrictions on the sensitivity and computational e ciency of
gravitational-wave searches. Here, we use a novel combination of machine-learning algorithms and
arrive at sensitive distances that surpass traditional techniques in a speci c setting. Moreover, the
computational cost is only a small fraction of the computational cost of matched  ltering. The main
ingredients are a 54-layer deep residual network (ResNet), a Deep Adaptive Input Normalization
(DAIN), a dynamic dataset augmentation, and curriculum learning, based on an empirical relation
for the signal-to-noise ratio. We compare the algorithm's sensitivity with two traditional algorithms
on a dataset consisting of a large number of injected waveforms of non-aligned binary black hole
mergers in real LIGO O3a noise samples. Our machine-learning algorithm can be used in upcoming
rapid online searches of gravitational-wave events in a sizeable portion of the astrophysically
interesting parameter space. We make our code, AResGW, and detailed results publicly available
at https://github.com/vivinousi/gw-detection-deep-learning.

## Links

* Deep Residual Networks for Gravitational Wave Detection - [arXiv](https://arxiv.org/abs/2211.01520)
