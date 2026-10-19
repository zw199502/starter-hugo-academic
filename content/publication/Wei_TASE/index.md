---
title: "TRAIN: Terrain-Aware Interactive Navigation for Quadruped Robots via Reinforcement Learning"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Irfan Tito Kurniawan
- Ye Zhao
- and Mitsuhiro Hayashibe


date: "2026-10-02T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Automation Science and Engineering (T-ASE)*
publication_short: In *IEEE Transactions on Automation Science and Engineering (T-ASE)*

abstract: This study introduces TRAIN -- TeRrain-Aware Interactive Navigation, a deep reinforcement learning (DRL)-based framework for quadrupedal navigation across unstructured terrain and human-populated environments. Conventional quadrupedal navigation typically separates motion planning from locomotion control, neglecting whole-body constraints and terrain awareness. On the other hand, end-to-end methods are more integrated but require high-frequency sensing, which is often noisy and computationally costly. In addition, most existing approaches assume static environments, limiting their use in human-populated settings. To address these limitations, we propose a two-stage training framework with three DRL pipelines. (1) TRAIN-Loco employs an asymmetric actor–critic (AC) model for quadrupedal locomotion, enabling agile traversal of uneven terrains without explicit terrain or contact observations. (2) TRAIN-Nav applies a symmetric AC framework for navigation with interactive pedestrians, directly mapping transformed LiDAR data to ego-agent actions under differential-drive kinematics. (3) A unified pipeline, TRAIN, integrates TRAIN-Loc and TRAIN-Nav, supporting terrain-aware quadrupedal navigation in uneven and interactive environments. Comprehensive benchmarks against quadrupedal locomotion and robot navigation baselines demonstrate the effectiveness of TRAIN. Hardware experiments further confirm its potential for sim-to-real transfer.


tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false
---



