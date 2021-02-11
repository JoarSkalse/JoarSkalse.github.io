---
title: "Is SGD a Bayesian sampler? Well, almost."
collection: publications
permalink: /publication/is-sgd-a-bayesian-sampler
excerpt: 'In this paper we provide extensive empirical evidence that SGD (and related optimisers) behave approximately like Bayesian samplers. This is in turn strong evidence that the inductive bias of neural networks comes primarily from their parameter-function map, rather than SGD (which is commonly assumed).'
date: 2020-01-02
venue: 'unpublished'
paperurl: 'https://arxiv.org/pdf/2006.15191.pdf'
citation: Mingard et al. (2020). Is SGD a Bayesian sampler? Well, almost.'
---
Deep neural networks (DNNs) generalise remarkably well in the overparameterised regime, suggesting a strong inductive bias towards functions with low generalisation error. We empirically investigate this bias by calculating, for a range of architectures and datasets, the probability P_SGD that an overparameterised DNN, trained with stochastic gradient descent (SGD) or one of its variants, converges on a function &quot;f&quot; consistent with a training set &quot;S&quot;. We also use Gaussian processes to estimate the Bayesian posterior probability P_B that the DNN expresses &quot;f&quot; upon random sampling of its parameters, conditioned on &quot;S&quot;. Our main findings are that P_SGD correlates remarkably well with P_B and that P_B is strongly biased towards low-error and low complexity functions. These results imply that strong inductive bias in the parameter-function map (which determines P_B), rather than a special property of SGD, is the primary explanation for why DNNs generalise so well in the overparameterised regime. While our results suggest that the Bayesian posterior P_B is the first order determinant of P_SGD, there remain second order differences that are sensitive to hyperparameter tuning. A function probability picture, based on P_SGD and/or P_B, can shed light on the way that variations in architecture or hyperparameter settings such as batch size, learning rate, and optimiser choice, affect DNN performance. 

[Download paper here](https://arxiv.org/pdf/2006.15191.pdf)

A summary of this research can be found [here](https://towardsdatascience.com/neural-networks-are-fundamentally-bayesian-bee9a172fad8).
