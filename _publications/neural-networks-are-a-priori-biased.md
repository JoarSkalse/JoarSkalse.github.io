---
title: "Neural Networks Are A Priori Biased Towards Boolean Functions With Low Entropy."
collection: papers
permalink: papers/neural-networks-are-a-priori-biased
excerpt: 'In this paper we show analytically that neural networks have a certain built-in simplicity bias upon initialisation.'
date: 2020-01-02
venue: 'unpublished'
paperurl: 'https://arxiv.org/pdf/1909.11522.pdf'
citation: Mingard et al. (2020). Neural Networks Are A Priori Biased Towards Boolean Functions With Low Entropy.'
---
Understanding the inductive bias of neural networks is critical to explaining their ability to generalise. Here, for one of the simplest neural networks -- a single-layer perceptron with n input neurons, one output neuron, and no threshold bias term -- we prove that upon random initialisation of weights, the a priori probability P(<i>t</i>) that it represents a Boolean function that classifies <i>t</i> points in {0,1}<sup>n</sup> as 1 has a remarkably simple form: P(<i>t</i>) = 2<sup>-n</sup> for 0 ≤ <i>t</i> < 2<sup>n</sup>. Since a perceptron can express far fewer Boolean functions with small or large values of <i>t</i> (low “entropy”) than with intermediate values of <i>t</i> (high “entropy”) there is, on average, a strong intrinsic a-priori bias towards individual functions with low entropy.  Furthermore, within a class of functions with fixed <i>t</i>, we often observe a further intrinsic bias towards functions of lower complexity. Finally, we prove that, regardless of the distribution of inputs, the bias towards low entropy becomes monotonically stronger upon adding ReLU layers, and empirically show that increasing the variance of the bias term has a similar effect.

[Download paper here](https://arxiv.org/pdf/1909.11522.pdf)
