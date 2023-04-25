---
# title: Sampling Efficient Deep Reinforcement Learning for Dynamic Navigation with Raw Laser Scans
title: Sampling Efficient Deep Reinforcement Learning for Dynamic Navigation with Raw Laser Scans
subtitle:  IEEE/ASME Transactions on Mechatronics, under review for six months, [Paper video](https://youtu.be/wL3-diEXMes).

# Summary for listings and search engines
summary: IEEE/ASME Transactions on Mechatronics, reject and resubmit, [PDF](uploads/TMECH.pdf), [Video](https://youtu.be/wL3-diEXMes).
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)'
  focal_point: ""
  placement: 2
  preview_only: false

authors:
- admin
- Mitsuhiro Hayashibe
---

We present a Sampling Efficient deep reinforcement learning (DRL) framework for Dynamic Navigation (SEDN) directly using raw laser scans. To accelerate the running of DRL training and simulate the laser sensor, we specially designed a kinematics-based simulator, where the learned policy can be directly transferred into a physics-based Gazebo simulator and the real world. Moreover, the policy acquired from a specific environment can be directly generalized to other diverse environments that have never been explored by the DRL model. To individually extract the motion features of surroundings, we transformed the center of the previous laser scans into the center of the current laser sensor. After processing the transformed laser scans with convoluted neural networks, the abstract features which state predictions for other moving objects, can be extracted for further DRL neural networks. To further enhance the sampling efficiency, and thus, optimize the navigation policy quickly and stably, we integrate optimal reciprocal collision avoidance (ORCA) to generate auxiliary action alternatives. Various experiments against several state-of-the-art baselines and sim-to-real implementations demonstrate a high success rate of dynamic navigation, superior generality, simulator effectiveness, and efficient sampling of our approach.
