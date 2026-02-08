---
title: "Software"
author_profile: true
redirect_from: 
  - /software.html
---

## Packages

[**Invisible Ink**](https://github.com/cerai-iitm/invisibleink)  
Package for LLM-based text generation with differential privacy using the [InvsibleInk method (NeurIPS 2025)](https://arxiv.org/abs/2507.02974). 
Install as `pip install invink`.

[**XBern Confidence Intervals**](https://github.com/krishnap25/xbern_confidence_intervals/)   
An XBern or exchangeable Bernoulli distribution is a probability distribution over binary vectors which is exchangeable, i.e., the probability mass does not change when the coordinates of the vector are permuted. This package gives confidence intervals for the mean of the XBern distribution.

For n binary vectors in k-dimensions, the confidence interval could vary from 1 / sqrt(n) (if the k dimensions are copies of each other) to 1 / sqrt(nk) (if the k dimensions are independent). This software gives adaptive confidence intervals yielding 1 / sqrt(n) intervals in high correlation and automatically improving to 1 / sqrt(nk) + 1 / n^{3/4} when correlations are low.

Install as `pip install xbern-confidence-intervals`.

[**Dataset Grouper**](https://github.com/google-research/dataset_grouper)  
A scalable library to create, write, and iterate over group-partitioned (i.e. federated) datasets.
It allows the creation of federated datasets suitable for pretraining and finetuning large language models.
Install as `pip install dataset-grouper`.

[**Mauve**](https://github.com/krishnap25/mauve) ([Documentation](https://krishnap25.github.io/mauve/))  
A package to compute the Mauve score for neural text generation. Install as `pip install mauve-text`.
It is also supported via the [HuggingFace Evaluate](https://github.com/huggingface/evaluate/) package. 

[**SQwash**](https://github.com/krishnap25/sqwash) ([Documentation](https://krishnap25.github.io/sqwash/))   
Distributionally robust learning in PyTorch with 1 additional line of code. Install as `pip install sqwash`. 

[**Geom-Median**](https://github.com/krishnap25/geom_median)  
Fast and Differentiable Geometric Median in PyTorch and NumPy. Install as `pip install geom-median`. 

[**Casimir**](https://github.com/krishnap25/casimir) ([Documentation](https://krishnap25.github.io/casimir/))  
A toolbox of selected optimization algorithms for unstructured tasks such as binary classification, and structured prediction tasks such as visual object localization and named entity recognition.

[**RFA**](https://github.com/google-research/federated/tree/master/robust_aggregation)
TensorFlow Federated Implementation of robust aggregation for federated learning using the geometric median.

## Code to reproduce results from papers

[**LiDP Auditing**](https://github.com/google-research/federated/tree/master/lidp_auditing):
Code to reproduce the experimental results of [this NeurIPS 2023 paper](https://arxiv.org/pdf/2305.18447.pdf), which shows how to improve the sample complexity of auditing differential privacy (DP) by auditing the equivalent notion of Lifted DP with randomized hypothesis tests and adaptive confidence intervals.

[**Federated Learning with Partial Personalization**](https://github.com/facebookresearch/FL_partial_personalization):
PyTorch implementation of various personalized federated learning algorithms and experiments on text, vision, and speech data. 
Reproduce results from [this ICML 2022 paper](https://arxiv.org/pdf/2204.03809.pdf).

[**Mauve Experiments**](https://github.com/krishnap25/mauve-experiments):
Implementation of Mauve and other similarity measures for neural text generation. Reproduce results from [this NeurIPS 2021 paper](https://arxiv.org/pdf/2102.01454.pdf).

[**RFA**](https://github.com/krishnap25/RFA) and PyTorch port [**tRFA**](https://github.com/krishnap25/tRFA):
Implementation of RFA, a robust aggregation algorithm for federated learning,
in simulation. Reproduce results from [this paper](https://arxiv.org/pdf/1912.13445.pdf) published in IEEE Transactions on Signal Processing 2022.

[**Simplicial-FL**](https://github.com/krishnap25/simplicial-fl):
Implementation of Simplicial-FL to handle device heterogeneity in federated learning,
in simulation. Reproduce results from [this paper](https://krishnap25.github.io/papers/2021_Simplicial_FL_CISS.pdf).
