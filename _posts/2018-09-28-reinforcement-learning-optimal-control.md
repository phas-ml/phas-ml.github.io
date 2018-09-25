---
layout: post
title:  "Estimation and Control Using Sampling-Based Bayesian Reinforcement Learning"
date:   2018-09-28
categories: paper
---

At this reading group we discussed ways to do the optimal control with the Reinforcement Learning.

# Abstract

>Robots performing manipulation tasks must operate
>under uncertainty about both their pose and the dynamics
>of the system. In order to remain robust to modeling error and
>shifts in payload dynamics, agents must simultaneously perform
>estimation and control tasks. However, the optimal estimation
>actions are often not the optimal actions for accomplishing
>the control tasks, and thus agents trade between exploration
>and exploitation. This work frames the problem as a Bayesadaptive
>Markov decision process and solves it online using
>Monte Carlo tree search and an extended Kalman filter to
>handle Gaussian process noise and parameter uncertainty in a
>continuous space. MCTS selects control actions to reduce model
>uncertainty and reach the goal state nearly optimally. Certainty
>equivalent model predictive control is used as a benchmark to
>compare performance in simulations with varying process noise
>and parameter uncertainty.

Here is the link to the [paper]. 

[paper]: https://arxiv.org/abs/1808.00888
