---
layout: page
title:
permalink: /research/
group: research
---


# Research Interests

My goal is to understand the **performance behavior of highly-configurable software systems** in dynamic and uncertain environments. 

### Why this is an important problem?
An example of highly-configurable system is Deep Neural Networks having tons of hyper-parameters (e.g., learning rate, depth of the neural architecture, deployment configuration, etc) to set. To find the optimal configuration that provide an ideal trade-off between the accuracy and inference time, we need to search and optimize a highly-dimensional configuration space which is extremely challenging. 

### Who cares?

Many small and medium sized enterprises use a form of machine learning model for their tasks (e.g., fraud detection). Due to the limited resources and desire for speed, it is important to tune the neural architectures to achieve the desired accuracy and inference speed, while demanding less computing resources. 

### What is my approach and the intuition behind it? 
Our recent [empirical study](https://arxiv.org/pdf/1709.02280) revealed that there exist several sources of similarities between the performance behavior of configurable systems in different environments, opening up several opportunities for **transfer learning**. Using this intuition, I develop methods to enable learning performance behavior of configurable systems using a lower fidelity or cheaper version of the target system that we are optimizing (e.g., using a workload that allow us to measure the neural architecture performance faster). Please see our recent publications for further details: [SEAMS'17](https://arxiv.org/pdf/1704.00234), [MASCOTS'16](https://arxiv.org/pdf/1606.06543).


# Research Expertise

* **Software Engineering:** Highly-configurable software, self-adaptive software, software architecture
* **Systems:** Black-box performance modeling and analysis, control theory, autonomic computing, cloud computing, big data
* **Machine Learning:** Transfer learning, Gaussian processes, reinforcement learning, Bayesian optimization