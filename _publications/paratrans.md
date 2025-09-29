---
title: "Towards Understanding Feature Learning in Parameter Transfer."
collection: publications
category: preprints
permalink: /publication/paratrans
date: 2025-9-27
excerpt: 'Submitted to ICLR'
venue: 'Arxiv'
#slidesurl: 'http://academicpages.github.io/files/slides3.pdf'
paperurl: 'https://arxiv.org/pdf/2509.22056'
citation: 'Yuan hua, <b>Xuran Meng</b> et. al., &quot;Towards Understanding Feature Learning in Parameter Transfer.&quot; <i>arxiv: 2509.22056</i>, 2025.'
---
Parameter transfer is a central paradigm in transfer learning, enabling knowledge reuse across tasks and domains by sharing model parameters between upstream and downstream models. However, when only a subset of parameters from the upstream model is transferred to the downstream model, there remains a lack of theoretical understanding of the conditions under which such partial parameter reuse is beneficial and of the factors that govern its effectiveness. To address this gap, we analyze a setting in which both the upstream and downstream models are ReLU convolutional neural networks (CNNs). Within this theoretical framework, we characterize how the inherited parameters act as carriers of universal knowledge and identify key factors that amplify their beneficial impact on the target task. Furthermore, our analysis provides insight into why, in certain cases, transferring parameters can lead to lower test accuracy on the target task than training a new model from scratch. Numerical experiments and real-world data experiments are conducted to empirically validate our theoretical findings.
