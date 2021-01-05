---
date: 2021-01-05T01:50:00.000Z
layout: post
title: Wide Open Spaces&#58; A Statistical Technique for Measuring Space Creation in Professional Soccer
subtitle: This paper presents a method for quantifying spatial value occupation and generation during open play.
description: This paper presents a method for quantifying spatial value occupation and generation during open play.
image: https://res.cloudinary.com/dthouk4zq/image/upload/v1609833860/soccer_cexzcp.png
optimized_image: https://res.cloudinary.com/dthouk4zq/image/upload/c_limit,h_200,w_380/v1609833860/soccer_cexzcp.png
category: Machine Learning
tags:
  - Machine Learning
  - Sports Analysis
author: Munjun-Hwang
---

### Video
<iframe width="560" height="315" src="https://www.youtube.com/embed/sCB41ePNl9Y" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### References
Sports analytics has long focused on the outcomes of discrete, on-ball events. 
Whether a player is good or not mostly depends on statistics from on-ball events. 
However, much of the sport’s complexity resides in off-ball events because only one player can possess the ball during a play, and other teammates move without the ball to create a space for increasing scoring chances efficiently. The creation and closure of spaces is a recurrent subject in observation-based tactical analysis, yet it remains highly unexplored from a quantitative perspective.

This paper presents a method for quantifying spatial value occupation and generation during open play. Here direct space occupation refers to space created for oneself, 
while space generation refers to opening up space for teammates by attracting opponents out of position. The study builds a novel parametric pitch control model that incorporates motion information, relative distance to the ball, and player position in order to provide a smooth surface of potential ball control. A Model is also constructed for the relative value of any pitch position, based on the position of the ball and using feed forward neural networks. From all this (a player’s invested pitch zones, a team’s pitch control, and the relative value of each zone), The study employ the full spatio-temporal dynamics of each player to construct two novel spatial value creation metrics, accounting for both occupation and generation of spaces.