---
title: "Neural Networks Are A Priori Biased Towards Boolean Functions With Low Entropy."
collection: publications
permalink: /publication/neural-networks-are-a-priori-biased
excerpt: 'In this paper we show analytically that neural networks have a certain built-in simplicity bias upon initialisation.'
date: 2020-01-02
venue: 'unpublished'
paperurl: 'https://arxiv.org/pdf/1909.11522.pdf'
citation: Mingard et al. (2020). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---
Understanding the inductive bias of neural networks is critical to explaining theirability to generalise. Here, for one of the simplest neural networks – a single-layerperceptron withninput neurons, one output neuron, and no threshold bias term –we prove that upon random initialisation of weights, thea prioriprobabilityP(t)that it represents a Boolean function that classifiestpoints in{0,1}nas1has aremarkably simple form:P(t) = 2−nfor 0≤t <2n.Since a perceptron can express far fewer Boolean functions with small or largevalues oft(low “entropy”) than with intermediate values oft(high “entropy”)there is,on average, a strong intrinsica-prioribias towards individual functionswith low entropy.  Furthermore, within a class of functions with fixedt, we oftenobserve a further intrinsic bias towards functions of lower complexity. Finally, weprove that, regardless of the distribution of inputs, the bias towards low entropybecomes monotonically stronger upon adding ReLU layers, and empirically showthat increasing the variance of the bias term has a similar effect.

[Download paper here](https://arxiv.org/pdf/1909.11522.pdf)
