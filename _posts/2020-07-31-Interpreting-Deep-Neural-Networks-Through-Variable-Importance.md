---
date: 2020-07-31T23:48:05.000Z
layout: post
title: Interpreting Deep Neural Networks Through Variable Importance
subtitle: Given a trained model, which features are the most important?
description: Given a trained model, which features are the most important?
image: >-
  https://res.cloudinary.com/dthouk4zq/image/upload/v1602333954/bayes_nn_nqurjs.png
optimized_image: >-
  https://res.cloudinary.com/dthouk4zq/image/upload/c_scale,w_380/v1602333954/bayes_nn_nqurjs.png
category: XAI
tags:
  - XAI
  - Statistical Learning
author: Kyuyong-Shin
---

### Video
<iframe width="560" height="315" src="https://www.youtube.com/embed/vWCpziECyAw" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Variable importance is one possible approach to achieve global interpretability, where the goal is to rank each input feature based on its contributions to predictive accuracy. This is in contrast to local interpretability, which aims to simply provide an explanation behind a specific prediction or group of predictions. 


Here, This paper describes an approach to achieve global interpretability for deep neural networks using “RelATive cEntrality” (RATE), a recently-proposed variable importance criterion for Bayesian models (Gaussian process regression).  


Furthermore, they present a unified framework under which RATE can be applied to deep neural networks and propose GroupRATE for ranking groups of variables. 

