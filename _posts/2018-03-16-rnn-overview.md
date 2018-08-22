---
layout: post
title:  "Overview of RNN architectures"
date:   2018-03-16
categories: overview
---

This reading group took a different structure to those held previously. Following the network proposed in the [previous paper], we discussed three of the most commonly used RNN architectures and which might be best suited to the time-series based analysis carried out by those of us working on gravitational waves.

The three papers were:

# WaveNet: A Generative Model for Raw Audio

This paper was discussed previously as one of the [meetings][wavenet-meeting].

# Attention Is All You Need

This is the attention based architecture that was mentioned in the previous [meeting][previous paper].



# Learning to Forget: Continual Prediction with LSTM

This paper presents the non-original, but more widely used version of Long-Short-Term-Memory (LSTM) and has not been discussed previously.

## Abstract 

> Long short-term memory (LSTM; Hochreiter & Schmidhuber, 1997) can solve numerous tasks not solvable by previous learning algorithms for recurrent neural networks (RNNs). We identify a weakness of LSTM networks processing continual input streams that are not a priori segmented into subsequences with explicitly marked ends at which the network's internal state could be reset. Without resets, the state may grow indefinitely and eventually cause the network to break down. Our remedy is a novel, adaptive "forget gate" that enables an LSTM cell to learn to reset itself at appropriate times, thus releasing internal resources. We review illustrative benchmark problems on which standard LSTM outperforms other RNN algorithms. All algorithms (including LSTM) fail to solve continual versions of these problems. LSTM with forget gates, however, easily solves them, and in an elegant way.

Link to the [paper][lstm].

[previous paper]: _posts/2018-03-09-generating-wikipedia.md
[wavenet-meeting]: _posts/2017-12-01-wavenet.markdown
[lstm]: http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.55.5709
