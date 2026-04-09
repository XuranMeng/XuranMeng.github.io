---
title: "Beyond Consistency: Inference for the Relative Risk Functional in Deep Nonparametric Cox Models."
collection: publications
category: preprints
permalink: /publication/beyondconsistency
date: 2026-03-01
venue: 'Arxiv'
paperurl: 'https://arxiv.org/pdf/2603.23835'
citation: 'Sattwik Ghosal, <b>Xuran Meng</b> and Yi Li, '
---
There remain theoretical gaps in deep neural network estimators for the nonparametric Cox proportional hazards model. In particular, it is unclear how gradient-based optimization error propagates to population risk under partial likelihood, how pointwise bias can be controlled to permit valid inference, and how ensemble-based uncertainty quantification behaves under realistic variance decay regimes. We develop an asymptotic distribution theory for deep Cox estimators that addresses these issues. First, we establish nonasymptotic oracle inequalities for general trained networks that link in-sample optimization error to population risk without requiring the exact empirical risk optimizer. We then construct a structured neural parameterization that achieves infinity-norm approximation rates compatible with the oracle bound, yielding control of the pointwise bias. Under these conditions and using the Hajek--Hoeffding projection, we prove pointwise and multivariate asymptotic normality for subsampled ensemble estimators. We derive a range of subsample sizes that balances bias correction with the requirement that the Hajek--Hoeffding projection remain dominant. This range accommodates decay conditions on the single-overlap covariance, which measures how strongly a single shared observation influences the estimator, and is weaker than those imposed in the subsampling literature. An infinitesimal jackknife representation provides analytic covariance estimation and valid Wald-type inference for relative risk contrasts such as log-hazard ratios. Finally, we illustrate the finite-sample implications of the theory through simulations and a real data application.
