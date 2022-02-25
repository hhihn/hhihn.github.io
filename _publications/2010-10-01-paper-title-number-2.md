---
title: "Multi-Modal Pain Intensity Assessment Based on Physiological Signals: A Deep Learning Perspective"
collection: publications
permalink: /publication/2010-10-01-paper-title-number-2
excerpt: 'This paper is about the number 2. The number 3 is left for future work.'
date: 2021-09-01
venue: 'Frontiers in Physiology'
---
# Abstract
Traditional pain assessment approaches ranging from self-reporting methods, to observational scales, rely on the ability of an individual to accurately assess and successfully report observed or experienced pain episodes. Automatic pain assessment tools are therefore more than desirable in cases where this specific ability is negatively affected by various psycho-physiological dispositions, as well as distinct physical traits such as in the case of professional athletes, who usually have a higher pain tolerance as regular individuals. Hence, several approaches have been proposed during the past decades for the implementation of an autonomous and effective pain assessment system. These approaches range from more conventional supervised and semi-supervised learning techniques applied on a set of carefully hand-designed feature representations, to deep neural networks applied on preprocessed signals. Some of the most prominent advantages of deep neural networks are the ability to automatically learn relevant features, as well as the inherent adaptability of trained deep neural networks to related inference tasks. Yet, some significant drawbacks such as requiring large amounts of data to train deep models and over-fitting remain. Both of these problems are especially relevant in pain intensity assessment, where labeled data is scarce and generalization is of utmost importance. In the following work we address these shortcomings by introducing several novel multi-modal deep learning approaches (characterized by specific supervised, as well as self-supervised learning techniques) for the assessment of pain intensity based on measurable bio-physiological data. While the proposed supervised deep learning approach is able to attain state-of-the-art inference performances, our self-supervised approach is able to significantly improve the data efficiency of the proposed architecture by automatically generating physiological data and simultaneously performing a fine-tuning of the architecture, which has been previously trained on a significantly smaller amount of data.

[Download paper here](https://www.frontiersin.org/articles/10.3389/fphys.2021.720464/pdf)

### Recommended BibTex citation: 
@Article{thiam2021multi,
  author    = {Thiam, Patrick and Hihn, Heinke and Braun, Daniel A and Kestler, Hans A and Schwenker, Friedhelm},
  title     = {Multi-Modal Pain Intensity Assessment Based on Physiological Signals: A Deep Learning Perspective},
  journal   = {Frontiers in Physiology},
  year      = {2021},
  volume    = {12},
  publisher = {Frontiers Media SA},
}