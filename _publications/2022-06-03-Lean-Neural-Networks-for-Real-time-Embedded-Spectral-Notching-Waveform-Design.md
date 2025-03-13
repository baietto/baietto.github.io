---
title: "Lean Neural Networks for Real-time Embedded Spectral Notching Waveform Design"
collection: publications
category: conferences
permalink: /publication/2022-06-03-Lean-Neural-Networks-for-Real-time-Embedded-Spectral-Notching-Waveform-Design
excerpt: ''
date: 2022-06-03
venue: 'IEEE 31st International Symposium on Industrial Electronics'
slidesurl: 
slieslink: 
paperurl: 'https://ieeexplore.ieee.org/document/9831772'
paperlink: 
citation: 'A. Baietto, J. Boubin, P. Farr and T. J. Bihl, &quot;Lean Neural Networks for Real-time Embedded Spectral Notching Waveform Design,&quot; <i>2022 IEEE 31st International Symposium on Industrial Electronics (ISIE)</i>, Anchorage, AK, USA, 2022, pp. 1121-1126, doi: 10.1109/ISIE51582.2022.9831772.'
---

Spectral notching, a waveform design method used in signal processing and radar, mitigates interference caused by an ever-growing number of technologies which saturate the radio frequency (RF) spectrum. Online wave-form design is possible with current technology, but extant techniques can not meet real-time latency requirements on the low size weight and power (SWaP) embedded hardware ideal for contexts where online waveform design is most useful. Current techniques rely on convex optimization, leading to non-trivial execution times and excessive compute and power requirements. Artificial Neural Networks (ANNs) could feasibly be used for spectral notching due to their ability to approximate complex non-linear functions; however, ANNs generally require considerable processing power and result in long inference times. Prior work has shown that ANNs can accurately perform real-time radar waveform design, albeit in very specific contexts. In this paper, we extend that work, demonstrating that lean neural networks, which model successful convex optimization algorithms in a lower dimensional representation, can meet real-time latency constraints for general waveform design without sacrificing accuracy on low SWaP embedded hardware. Our results are exemplified in simulation on real embedded and general purpose hardware. Overall, our lean neural network solution decreases inference time on traditional embedded hardware by 8.5x when compared to the fastest optimization approach, and uses 10.6x less energy. Our system executes quickly on low-power embedded devices, using only 16.6% of the energy a conventional GPU-provisioned system would require.