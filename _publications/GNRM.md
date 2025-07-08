---
title: "Inferring Outcome Means of Exponential Family Distributions Estimated by Deep Neural Networks."
collection: publications
category: preprints
permalink: /publication/GNRM
excerpt: 'Submitted to AOS'
date: 2025-04-12
venue: 'Arxiv'
#slidesurl: 'http://academicpages.github.io/files/slides3.pdf'
paperurl: 'https://arxiv.org/pdf/2504.09347'
citation: '<b>Xuran Meng</b> and Yi Li, &quot;Inferring Outcome Means of Exponential Family Distributions Estimated by Deep Neural Networks.&quot; <i>arxiv: 2504.09347</i>, 2025.'
---
Despite the widespread use of deep neural networks (DNNs) for prediction, inference on estimated means for categorical or exponential family outcomes remains underexplored. We address this gap by framing the problem within the generalized linear models (GLMs) framework and developing a rigorous statistical approach for inference on DNN-estimated means. To address a key limitation of assuming independence between prediction errors and input variables in the literature, which often fails in GLMs, we introduce a truncation technique that partitions the problem into regimes with distinct noise behaviors, enabling refined analysis and robust theoretical guarantees under general GLM frameworks. To implement inference, we consider an Ensemble Subsampling Method (ESM) that leverages U-statistics and the Hoeffding decomposition to construct reliable confidence intervals. This method enables model-free variance estimation and accounts for heterogeneity among individuals in the population. Through extensive simulations across Binary, Poisson and Binomial models, we demonstrate the effectiveness and efficiency of our method. We further apply the method to real-world data from the eICU dataset to predict patient readmission risks, providing actionable insights for clinical decision-making.

