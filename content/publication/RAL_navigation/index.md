---
title: "Autonomous Navigation System in Pedestrian Scenarios using a Dreamer based Motion Planner"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- and Mitsuhiro Hayashibe

date: "2023-04-01T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Robotics and Automation Letters (RA-L)*
publication_short: In *IEEE Robotics and Automation Letters (RA-L)*

abstract: Navigation among pedestrians is a crucial capability of service robots; however, it is a challenge to manage time-varying environments stably. Recent deep reinforcement learning (DRL)-based approaches to crowd navigation have yielded numerous promising applications. However, they rely heavily on initial imitation learning and colossal positive datasets. Moreover, the difficulties in accurately localizing robots, detecting and tracking humans, representing and generalizing reciprocal human relationships restrict their deployment in real-world problems. We propose a Dreamer-based motion planner for collision-free navigation in diverse pedestrian scenarios. Our RL framework can completely learn from zero experience via a model-based DRL. The robot and humans are first projected onto a map, which is subsequently decoded into low-dimensional latent state. A predictive dynamic model in the latent space is jointly created to efficiently optimize the navigation policy. Additionally, we leverage the techniques of system identification, domain randomization, clustering and LiDAR SLAM for practical deployment. Simulation ablations and real implementations demonstrate that our motion planner outperforms state-of-the-art methods, and that the navigation system can be physically implemented in the real world.


tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_video: 'https://youtu.be/KM2WPpQBfrI'
url_pdf: 'https://ieeexplore.ieee.org/abstract/document/8556369'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false
---




