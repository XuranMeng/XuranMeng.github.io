---
title: "Transformer learns optimal variable selection in group-sparse classification."
collection: publications
category: conferences
permalink: /publication/transformergroupsparse
excerpt: ' '
date: 2025-02-28
venue: ' International Conference on Learning Representations'
paperurl: 'https://openreview.net/pdf?id=fuoM5YDBX4'
citation: 'Chenyang Zhang, <b>Xuran Meng</b> and Yuan Cao, &quot;Transformer learns optimal variable selection in group-sparse classification.&quot; <i>ICLR</i>, 2025.'
---
Transformers have demonstrated remarkable success across various applications. However, the success of transformers have not been understood in theory.  In this work, we give a case study of how transformers can be trained to learn a classic statistical model with ``group sparsity'', where the input variables form multiple groups, and the label only depends on the variables from one of the groups. We theoretically demonstrate that, a one-layer transformer trained by gradient descent can correctly leverage the attention mechanism to select variables, disregarding irrelevant ones and focusing on those beneficial for classification. We also demonstrate that a well-pretrained one-layer transformer can be adapted to new downstream tasks to achieve good prediction accuracy with a limited number of samples. Our study sheds light on how transformers effectively learn structured data.
