---
title: 'SimNet: Learning reactive self-driving simulations from real-world observations'
authors:
  - Luca Bergamini
  - Yawei Ye
  - Oliver Scheel
  - admin
  - Chih Hu
  - Luca Del Pero
  - Błażej Osiński
  - Hugo Grimmett
  - Peter Ondruska
date: '2021-01-01'
doi: ''
publishDate: '2021-01-01'
publication_types: ['conference']
publication: In *2021 IEEE International Conference on Robotics and Automation (ICRA)*
abstract: "In this work, we present a simple end-to-end trainable machine learning system capable of realistically simulating driving experiences. This can be used for the verification of self-driving system performance without relying on expensive and time-consuming road testing. In particular, we frame the simulation problem as a Markov Process, leveraging deep neural networks to model both state distribution and transition function. These are trainable directly from the existing raw observations without the need for any handcrafting in the form of plant or kinematic models. All that is needed is a dataset of historical traffic episodes. Our formulation allows the system to construct never seen scenes that unfold realistically reacting to the self-driving car's behaviour. We train our system directly from 1,000 hours of driving logs and measure both realism, reactivity of the simulation as the two key properties of the simulation. At the same time, we apply the method to evaluate the performance of a recently proposed state-of-the-art ML planning system trained from human driving logs. We discover this planning system is prone to previously unreported causal confusion issues that are difficult to test by non-reactive simulation. To the best of our knowledge, this is the first work that directly merges highly realistic data-driven simulations with a closed-loop evaluation for self-driving vehicles. We make the data, code, and pre-trained models publicly available to further stimulate simulation development."
url_pdf: 'https://arxiv.org/pdf/2105.12332.pdf'
url_code: 'https://github.com/woven-planet/l5kit/blob/master/examples/simulation/simulation_test.ipynb'
url_dataset: ''
url_video: 'https://www.youtube.com/watch?v=qedl21IhWH8'
image:
  caption: ''
  focal_point: ''
  preview_only: false
tags: [featured]

---
