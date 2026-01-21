---
title: TRANCE Terrain-aware Reinforcement Learning for Agile Navigation of Quadruped Robots in Crowded Environments
subtitle:  submit for IEEE ***.

# Summary for listings and search engines
summary: submit for IEEE ***.
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
- Irfan Tito Kurniawan
- Ye Zhao
- Mitsuhiro Hayashibe
---

This study introduces TRANCE: Terrain-aware Reinforcement learning for Agile Navigation in Crowded Environments, a deep reinforcement learning (DRL) framework for quadrupedal navigation. Conventional quadrupedal navigation typically separates motion planning from locomotion control, neglecting whole-body constraints and terrain awareness. End-to-end methods are more integrated but require high-frequency sensing, which is noisy and computationally costly. In addition, most existing approaches assume static environments, limiting their use in human-populated settings. To address these limitations, we propose a two-stage training framework with three DRL pipelines. (1) TRANCE-Loco employs an asymmetric actor–critic (AC) model for quadrupedal locomotion, enabling traversal of uneven terrains without explicit terrain or contact observations. (2) TRANCE-Nav applies a symmetric AC framework for crowd navigation, directly mapping transformed LiDAR data to ego-agent actions under differential-drive kinematics. (3) A unified pipeline, TRANCE, integrates TRANCE-Loco and TRANCE-Nav, supporting terrain-aware quadrupedal navigation in uneven and crowded environments. Comprehensive benchmarks against locomotion and crowd-navigation baselines demonstrate the effectiveness of TRANCE. Hardware experiments further confirm its potential for sim-to-real transfer.