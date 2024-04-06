---
title: 'What data do we need for training an av motion planner?'
authors:
  - admin
  - Lukas Platinsky
  - Stefanie Speichert
  - Błażej Osiński
  - Oliver Scheel
  - Yawei Ye
  - Hugo Grimmett
  - Luca Del Pero
  - Peter Ondruska
date: '2021-01-01'
doi: ''
publishDate: '2021-01-01'
publication_types: ['conference']
publication: In *2021 IEEE International Conference on Robotics and Automation (ICRA)*
abstract: 'We investigate what grade of sensor data is required for training an imitation-learning-based AV planner on human expert demonstration. Machine-learned planners are very hungry for training data, which is usually collected using vehicles equipped with the same sensors used for autonomous operation. This is costly and non-scalable. If cheaper sensors could be used for collection instead, data availability would go up, which is crucial in a field where data volume requirements are large and availability is small. We present experiments using up to 1000 hours worth of expert demonstration and find that training with 10x lower-quality data outperforms 1x AV-grade data in terms of planner performance. The important implication of this is that cheaper sensors can indeed be used. This serves to improve data access and democratize the field of imitation-based motion planning. Alongside this, we perform a sensitivity analysis of planner performance as a function of perception range, field-of-view, accuracy, and data volume, and the reason why lower-quality data still provide good planning results.'
url_pdf: 'https://arxiv.org/pdf/2105.12337.pdf'
url_code: 'https://colab.research.google.com/github/lyft/l5kit/blob/master/examples/planning/train.ipynb'
url_dataset: ''
url_video: 'https://www.youtube.com/watch?v=QzKrhGgbUew'
tags: [featured]
image:
  caption: ''
  focal_point: ''
  preview_only: False
featured: false
---
