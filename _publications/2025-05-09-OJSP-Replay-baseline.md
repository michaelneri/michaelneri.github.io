---
title: "Multi-channel Replay Speech Detection using an Adaptive Learnable Beamformer"
collection: publications
category: manuscripts
permalink: /publication/2025-05-09-OJSP-Replay-baseline
excerpt: 'Detecting replay excerpts from multi-channels recordings with a learnable adaptive time-frequency beamformer.'
date: 2025-05-09
venue: 'IEEE Open Journal of Signal Processing'
paperurl: 'https://michaelneri.github.io/files/2025-05-06-OJSP-Replay.pdf'
citation: 'M. Neri, and T. Virtanen, "SMulti-channel Replay Speech Detection using an Adaptive Learnable Beamformer," in IEEE Open Journal of Signal Processing, Early Access, 2025, doi: 10.1109/OJSP.2025.3568758.'
---

<img src="../files/Model-OJSP.png"/>

Replay attacks belong to the class of severe threats against voice-controlled systems, exploiting the easy accessibility of speech signals by recorded and replayed speech to grant unauthorized access to sensitive data. In this work, we propose a multi-channel neural network architecture called M-ALRAD for the detection of replay attacks based on spatial audio features. This approach integrates a learnable adaptive beamformer with a convolutional recurrent neural network, allowing for joint optimization of spatial filtering and classification. Experiments have been carried out on the ReMASC dataset, which is a state-of-the-art multi-channel replay speech detection dataset encompassing four microphones with diverse array configurations and four environments. Results on the ReMASC dataset show the superiority of the approach compared to the state-of-the-art and yield substantial improvements for challenging acoustic environments. In addition, we demonstrate that our approach is able to better generalize to unseen environments with respect to prior studies.