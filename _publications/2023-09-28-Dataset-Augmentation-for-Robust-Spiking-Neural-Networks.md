---
title: "Dataset Augmentation for Robust Spiking Neural Networks"
collection: publications
category: conferences
permalink: /publication/2023-09-28-Dataset-Augmentation-for-Robust-Spiking-Neural-Networks
excerpt: ''
date: 2023-09-28
venue: 'IEEE International Conference on Autonomic Computing and Self-Organizing Systems Companion'
slidesurl: 
slideslink: '2023-09-28-Dataset-Augmentation-for-Robust-Spiking-Neural-Networks.pdf'
paperurl: 'https://www.computer.org/csdl/proceedings-article/acsos-c/2023/374600a116/1SN6yV2yKR2'
paperlink: 
citation: 'A. Baietto, C. Stewart and T. J. Bihl, &quot;Dataset Augmentation for Robust Spiking Neural Networks,&quot; in <i>2023 IEEE International Conference on Autonomic Computing and Self-Organizing Systems Companion (ACSOS-C)</i>, Toronto, ON, Canada, 2023, pp. 116-121, doi: 10.1109/ACSOS-C58168.2023.00050.'
---

In spiking neural networks (SNNs), neurons are connected in layers but, unlike artificial neural networks (ANNs), they transmit output signals only after their input signals exceed the activation threshold. By eliding unnecessary transmissions, processors designed for SNNs can consume much less power than processors designed for ANNs, making SNNs a promising architecture for energy-constrained datacenters and Internet of Things (IoT) devices. However, training SNNs to perform machine learning tasks as well as ANNs is challenging because backpropagation, a widely used technique to train ANNs, cannot infer the changing subset of transmitting neurons and the duration of their transmissions for each input. State-of-the-art SNN platforms provide platform-specific, mechanistic models to characterize neuron activations; however, these models are often heavily tied to the specific spike distribution. In this paper, we show that SNNs trained on state-of-the-art platforms perform poorly when presented with different spike distributions. We present a platform-agnostic approach that automatically learns neuron activations from observations. Precisely, we use established approximations, combined with a generative adversarial network (GAN) to augment the training dataset with broader spike distribution data. Our approach achieved 54.57 % accuracy on the CIFAR-10 dataset with an average 1.80% improvement in accuracy over existing state-of-the-art SNNs when evaluated on differing spike distributions. These preliminary results validate our approach and lay the groundwork for future research into strengthening SNN models.