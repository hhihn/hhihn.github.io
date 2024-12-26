---
title: "Bounded rational decision-making with adaptive neural network priors"
collection: publications
excerpt: 'MCMC methods to simulate bounded rationality in neural networks'
date: 2018-01-01
venue: 'Neurocomputing'


---
## Abstract
Bounded rationality investigates utility-optimizing decision-makers with limited information-processing power. In particular, information theoretic bounded rationality models formalize resource constraints abstractly in terms of relative Shannon information, namely the Kullback-Leibler Divergence between the agents’ prior and posterior policy. Between prior and posterior lies an anytime deliberation process that can be instantiated by sample-based evaluations of the utility function through Markov Chain Monte Carlo (MCMC) optimization. The most simple model assumes a fixed prior and can relate abstract information-theoretic processing costs to the number of sample evaluations. However, more advanced models would also address the question of learning, that is how the prior is adapted over time such that generated prior proposals become more efficient. In this work we investigate generative neural networks as priors that are optimized concurrently with anytime sample-based decision-making processes such as MCMC. We evaluate this approach on toy examples.
[Find the paper here](https://link.springer.com/chapter/10.1007/978-3-319-99978-4_17)

### Recommended BibTex citation: 
@inproceedings{hihn2018bounded,
  title={Bounded rational decision-making with adaptive neural network priors},
  author={Hihn, Heinke and Gottwald, Sebastian and Braun, Daniel A},
  booktitle={Artificial Neural Networks in Pattern Recognition: 8th IAPR TC3 Workshop, ANNPR 2018, Siena, Italy, September 19--21, 2018, Proceedings 8},
  pages={213--225},
  year={2018},
  organization={Springer}
}