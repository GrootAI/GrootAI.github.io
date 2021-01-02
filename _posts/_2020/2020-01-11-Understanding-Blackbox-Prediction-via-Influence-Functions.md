---
date: 2020-01-11 12:00:00
layout: post
title: Understanding Blackbox Prediction via Influence Functions
subtitle: Why did the system make this prediction? How can we explain where the model came from?
description: Why did the system make this prediction? How can we explain where the model came from?
optimized_image: https://res.cloudinary.com/dfnkx5mr1/image/upload/c_fit,h_200,q_100,w_380/v1602307780/post_img/3D-black-box-artificial-intelligence-interviews-shutterstock-489987685_p014pw.jpg
category: XAI
tags:
  - XAI
author: Kyuyong-Shin
---

### Video
<iframe width="560" height="315" src="https://www.youtube.com/embed/sYoJ3V5NmMY" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Slide 
<iframe src="//www.slideshare.net/slideshow/embed_code/key/uv0Z9ukp85Rx4J" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:0px; margin-bottom:5px; max-width: 100%;" allowfullscreen> </iframe> 

In this paper, they tackle this question by tracing a model’s predictions through its learning algorithm and back to the training data, where the model parameters ultimately derive from.

They use inﬂuence functions, a classic technique from robust statistics (Cook & Weisberg, 1980) that tells us how the model parameters change as we upweight a training point by an inﬁnitesimal amount.