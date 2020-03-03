---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S. in Software Engineering, École Polytechnique de Montréal, 2018
* Ph.D in Deep Learning, MILA / École Polytechnique de Montréal, 2022 (expected)

Research Interest
======
* Natural Language Processing
  * Exploring emerging properties from very large pre-trained models such as [BERT](https://arxiv.org/abs/1810.04805)
  * Zero-shot question answering as well as information embedding within a model's parameters.
  
* Meta-Learning
  * Application relating to Meta-Learning and 1D data such as time-series and text.
  
* Recurrence and Transformers
  * Understanding how non-recurrent approaches to 1D data, such as Transformers, compare with recurrent approaches.
  * Studying the importance of the dimensionality of sequences.

Work experience
======
* Summer 2018 - ongoing: Quantitative Research Scientist
  * Shell Street Labs
  * Conceptualize, develop and deliver trading strategies used to invest hundreds of millions of dollars

* Summer 2018: AI Research Intern
  * Ubisoft, LaForge
  * Implement and iterate with state of the art deep learning text to speech models

* Summer 2017: Data science Intern
  * Société Générale
  * Developed machine learning based solution to predictive maintenance on a wide array of technologies.
  
Kaggle
======
* Kaggle Master
  * Best global rank : 442th / 133469 Data scientist
  * Gendered Pronoun Resolution: Gold Medal
  * Jigsaw Unintended Bias in Toxicity Classification : Silver Medal
  * Sberbank Russian Housing Market: Silver Medal

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Open Source Project
======

* [PPO-Keras](https://github.com/LuEE-C/PPO-Keras)
  * The first implementation of [Proximal Policy Optimization](https://arxiv.org/abs/1707.06347) in the Keras framework.
  
* [FIGR](https://github.com/LuEE-C/FIGR)
  * Few-shot image generation by meta-training a [Generative Adversarial Network](https://arxiv.org/abs/1406.2661) with the [Reptile](https://arxiv.org/abs/1803.02999) algorithm.
  
* [FIGR-8](https://github.com/marcdemers/FIGR-8)
  * Dataset containing 1.5 million images in 17000 classes. Intended for few-shot classification or few-shot image generation tasks.
  
Perfectly trilingual: French, English and Python

