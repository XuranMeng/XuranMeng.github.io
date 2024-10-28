---
title: "Initialization Matters: On the Benign Overfitting of Two-Layer ReLU CNN with Fully Trainable Layers."
collection: publications
category: preprints
permalink: /publication/twolayer
excerpt: 'Submitted to JASA'
date: 2024-10-24
venue: 'Arxiv'
#slidesurl: 'http://academicpages.github.io/files/slides3.pdf'
paperurl: 'https://arxiv.org/pdf/2410.19139'
citation: 'Shuning Shang, <b>Xuran Meng</b>, Yuan Cao and Difan Zou, &quot;Initialization Matters: On the Benign Overfitting of Two-Layer ReLU CNN with Fully Trainable Layers.&quot; <i>arxiv: 2410.19139</i>, 2024.'
---
Benign overfitting refers to how over-parameterized neural networks can fit training data perfectly and generalize well to unseen data. While this has been widely investigated theoretically, existing works are limited to two-layer networks with fixed output layers, where only the hidden weights are trained. We extend the analysis to two-layer ReLU convolutional neural networks (CNNs) with fully trainable layers, which is closer to the practice. Our results show that the initialization scaling of the output layer is crucial to the training dynamics: large scales make the model training behave similarly to that with the fixed output, the hidden layer grows rapidly while the output layer remains largely unchanged; in contrast, small scales result in more complex layer interactions, the hidden layer initially grows to a specific ratio relative to the output layer, after which both layers jointly grow and maintain that ratio throughout training.
Furthermore, in both settings, we provide nearly matching upper and lower bounds on the test errors, identifying the sharp conditions on the initialization scaling and signal-to-noise ratio (SNR) in which the benign overfitting can be achieved or not. Numerical experiments back up the theoretical results.
