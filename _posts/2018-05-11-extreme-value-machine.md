---
layout: post
title:  "The Extreme Value Machine"
date:   2018-05-11
categories: paper
---

At this reading group we discussed a novel classifier derived from incremental learning. This classifier allows for new unseen classes to be indentified in the testing stage.

# Abstract

> It is often desirable to be able to recognize when inputs to a recognition function learned in a supervised manner correspond to classes unseen at training time. With this ability, new class labels could be assigned to these inputs by a human operator, allowing them to be incorporated into the recognition function --- ideally under an efficient incremental update mechanism. While good algorithms that assume inputs from a fixed set of classes exist, e.g., artificial neural networks and kernel machines, it is not immediately obvious how to extend them to perform incremental learning in the presence of unknown query classes. Existing algorithms take little to no distributional information into account when learning recognition functions and lack a strong theoretical foundation. We address this gap by formulating a novel, theoretically sound classifier --- the Extreme Value Machine (EVM). The EVM has a well-grounded interpretation derived from statistical Extreme Value Theory (EVT), and is the first classifier to be able to perform nonlinear kernel-free variable bandwidth incremental learning. Compared to other classifiers in the same deep network derived feature space, the EVM is accurate and efficient on an established benchmark partition of the ImageNet dataset.


Here is the link to the [paper] and the [source code].

[paper]: https://arxiv.org/abs/1506.06112
[source code]:  https://github.com/EMRResearch/ExtremeValueMachine
