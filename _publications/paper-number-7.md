---
title: "Online continual learning through unsupervised mutual information maximization"
collection: publications
excerpt: 'a neural network layer implementing a mixture of experts to facilitate continual learning'
date: 2021-01-01
venue: 'Neurocomputing'


---
## Abstract
Catastrophic forgetting remains a challenge for artificial learning systems, especially in the case of Online learning, where task information is unavailable. This work proposes a novel task-agnostic approach for class-incremental Continual Learning that combines expansion and regularization methods through a non-parametric model. The model adds new experts automatically while regularizing old experts under a variational Bayes paradigm. Expert selection is implemented using Contrastive Learning techniques, catastrophic forgetting is mitigated by minimizing mutual information between the experts’ posterior and prior feature embeddings. Importantly, our method successfully handles single source tasks such as split-MNIST and split-CIFAR-10/100, mixed source tasks like split-CIFAR-100/split-F-CelebA, and long task sequences such as split-TinyImageNet, without using generative models or replay mechanisms. We also successfully extend our approach to Continual Reinforcement learning tasks. Our method achieves these results in a task-agnostic and replay-free setting, making it more flexible than most existing Continual Learning approaches without compromising performance. We provide the code and hyper-parameters for our experiments.
[Find the paper](https://www.sciencedirect.com/science/article/pii/S0925231224001930)

### Recommended BibTex citation: 
@article{hihn2024online,
  title={Online continual learning through unsupervised mutual information maximization},
  author={Hihn, Heinke and Braun, Daniel A},
  journal={Neurocomputing},
  volume={578},
  pages={127422},
  year={2024},
  publisher={Elsevier}
}
