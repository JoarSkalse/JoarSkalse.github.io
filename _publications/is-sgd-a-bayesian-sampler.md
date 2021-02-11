---
title: "Is SGD a Bayesian sampler? Well, almost."
collection: papers
permalink: papers/is-sgd-a-bayesian-sampler
excerpt: 'In this paper we provide extensive empirical evidence that SGD (and related optimisers) behave approximately like Bayesian samplers. This is in turn strong evidence that the inductive bias of neural networks comes primarily from their parameter-function map, rather than SGD (which is commonly assumed).

A summary of this research can be found [here](https://towardsdatascience.com/neural-networks-are-fundamentally-bayesian-bee9a172fad8).'
date: 2020-01-02
venue: 'unpublished'
paperurl: 'https://arxiv.org/pdf/2006.15191.pdf'
citation: Mingard et al. (2020). Is SGD a Bayesian sampler? Well, almost.'
---
Deep neural networks (DNNs) generalise remarkably well in the overparameterised regime, suggesting a strong inductive bias towards functions with low generalisation error. We empirically investigate this bias by calculating, for a range of architectures and datasets, the probability P<sub>SGD</sub>(<i>f</i> | <i>S</i>) that an overparameterised DNN, trained with stochastic gradient descent (SGD) or one of its variants, converges on a function <i>f</i> consistent with a training set <i>S</i>. We also use Gaussian processes to estimate the Bayesian posterior probability P<sub>B</sub>(<i>f</i> | <i>S</i>) that the DNN expresses <i>f</i> upon random sampling of its parameters, conditioned on <i>S</i>. Our main findings are that P<sub>SGD</sub>(<i>f</i> | <i>S</i>) correlates remarkably well with P<sub>B</sub>(<i>f</i> | <i>S</i>) and that P<sub>B</sub>(<i>f</i> | <i>S</i>) is strongly biased towards low-error and low complexity functions. These results imply that strong inductive bias in the parameter-function map (which determines P<sub>B</sub>(<i>f</i> | <i>S</i>)), rather than a special property of SGD, is the primary explanation for why DNNs generalise so well in the overparameterised regime. While our results suggest that the Bayesian posterior P<sub>B</sub>(<i>f</i> | <i>S</i>) is the first order determinant of P<sub>SGD</sub>(<i>f</i> | <i>S</i>), there remain second order differences that are sensitive to hyperparameter tuning. A function probability picture, based on P<sub>SGD</sub>(<i>f</i> | <i>S</i>) and/or P<sub>B</sub>(<i>f</i> | <i>S</i>), can shed light on the way that variations in architecture or hyperparameter settings such as batch size, learning rate, and optimiser choice, affect DNN performance. 

[Download paper here](https://arxiv.org/pdf/2006.15191.pdf)
