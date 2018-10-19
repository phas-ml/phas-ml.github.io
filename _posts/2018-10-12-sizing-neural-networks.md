---
layout: post
title:  "A Practical Approach to Sizing Neural Networks"
date:   2018-10-12
categories: paper
---

At this meeting we discussed a paper that aimed to quantify the capacity of neural networks in bits. 

# Abstract

>Memorization is worst-case generalization. Based on MacKay's information theoretic model of supervised machine learning, this article discusses how to practically estimate the maximum size of a neural network given a training data set. First, we present four easily applicable rules to analytically determine the capacity of neural network architectures. This allows the comparison of the efficiency of different network architectures independently of a task. Second, we introduce and experimentally validate a heuristic method to estimate the neural network capacity requirement for a given dataset and labeling. This allows an estimate of the required size of a neural network for a given problem. We conclude the article with a discussion on the consequences of sizing the network wrongly, which includes both increased computation effort for training as well as reduced generalization capability.


The [paper] presents four "engineering rules" for perceptrons that it later justifies. They then derive a method for determining the size of the neural network requiered to completely represent a dataset. The approach is limited to multi-layer perceptron networks, but if it could be extended to other types (e.g. CNN) could be useful for some of the groups work.

The code is included in a [git repository], but at this time isn't clearly documented. The authors also wrote a [version of Tensorflow playground][tfmeter] that shows network capacity.

[paper]: https://arxiv.org/abs/1810.02328
[git repository]: https://github.com/fractor/nntailoring
[tfmeter]: http://tfmeter.icsi.berkeley.edu
