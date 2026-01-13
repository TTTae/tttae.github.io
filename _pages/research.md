---
layout: archive
title: ""
permalink: /research/
author_profile: true
---
{% include base_path %}


Diffusion Language Model Inference with Monte Carlo Tree Search
======
* __Zheng Huang__, Kiran Ramnath, Yueyan Chen, Aosong Feng, Sangmin Woo, Balasubramaniam Srinivasan, Zhichao Xu, Kang Zhou, Shuai Wang, Haibo Ding, Lin Lee Cheong
* EACL 2026 [[Arxiv]](https://arxiv.org/abs/2512.12168)

  * Investigated inference-time reasoning in diffusion language models by framing generation as a structured search problem.
  * Developed an MCTS-based decoding framework to improve long-horizon reasoning under token-level uncertainty.
  * Designed uncertainty-aware rewards and confidence-guided filtering to enable principled reasoning without additional training.
  * Conducted extensive empirical and theoretical analyses of reasoning and sampling strategies in large language models.



Seeing Through the Brain: New Insights from Decoding Visual Stimuli with fMRI
========
* __Zheng Huang__, Enpei Zhang, Yinghao Cai, Weikang Qiu, Carl Yang, Elynn Chen, Xiang Zhang, Rex Ying, Dawei Zhou, Yujun Yan
* Under Review [[Arxiv]](https://arxiv.org/abs/2510.16196)

  * Proposed PRISM, a fMRI decoding framework that uses language models as a brain-aligned intermediate representation for diffusion-based image reconstruction.
  * Supervised fine-tuned a language model on structured, object-centric text to align textual representations with fMRI signals.
  * Designed an agentic prompt optimization loop that iteratively discovers brain-aligned object attributes and
relationships.
  * Introduced an object-centric diffusion framework with spatially grounded cross-attention for text-guided image generation.
  * Conducted systematic analyses of supervised fine-tuning in large language models, and inference behavior in diffusion models.





Enhancing Size Generalization in GNNs through Disentangled Representation Learning
======
* __Zheng Huang__, Qihui Yang, Dawei Zhou and Yujun Yan
* International Conference on Machine Learning (ICML 2024) [[Arxiv]](https://arxiv.org/abs/2406.04601)


  * Researched the generalization of Graph Neural Networks (GNNs) through disentangled representation learning  
  * Proposed a novel and model-agnostic framework designed to disentangle size factors from graph representations
  * Employed size- and task-invariant augmentations, introducing a decoupling loss to minimize shared information in hidden representations
  * Conducted in-depth research on OOD generalization, explainable GNN models and disentangled representation learning


Empowering Next POI Recommendation with Multi-Relational Modeling   
======
* __Zheng Huang__, Jing Ma, Natasha Zhang Foutz and Jundong Li
* Special Interest Group on Information Retrieval (SIGIR 2022) [[Arxiv]](https://arxiv.org/abs/2204.12288)


  *  Studied on Points of Interests (POI) recommendation by capturing the influence of multiple relations
  *  Utilized multiple Graph Convolutional Networks (GCNs) with Self-Attention mechanism to capture multiple user-user social relations (family or colleague) and user-location check-in relations
  *  Adopted coupled Recurrent Neural Networks (RNNs) to capture the mutual influence between users and POIs over time
  *  Conducted in-depth research on recommender system, sequential recommendation and Graph Convolutional Networks



Assessing the Causal Impact of COVID-19 Related Policies on Outbreak Dynamics
======
* Jing Ma, Yushun Dong, __Zheng Huang__, Daniel Mietchen and Jundong Li
* International Conference on World Wide Web (WWW 2022) [[Arxiv]](https://arxiv.org/pdf/2106.01315.pdf)


  *  Studied on the causal effect of different policies in reducing the spread of COVID-19 in the US
  *  Worked on a team and developed a neural network framework (GCNs&RNNs) based on time-varying observation data to control the influence of confounders, and integrated data from different data sources
  *  Investigated the problem of causal inference and COVID-19 observational social network data  






