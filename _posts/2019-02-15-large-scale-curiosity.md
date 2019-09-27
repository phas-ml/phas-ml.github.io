---
layout: post
title:  "Large Scale Curiosity"
date:   2019-02-15
categories: paper
speaker: Hunter Gabbard
---

At this journal club the paper we discussed was focused on a particular aspect of reinforcement learning. In particular it focuses on the rewards using for training the agent and how more extrinsic rewards can be effective.

# Abstract

Reinforcement learning algorithms rely on carefully engineering environment rewards that are extrinsic to the agent. However, annotating each environment with hand-designed, dense rewards is not scalable, motivating the need for developing reward functions that are intrinsic to the agent. Curiosity is a type of intrinsic reward function which uses prediction error as reward signal. In this paper: (a) We perform the first large-scale study of purely curiosity-driven learning, i.e. without any extrinsic rewards, across 54 standard benchmark environments, including the Atari game suite. Our results show surprisingly good performance, and a high degree of alignment between the intrinsic curiosity objective and the hand-designed extrinsic rewards of many game environments. (b) We investigate the effect of using different feature spaces for computing prediction error and show that random features are sufficient for many popular RL game benchmarks, but learned features appear to generalize better (e.g. to novel game levels in Super Mario Bros.). (c) We demonstrate limitations of the prediction-based rewards in stochastic setups. Game-play videos and code are at [this https URL]

The paper is available [here] and there is a general [post] that serves as an overview and links to several different resources.

[this https URL]: https://pathak22.github.io/large-scale-curiosity/
[here]: https://arxiv.org/abs/1808.04355
[post]: https://pathak22.github.io/large-scale-curiosity/
