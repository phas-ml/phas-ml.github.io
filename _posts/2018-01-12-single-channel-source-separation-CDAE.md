---
layout: post
title:  "Single Channel Audio Source Separation using Convolutional Denoising Autoencoders"
date:   2018-01-12
categories: paper
---

At this reading group we discussed a proposed method for signal seperation using Convoultional Denoising Autoencoders. This paper uses the method for extracting individual instruments from a piece music. Such a problem is comparable to source seperation in LISA and aLISA.

> Deep learning techniques have been used recently to tackle the audio source separation problem. In this work, we propose to use deep fully convolutional denoising autoencoders (CDAEs) for monaural audio source separation. We use as many CDAEs as the number of sources to be separated from the mixed signal. Each CDAE is trained to separate one source and treats the other sources as background noise. The main idea is to allow each CDAE to learn suitable spectral-temporal filters and features to its corresponding source. Our experimental results show that CDAEs perform source separation slightly better than the deep feedforward neural networks (FNNs) even with fewer parameters than FNNs.


Here is the link to the [paper]. 


[paper]: https://arxiv.org/abs/1703.08019
