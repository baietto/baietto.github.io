---
title: "Lean Neural Networks for Autonomous Radar Waveform Design"
collection: publications
category: manuscripts
permalink: /publication/2022-02-09-Lean-Neural-Networks-for-Autonomous-Waveform-Radar-Design
excerpt: ''
date: 2022-02-09
venue: 'Sensors'
slidesurl: 
slideslink: 
paperurl: 'https://www.mdpi.com/1424-8220/22/4/1317'
paperlink: 
citation: 'Baietto, A., Boubin, J., Farr, P., Bihl, T. J., Jones, A. M., & Stewart, C. (2022). Lean Neural Networks for Autonomous Radar Waveform Design. <i>Sensors</i>, 22(4), 1317. https://doi.org/10.3390/s22041317'
---

In recent years, neural networks have exploded in popularity, revolutionizing the domains of computer vision, natural language processing, and autonomous systems. This is due to neural networks ability to approximate complex non-linear functions. Despite their effectiveness, they generally require large labeled data sets and considerable processing power for both training and prediction. Some of these bottlenecks have been mitigated by recent increased availability of high-quality data sets, improvements in neural network development software, and greater hardware support. Due to algorithmic bloat, neural network inference times and imprecision make them undesirable for some problems where fast classical algorithm solutions already exist, other classes of algorithms, such as convex optimization, with non-trivial execution times could be reduced using neural solutions. These algorithms could be replaced with light-weight neural networks, benefiting from their high degree of parallelization and high accuracy when properly trained. Previous work has explored how low size, weight, and power (low SWaP) neural networks and neuromorphic computing can be used to improve autonomous radar waveform design techniques that currently rely on convex optimization. Autonomous radar waveform design helps meet the need for interference mitigation caused by an ever-growing number of consumer and commercial technologies which pollute the radio frequency (RF) spectrum. Spectral notching, a radar waveform design technique, augments transmitted radar waveforms to avoid frequencies with excessive interference while maintaining the integrity of the waveform. In this paper, we extend that work, demonstrating that lean neural networks and specialized hardware can improve inference time for waveform design without sacrificing accuracy. Our lean neural solution incorporates problem-specific information into the layer structures and loss functions to decrease network size and improve accuracy. We provide model outcomes implemented on radio frequency system on a chip (RFSoC) hardware that support our simulation results. Our neural network solution decreases inference time on traditional CPU hardware by 1057× and on GPU hardware accelerators by 883× while maintaining 99% cosine similarity.