---
title: "Statistical Inference on High Dimensional Gaussian Graphical Regression Models."
collection: publications
category: preprints
permalink: /publication/SAGE
excerpt: 'Submitted to Biometrics'
date: 2024-11-03
venue: 'Arxiv'
#slidesurl: 'http://academicpages.github.io/files/slides3.pdf'
paperurl: 'http://arxiv.org/abs/2411.01588'
citation: '<b>Xuran Meng</b>, Jingfei Zhang and Yi Li, &quot;Statistical Inference on High Dimensional Gaussian Graphical Regression Models.&quot; <i>arxiv: 2411.01588</i>, 2024.'
---
Gaussian graphical regressions have emerged as a powerful approach for regressing the precision matrix of a Gaussian graphical model on covariates, which, unlike traditional Gaussian graphical models, can help determine how graphs are modulated by high dimensional subject-level covariates, and recover both the population-level and subject-level graphs. To fit the model, a multi-task learning approach achieves lower error rates compared to node-wise regressions. However, due to the high complexity and dimensionality of the Gaussian graphical regression problem, the important task of statistical inference remains unexplored. We propose a class of debiased estimators based on multi-task learners for statistical inference in Gaussian graphical regressions. We show that debiasing can be performed quickly and separately for the multi-task learners. In a key debiasing step that estimates the inverse covariance matrix, we propose a novel projection technique that dramatically reduces computational costs in optimization to scale only with the sample size $n$. We show that our debiased estimators enjoy a fast convergence rate and asymptotically follow a normal distribution, enabling valid statistical inference such as constructing confidence intervals and performing hypothesis testing. Simulation studies confirm the practical utility of the proposed approach, and we further apply it to analyze gene co-expression graph data from a brain cancer study, revealing meaningful biological relationships. 
