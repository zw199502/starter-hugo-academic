---
# title: Sampling Efficient Deep Reinforcement Learning for Dynamic Navigation with Raw Laser Scans
title: Local Collision Avoidance for Unmanned Surface Vehicles based on an End-to-End Planner with a LiDAR Beam Map
subtitle:  submit for IEEE Transactions on Intelligent Transportation Systems (TITS).

# Summary for listings and search engines
summary: submit for IEEE Transactions on Intelligent Transportation Systems (TITS).
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
- Zhiting Yao
- Xiyuan Chen
- Mitsuhiro Hayashibe
- admin
- Ninghui Xu
---

Collision avoidance capability ensures the safe navigation of unmanned surface vehicles (USVs). This paper presents an end-to-end approach to local collision prevention in water surface environments, with an emphasis on augmenting the evasion of obstacles and the smoothness of navigation paths. The deep reinforcement learning (DRL) method is leveraged to directly project relative distance states into autonomous actions without cumbersome map maintenance. We introduce a novel observation modality known as a beam map, which precisely pinpoints obstacles in all directions. This new input modality, functioning in harmony with range sensors, imitates the operation of an on-board LiDAR system. Unlike prior methodologies that rely on discrete action spaces, our research utilizes a continuous action space that enables smoother paths and nuanced maneuvers. Additionally, warning zone and discomfort angle have been incorporated to allocate ample time and space for motion decision-making, promoting effective collision avoidance. Experiments, in comparison with advanced RL techniques and traditional navigation methods, demonstrate that our algorithm exhibits remarkable capability for obstacle avoidance and robust adaptability to environmental changes. With real inland ships navigation data, four steering situations have been designed to further confirm the efficacy of the proposed method.