---
layout: post
title:  "Alpha Go Zero: Mastering the game of Go without human knowledge"
date:   2017-12-01
categories: paper
---

The article introduces Alpha Go Zero (based off of the first algorithm to defeat a world champion at the notoriously complex game of Go). Whereas previous versions of Alpha Go were trained on many thousands of pre-played human games, Alpha Go Zero is simply given the rules of Go and then told to play consecutive random games against itself. This is very exciting because the algorithm is essentially it's own teacher and is not necessarily constrained by the limits of human knowledge (minimum level of supervision). 

# Abstract

> A long-standing goal of artificial intelligence is an algorithm that learns, tabula rasa, superhuman proficiency in challenging domains. Recently, AlphaGo became the first program to defeat a world champion in the game of Go. The tree search in AlphaGo evaluated positions and selected moves using deep neural networks. These neural networks were trained by supervised learning from human expert moves, and by reinforcement learning from self-play. Here we introduce an algorithm based solely on reinforcement learning, without human data, guidance or domain knowledge beyond game rules. AlphaGo becomes its own teacher: a neural network is trained to predict AlphaGo’s own move selections and also the winner of AlphaGo’s games. This neural network improves the strength of the tree search, resulting in higher quality move selection and stronger self-play in the next iteration. Starting tabula rasa, our new program AlphaGo Zero achieved superhuman performance, winning 100–0 against the previously published, champion-defeating AlphaGo.

Here is the link to the [paper] and the [blog-post]

[paper]: https://www.nature.com/articles/nature24270
[blog-post]: https://deepmind.com/blog/alphago-zero-learning-scratch/
