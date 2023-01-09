---
# title: Sampling Efficient Deep Reinforcement Learning for Dynamic Navigation with Raw Laser Scans
title: An Autonomous Navigation System among Pedestrians with a Dreamer based Motion Planner
subtitle:  in preparation for submission to IEEE Robotics and Automation Letters (RA-L), [Paper video](https://youtu.be/RVfYF8jYBsQ).

# Summary for listings and search engines
summary: in preparation for submission to IEEE Robotics and Automation Letters (RA-L).
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)'
#   focal_point: ""
#   placement: 2
#   preview_only: false

authors:
- admin
- Mitsuhiro Hayashibe
---

Navigation among pedestrians is a crucial capability for service robots, which is however challenging to stably master. Recent deep reinforcement learning (DRL) based approaches for crowd navigation have yielded numerous promising applications. However, they heavily rely on initial imitation learning and colossal positive dataset. Moreover, the difficulties of accurately localizing robots, detecting and tracking humans, and predicting reciprocal human motions limit the sim-to-real transfer. We propose a model-based DRL framework for collision-free motion planning, which can represent the interaction dynamics and completely learn from zero experience. The robot and humans are projected on a map, which is decoded into low-dimensional latent features. A dynamics in the latent space is created to efficiently learn a motion planner. Additionally, we leverage the techniques of system identification, domain randomization, and LiDAR SLAM for practical applications. Simulation ablations and real implementations demonstrate that our navigation system outperforms state-of-the-art methods and can be transferred into physical worlds.
