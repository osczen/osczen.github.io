---
layout: post
title: Implementing a simple attention mechanism for RNNs in Tensorflow
---

Over the course of my research project, I struggled to find a good tutorial for implementing simple attention mechanisms for RNN models in Tensorflow. The code for doing so is actually quite simple once you grasp the essential Tensorflow operators needed for implementing attention. In this tutorial, we will implement a simple attention mechanism for a LSTM-RNN language model trained on the Penn Tree Bank dataset. We will be using the code and dataset provided in https://www.tensorflow.org/tutorials/recurrent. I highly recommend at least skimming the Tensorflow RNN tutorial before diving into this one.


**What is Attention?**

