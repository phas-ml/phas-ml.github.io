---
layout: post
title:  "AlphaFold: Improved protein structure prediction using potentials from deep learning"
date:   2021-03-10
categories: paper
speaker: Michael Williams
---

At this meeting we discussed the first AlphaFold which discusses a deep learning approach to solving the problem of protein folding.

# Abstract

> Protein structure prediction can be used to determine the three-dimensional shape of a protein from its amino acid sequence1. This problem is of fundamental importance as the structure of a protein largely determines its function2; however, protein structures can be difficult to determine experimentally. Considerable progress has recently been made by leveraging genetic information. It is possible to infer which amino acid residues are in contact by analysing covariation in homologous sequences, which aids in the prediction of protein structures3. Here we show that we can train a neural network to make accurate predictions of the distances between pairs of residues, which convey more information about the structure than contact predictions. Using this information, we construct a potential of mean force4 that can accurately describe the shape of a protein. We find that the resulting potential can be optimized by a simple gradient descent algorithm to generate structures without complex sampling procedures. The resulting system, named AlphaFold, achieves high accuracy, even for sequences with fewer homologous sequences. In the recent Critical Assessment of Protein Structure Prediction5 (CASP13)—a blind assessment of the state of the field—AlphaFold created high-accuracy structures (with template modelling (TM) scores6 of 0.7 or higher) for 24 out of 43 free modelling domains, whereas the next best method, which used sampling and contact information, achieved such accuracy for only 14 out of 43 domains. AlphaFold represents a considerable advance in protein-structure prediction. We expect this increased accuracy to enable insights into the function and malfunction of proteins, especially in cases for which no structures for homologous proteins have been experimentally determined7. 

Paper link [here](https://www.nature.com/articles/s41586-019-1923-7)


