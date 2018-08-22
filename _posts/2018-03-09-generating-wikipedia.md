---
layout: post
title:  "Generating Wikipedia by Summarizing Long Sequences"
date:   2018-03-09
categories: paper
---

This paper is less applicable to physics than those dicussed previously, but it is an interesting read.

# Abstract

> We show that generating English Wikipedia articles can be approached as a multi- document summarization of source documents. We use extractive summarization to coarsely identify salient information and a neural abstractive model to generate the article. For the abstractive model, we introduce a decoder-only architecture that can scalably attend to very long sequences, much longer than typical encoder- decoder architectures used in sequence transduction. We show that this model can generate fluent, coherent multi-sentence paragraphs and even whole Wikipedia articles. When given reference documents, we show it can extract relevant factual information as reflected in perplexity, ROUGE scores and human evaluations. 

Link to the [paper] and [code] that was later released.

[paper]: https://arxiv.org/abs/1801.10198
[code]: https://github.com/tensorflow/tensor2tensor/tree/master/tensor2tensor/data_generators/wikisum
