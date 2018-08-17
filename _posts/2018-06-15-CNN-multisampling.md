---
layout: post
title:  "Improving the Resolution of CNN Feature Maps Efficiently with Multisampling"
date:   2018-06-15
categories: paper
---

At this reading group we discussed a modification to convolutional neural networks that uses an extra dimension to encode more information about the inputs.

# Abstract

> We describe a new class of subsampling techniques for CNNs, termed multisampling, that significantly increases the amount of information kept by feature maps through subsampling layers. One version of our method, which we call checkered subsampling, significantly improves the accuracy of state-of-the-art architectures such as DenseNet and ResNet without any additional parameters and, remarkably, improves the accuracy of certain pretrained ImageNet models without any training or fine-tuning. We glean new insight into the nature of data augmentations and demonstrate, for the first time, that coarse feature maps are significantly bottlenecking the performance of neural networks in image classification. 


Link to the [paper].

There is also an [implementation][code] of the paper in PyTorch.


[paper]: https://arxiv.org/abs/1805.10766
[code]: https://github.com/ShayanPersonal/checkered-cnn
