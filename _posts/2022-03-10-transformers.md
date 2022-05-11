---
layout: post
title:  "Attention Is All You Need"
date:   2022-03-10
categories: paper
speaker: Natalia Korsakova
---

Attention has been mentioned in previous but we've never actually discussed the paper that originally proposed it. In this meeting we discussed said paper and a couple of blog posts that included some useful illustrations.

## Abstract

> The dominant sequence transduction models are based on complex recurrent or convolutional neural networks in an encoder-decoder configuration. The best performing models also connect the encoder and decoder through an attention mechanism. We propose a new simple network architecture, the Transformer, based solely on attention mechanisms, dispensing with recurrence and convolutions entirely. Experiments on two machine translation tasks show these models to be superior in quality while being more parallelizable and requiring significantly less time to train. Our model achieves 28.4 BLEU on the WMT 2014 English-to-German translation task, improving over the existing best results, including ensembles by over 2 BLEU. On the WMT 2014 English-to-French translation task, our model establishes a new single-model state-of-the-art BLEU score of 41.8 after training for 3.5 days on eight GPUs, a small fraction of the training costs of the best models from the literature. We show that the Transformer generalizes well to other tasks by applying it successfully to English constituency parsing both with large and limited training data.

## Links

* Attention Is All You Need - [arXiv](https://arxiv.org/abs/1706.03762) - [Annotated](https://nlp.seas.harvard.edu/2018/04/03/attention.html)
* The Illustrated Transformer - [Blog post](https://jalammar.github.io/illustrated-transformer/)
* Illustrated Guide to Transformers - [Blog post](https://towardsdatascience.com/illustrated-guide-to-transformers-step-by-step-explanation-f74876522bc0)
