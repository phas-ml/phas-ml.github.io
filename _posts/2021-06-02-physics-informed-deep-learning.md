---
layout: post
title:  "Physics Informed Deep Learning (Part I): Data-driven Solutions of Nonlinear Partial Differential Equations"
date:   2021-06-02
categories: paper
speaker: John Veitch
---

This paper outlines how including knowledge about physics can improve the results when considering partial differential equations. In particular, the paper presents two methods for solving PDEs using neural networks, one considering continuous time models and the other considering discrete time models. Both are applied to range of PDEs including Burger's equation and Schrödinger's equation.


# Abstract

> We introduce physics informed neural networks -- neural networks that are trained to solve supervised learning tasks while respecting any given law of physics described by general nonlinear partial differential equations. In this two part treatise, we present our developments in the context of solving two main classes of problems: data-driven solution and data-driven discovery of partial differential equations. Depending on the nature and arrangement of the available data, we devise two distinct classes of algorithms, namely continuous time and discrete time models. The resulting neural networks form a new class of data-efficient universal function approximators that naturally encode any underlying physical laws as prior information. In this first part, we demonstrate how these networks can be used to infer solutions to partial differential equations, and obtain physics-informed surrogate models that are fully differentiable with respect to all input coordinates and free parameters. 


Paper available [here](https://arxiv.org/abs/1711.10561).
