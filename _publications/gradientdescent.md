---
title: "Per-Example Gradient Regularization Improves Learning Signals from Noisy Data."
collection: publications
category: preprints
permalink: /publication/gradientdescent
excerpt: 'Submitted to Machine Learning'
date: 2023-03-27
venue: 'Arxiv'
#slidesurl: 'http://academicpages.github.io/files/slides2.pdf'
paperurl: 'https://arxiv.org/pdf/2303.17940'
citation: '<b>Xuran Meng</b>, Yuan Cao and Difan Zou, &quot;Per-Example Gradient Regularization Improves Learning Signals from Noisy Data.&quot; <i>arxiv:2303.17940</i>, 2023.'
---
Gradient regularization, as described in Barrett and Dherin (2021), is a highly effective technique for promoting flat minima during gradient descent. Empirical evidence suggests that this regularization technique can significantly enhance the robustness of deep learning models against noisy perturbations, while also reducing test error. In this paper, we explore the per- example gradient regularization (PEGR) and present a theoretical analysis that demonstrates its effectiveness in improving both test error and robustness against noise perturbations. Specifically, we adopt a signal-noise data model from Cao et al. (2022) and show that PEGR can learn signals effectively while suppressing noise. In contrast, standard gradient descent struggles to distinguish the signal from the noise, leading to suboptimal generalization performance. Our analysis reveals that PEGR penalizes the variance of pattern learning, thus effectively suppressing the memorization of noises from the training data. These findings underscore the importance of variance control in deep learning training and offer useful insights for developing more effective training approaches.
