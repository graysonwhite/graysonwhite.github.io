---
author: Jerzy A. Weiczorek, Grayson W. White, Zachariah W. Cody, Emily X. Tan, Jacqueline O. Chistolini, Kelly S. McConville, Tracey S. Frescino, and Gretchen G. Moisen
date: "2023-06-27"
draft: false
excerpt: arXiv preprint.
layout: single
title: >
  [preprint]: Assessing small area estimates via artificial populations from KBAABB: a kNN-based approximation to ABB
---

### Abstract

Comparing and evaluating small area estimation (SAE) models for a given application is inherently difficult. Typically, we do not have enough data in many areas to check unit-level modeling assumptions or to assess unit-level predictions empirically; and there is no ground truth available for checking area-level estimates. Design-based simulation from artificial populations can help with each of these issues, but only if the artificial populations (a) realistically represent the application at hand and (b) are not built using assumptions that could inherently favor one SAE model over another. In this paper, we borrow ideas from random hot deck, approximate Bayesian bootstrap (ABB), and k nearest neighbor (kNN) imputation methods, which are often used for multiple imputation of missing data. We propose a kNN-based approximation to ABB (KBAABB) for a different purpose: generating an artificial population when rich unit-level auxiliary data is available. We introduce diagnostic checks on the process of building the artificial population itself, and we demonstrate how to use such an artificial population for design-based simulation studies to compare and evaluate SAE models, using real data from the Forest Inventory and Analysis (FIA) program of the US Forest Service. We illustrate how such simulation studies may be disseminated and explored interactively through an online R Shiny application. 

### Access

This is a preprint that can be found [on arXiv.](https://arxiv.org/abs/2306.15607) 

