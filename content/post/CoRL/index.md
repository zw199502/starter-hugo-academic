---
# title: Sampling Efficient Deep Reinforcement Learning for Dynamic Navigation with Raw Laser Scans
title: Learn to Navigate in Dynamic Environments with Normalized LiDAR Scans
subtitle:  in preparation for submission to Conference of Robot Learning (CoRL), [Paper video](https://youtu.be/sGKk0_fSDGM).

# Summary for listings and search engines
summary: in preparation for submission to Conference of Robot Learning (CoRL), [Video](https://youtu.be/sGKk0_fSDGM).
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

Firstly, we designed a simulator that is equipped with a LiDAR sensor, which significantly accelerates running during DRL training. Secondly, to simulate real-world scenarios, we assume that dynamic humans have a fixed circle shape, and static obstacles are rectangles with variable sizes. However, since the contours of real-world obstacles are notably different from the shapes of simulated objects, we normalized the collision margins of real-world obstacles as circles with a fixed radius or rectangles with variable sizes. We accomplished this by employing clustering algorithms to localize and frame moving humans or static obstacles, and obtain their centroids and circumscribed cuboids in 3D space. We can then normalize obstacles as circles or rectangles on a 2D plane. Subsequently, we can re-generate 2D LiDAR scans according to the normalized obstacles. Thirdly, instead of using tens of continuous LiDAR scans or high-dimensional depth images which require colossal networks to decode, we leverage long-short term memory (LSTM) to process ego-centric sequential LiDAR scans, which reduces the consumption of hardware resources and enables deployment on small mobile robots.
