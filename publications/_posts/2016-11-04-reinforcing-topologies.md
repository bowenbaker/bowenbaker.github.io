---
layout: post
title: Designing neural network architectures using reinforcement learning
titlelink: https://arxiv.org/pdf/1611.02167.pdf
authors: Bowen Baker, Otkrist Gupta, Nikhil Naik, and Ramesh Raskar
venue: International Conference on Learning Representations, 2017
arxiv: https://arxiv.org/abs/1611.02167
code: https://github.com/bowenbaker/metaqnn
---

At present, designing convolutional neural network (CNN) architectures requires both human expertise and labor. New architectures are handcrafted by careful experimentation or modified from a handful of existing networks. We introduce MetaQNN, a meta-modeling algorithm based on reinforcement learning to automatically generate high-performing CNN architectures for a given learning task. The learning agent is trained to sequentially choose CNN layers using Q-learning with an ϵ-greedy exploration strategy and experience replay. The agent explores a large but finite space of possible architectures and iteratively discovers designs with improved performance on the learning task. On image classification benchmarks, the agent-designed networks (consisting of only standard convolution, pooling, and fully-connected layers) beat existing networks designed with the same layer types and are competitive against the state-of-the-art methods that use more complex layer types. We also outperform existing meta-modeling approaches for network design on image classification tasks.