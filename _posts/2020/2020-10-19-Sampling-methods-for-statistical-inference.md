---
date: 2020-10-19T20:00:00.000Z
layout: post
title: Sampling methods for statistical inference
subtitle: Several important sampling methods used in Bayesian statistics
description: >-
  Several important sampling methods used in Bayesian statistics
image: >-
  https://res.cloudinary.com/dthouk4zq/image/upload/v1603209729/gibs_mo5e0b.gif
optimized_image: >-
  https://res.cloudinary.com/dthouk4zq/image/upload/c_scale,w_380/v1603209729/gibs_mo5e0b.gif
category: Statistical Learning
tags:
  - Statistics
  - Bayesian Statistics
  - Statistical Learning
  - Machine Learning
author: Jinhwan-Suk
---

### Video 
<iframe width="560" height="315" src="https://www.youtube.com/embed/Ou7GOEP7aI0" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Main obstacles of Bayesian statistics or Bayesian machine learning is computing posterior distribution. In many contexts, computing posterior distribution is intractable. Today, there are two main stream to detour directly computing posterior distribution. One is using sampling method(ex. MCMC) and another is Variational inference. Compared to Variational inference, MCMC takes more time and vulnerable to high-dimensional parameters. However, MCMC has strength in simplicity and guarantees of convergence. I'll briefly introduce several methods people using in application.