---
layout: page
title:
permalink: /research/
group: research
---


# Research Interests

My goal is to understand the **performance behavior of highly-configurable software systems** in dynamic and uncertain environments. 

### Why this is an important problem?
An example of a highly-configurable system is Deep Neural Networks, which have tons of hyper-parameters (e.g., learning rate, depth of the neural architecture, deployment configuration, etc) to set. To find the optimal configuration that provide an ideal trade-off between the accuracy and inference time, we need to search and optimize a highly-dimensional configuration space which is an extremely challenging task. 

### Who cares?
Many small and medium sized enterprises use a form of machine learning pipeline for their tasks (e.g., fraud detection). Due to the limited resources and desire for speed, it is important to tune the data processing pipeline including machine learning algorithms to achieve the desired accuracy and inference speed, while demanding less computing resources. My research enables organizations to get the most out of their configurable systems by providing methods to understand the performance behavior of their systems, explore the design space, reason about qualities (performance, energy), and to make tradeoff.

### What is my solution and the intuition behind it? 
Our recent [empirical study](https://arxiv.org/pdf/1709.02280) revealed that there exist several sources of similarities between the performance behavior of configurable systems in different environments, opening up several opportunities for **transfer learning**. Using this intuition, I develop methods to enable learning performance behavior of configurable systems using a lower fidelity or cheaper version of the target system that we are optimizing (e.g., using a workload that allow us to measure the neural architecture performance faster). Please see our recent publications for further details: [ASE '17](https://arxiv.org/pdf/1709.02280), [SEAMS '17](https://arxiv.org/pdf/1704.00234), [MASCOTS '16](https://arxiv.org/pdf/1606.06543).

### What is my research approach/philosophy?

I go after difficult, but relevant problems in industry. For solving these real-world problems, I design and build solutions that rooted in theory, but at the same time I care a lot about practicality of the solutions that can advance the state-of-the-art. I also attempt to study existing systems to build and advance systems theory based on the observations and insights. I DO NOT BELIEVE in simulations, the solutions should work in practice!


# Research Expertise

* **Software Engineering:** Highly-configurable software, self-adaptive software, software architecture
* **Computer Systems:** Black-box performance modeling and analysis, control theory, autonomic computing, cloud computing, big data
* **Machine Learning:** Transfer learning, Gaussian processes, reinforcement learning, Bayesian optimization