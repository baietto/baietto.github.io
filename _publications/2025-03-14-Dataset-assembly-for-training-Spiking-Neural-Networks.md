---
title: "Dataset assembly for training Spiking Neural Networks"
collection: publications
category: manuscripts
permalink: /publication/2025-03-14-Dataset-assembly-for-training-Spiking-Neural-Networks
excerpt: ''
date: 2025-03-14
venue: 'Neurocomputing'
slidesurl: 
paperurl: 'https://www.sciencedirect.com/science/article/abs/pii/S0925231224019787'
citation: 'Baietto, A., Bihl, T. J., & Stewart, C. (2025). Dataset assembly for training Spiking Neural Networks. <i>Neurocomputing</i>, 622, 129207. https://doi.org/10.1016/j.neucom.2024.129207'
---

Spiking Neural Networks (SNNs) are the next generation of biologically plausible Artificial Neural Networks (ANNs) which utilize neurons that communicate via binary spikes distributed over time rather than scalar values. These sparse neuron-to-neuron communications offer significant power savings when realized on purpose-built neuromorphic hardware. However, training SNNs is challenging because backpropagation, the conventional technique used for ANNs, cannot handle the discrete pulses spread across differing neurons during activation. Various SNN training platforms have been put forth that provide workarounds for this problem by loosening the constraints on neuron activation. Such approximations have the negative side-effect of forming dependencies to the specific viewpoint in which the training spike data was collected. In this paper, we show that the mechanistic models used in state-of-the-art SNN platforms perform poorly when presented with samples of differing spike viewpoints caused by changes in light intensity, simulation parameters, or Dynamic Vision Sensor (DVS) camera settings. We present a platform-agnostic approach for dataset assembly, the maximization of model potential through methodical dataset selection at the sample-level granularity. Our approach mitigates spike viewpoint dependencies by combining established SNN training approximations with a Generative Adversarial Network (GAN) to augment training datasets with broader spike distribution data. Dataset assembly improves model robustness on targeted viewpoints, without introducing significant computational overhead, by extracting untapped performance from extant starting datasets. Models trained using our approach boast a 187.28% increase in accuracy robustness when evaluated on differing spike viewpoints using the IBM DVSGesture dataset.