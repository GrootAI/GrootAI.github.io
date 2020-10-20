---
date: 2020-10-17T17:14:05.000Z
layout: post
title: Active Learning for Community Detection in Stochastic Block Models
subtitle: Is community recovery possible even when D(a, b) < 1 in a symmetric SBM environment?
description: Is community recovery possible even when D(a, b) < 1 in a symmetric SBM environment?
image: >-
  https://res.cloudinary.com/dthouk4zq/image/upload/v1602922548/active_iigsos.png
optimized_image: >-
  https://res.cloudinary.com/dthouk4zq/image/upload/c_scale,w_380/v1602922548/active_iigsos.png
category: Statistical Learning
tags:
  - Stochastic Block Model
  - Statistical Learning
  - Active Learning
author: Kyuyong-Shin
---

### Video 
<iframe width="560" height="315" src="https://www.youtube.com/embed/pRl08WcIWKo" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

It was recently shown that recovering the community membership (or label) of every node with high probability (w.h.p.) using only the graph is possible if and only if the 𝐶ℎ𝑒𝑟𝑛𝑜𝑓𝑓−𝐻𝑒𝑙𝑙𝑖𝑛𝑔𝑒𝑟 (𝐶𝐻) 𝑑𝑖𝑣𝑒𝑟𝑔𝑒𝑛𝑐𝑒 𝐷(𝑎, 𝑏) =(√𝑎−√𝑏 )^2≥1. An algorithm to obtain a strongly consistent labeling under the assumption 𝐷 ≥ 1 is given in [Mossel et al 2016]

In this work, we study if, and by how much, community detection below the clustering threshold (i.e. 𝐷(𝑎, 𝑏)<1) is possible by querying (i.e., active learning) the labels of a vanishingly small fraction of carefully selected nodes (i.e., 𝑜(𝑛) number of nodes).

This paper suggests a bound on the number of observations (or samples) required as well as an algorithm which specifies which nodes to sample.