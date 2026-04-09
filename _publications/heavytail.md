---
title: "Impact of classification difficulty on the weight matrices spectra in Deep Learning and application to early-stopping."
collection: publications
category: manuscripts
permalink: /publication/heavytail
excerpt: ' '
date: 2023-01-01
venue: 'Journal of Machine Learning Research'
slidesurl: 'http://xuranmeng.github.io/files/slides/heavytail.pdf'
paperurl: 'https://www.jmlr.org/papers/volume24/21-1441/21-1441.pdf'
citation: '<b>Xuran Meng</b> and Jianfeng Yao, &quot;Impact of classification difficulty on the weight matrices spectra in Deep Learning and application to early-stopping.&quot; <i>JMLR 24</i>, 2023.'
---
Much recent research effort has been devoted to explain the success of deep learning.  Random Matrix Theory (RMT) provides an emerging way to this end by analyzing the spectra of  large random matrices involved in a trained deep neural network (DNN) such as weight matrices or Hessian matrices in the stochastic gradient descent algorithm.  To better  understand spectra of weight matrices, we conduct extensive experiments on weight matrices under different settings for layers, networks and data sets. Based on the previous work of Martin and Mahoney (2021), spectra of weight matrices at the terminal stage of training are classified  into three main types: Light Tail (LT), Bulk Transition period  (BT) and Heavy Tail (HT). These different types, especially HT, implicitly indicate some regularization in the DNNs.  In this paper, inspired from Martin and Mahoney (2021), we identify the difficulty of the classification problem as an important factor for the appearance of HT in weight matrices spectra. Higher the classification difficulty, higher the chance for HT to appear. Moreover, the classification difficulty can be affected either by the signal-to-noise ratio of the dataset, or by the complexity of the classification problem (complex features, large number of classes) as well. Leveraging on this finding, we further propose a spectral criterion to detect the appearance of HT and use it to early stop the training process without testing data. Such early stopped DNNs have the merit of avoiding overfitting and   unnecessary extra training while preserving a much comparable generalization ability. These findings from the paper are validated in several NNs (LeNet, MiniAlexNet and VGG), using Gaussian synthetic data and real data sets (MNIST and CIFAR10). 
