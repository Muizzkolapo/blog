---
title: "Data Augmentation for Cover Song Identification Systems Using Generative Adversarial Networks"
date: 2023-03-04T09:13:17Z
draft: false
---




Abstract
===================================

Generative Adversarial Networks (GAN) have seen great improvement in modelling
synthetic data with results unparalleled in the field of deep learning. This research explores
data augmentation for cover song identification by extending state-of-the-art GAN
frameworks used in image processing to cover song identification. Research in this domain
is still in the early phases, this work explores the implementation of a GAN model capable
of generating new features for cover song identification. The implementation utilises the
Deep Convolutional Generative Adversarial Networks (DCGAN) to learn the underlying
distribution of the sample dataset provided by Breathe Music, the conditional Generative
Adversarial Networks (cGANs) was used for the encoding of the class to give control over
which class in the distribution is generated. A control model was also created using an
industry-standard dataset, CIFAR-100, to validate the approach. The qualitative and
quantitative results were obtained for both two datasets, and a comparative analysis of
both models was undertaken. The model results demonstrated a strong performance in
capturing the underlying data distribution for the CIFAR100 dataset but performed poorly
for the custom music dataset provided by Breathe Music using the statistical probability
distribution plot, and Fr´echet Inception Score (FID) metric.

[Read Paper](https://github.com/Muizzkolapo/masters-dissertation/blob/main/Muizz%20Lateef%20Dissertation.pdf){: .btn}
