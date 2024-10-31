---
title: "High frequency algorithm and its back-testing results based on GAN."
collection: publications
category: manuscripts
permalink: /publication/gan
excerpt: ' '
date: 2020-01-01
venue: 'Journal of Machine Learning Research'
#slidesurl: 'http://xuranmeng.github.io/files/slides/heavytail.pdf'
paperurl: 'http://just.ustc.edu.cn/article/pdf/preview/1641365817900-1998767242.pdf'
citation: '<b>Xuran Meng</b>, Xiuchun Bi and Shuguang Zhang, &quot;High frequency algorithm and its back-testing results based on GAN.&quot; <i>JUSTC 50</i>, 2020.'
---
In the financial clasification mission,due to the big noise and low information-ratio in financial data,traditional supervised-learning regime may extend the noise influence because of the over dependent on the data label. GAN (generative adversarial network ) can learn the data characters and reduce the influence of noise.When it is used to analyze the financial data,it has great results.We apply GAN to the high frequency trading: set the data labeled or unlabeled based on its volatility,then use the adversarial training between generative network G and discriminative network D to learn the intrinsic characters of the data,finaly use the welltrained D to get the up and down clasification model and the quantization strategy.The sample is based on the future data,and the final results show that the LSTM model training by GAN is better than the deep learning models such as LSTM with supervised training and the Logistic regression model.
