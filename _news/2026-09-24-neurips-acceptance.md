---
layout: post
title: Paper accepted at NeurIPS 
date: 2026-09-24 10:00:00+0200
inline: false
related_posts: false
---

Our paper on Clustered Randomized Smoothing for Stochastic Prediction Functions was accepted at NeurIPS 2026. 
Randomized smoothing has emerged as a powerful technique for robustify predictors of all kinds, _with formal guarantees_. 
However, in contexts where the prediction is multi-modal, either by the induced distribution or inherently, we identified a core issue that the averaging results in _mode collapse_. As an example, a robot navigating around an obstacle might go either way, but the average behaviour is to navigate directly towards the obstacle. To address this, we propose clustered randomized smoothing: first cluster the samples of the prediction then perform smoothing locally inside each cluster. The smoothing maintains formal guarantees, now with respect to all clusters.

Thanks to all collaborators, reviewers, and ACs!