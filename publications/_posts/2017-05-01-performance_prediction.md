---
layout: post
title: Practical Neural Network Performance Prediction for Early Stopping
titlelink: https://arxiv.org/pdf/1705.10823.pdf
authors: Bowen Baker*, Otkrist Gupta*, Ramesh Raskar, and Nikhil Naik
venue: Preprint
arxiv: https://arxiv.org/abs/1705.10823
code: 
---

In the neural network domain, methods for hyperparameter optimization and meta-modeling are computationally expensive due to the need to train a large number of neural network configurations. In this paper, we show that a simple regression model, based on support vector machines, can predict the final performance of partially trained neural network configurations using features based on network architectures, hyperparameters, and time-series validation performance data. We use this regression model to develop an early stopping strategy for neural network configurations. With this early stopping strategy, we obtain significant speedups in both hyperparameter optimization and meta-modeling. Particularly in the context of meta-modeling, our method can learn to predict the performance of drastically different architectures and is seamlessly incorporated into reinforcement learning-based architecture selection algorithms. Finally, we show that our method is simpler, faster, and more accurate than Bayesian methods for learning curve prediction.