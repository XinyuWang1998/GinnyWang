---
title: word2vec Parameter Learning Explained
authors:
- Xin Rong
date: '2016-06-01'
publishDate: '2023-11-18T21:06:09.907273Z'
publication_types:
- article-journal
publication: '*arXiv:1411.2738 [cs]*'
abstract: The word2vec model and application by Mikolov et al. have attracted a great
  amount of attention in recent two years. The vector representations of words learned
  by word2vec models have been shown to carry semantic meanings and are useful in
  various NLP tasks. As an increasing number of researchers would like to experiment
  with word2vec or similar techniques, I notice that there lacks a material that comprehensively
  explains the parameter learning process of word embedding models in details, thus
  preventing researchers that are non-experts in neural networks from understanding
  the working mechanism of such models. This note provides detailed derivations and
  explanations of the parameter update equations of the word2vec models, including
  the original continuous bag-of-word (CBOW) and skip-gram (SG) models, as well as
  advanced optimization techniques, including hierarchical softmax and negative sampling.
  Intuitive interpretations of the gradient equations are also provided alongside
  mathematical derivations. In the appendix, a review on the basics of neuron networks
  and backpropagation is provided. I also created an interactive demo, wevi, to facilitate
  the intuitive understanding of the model.
tags:
- Computer Science - Computation and Language
- Word2vec
links:
- name: URL
  url: http://arxiv.org/abs/1411.2738
---
