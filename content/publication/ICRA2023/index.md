---
title: "Learn to Navigate in Dynamic Environments with Normalized LiDAR Scans"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Mitsuhiro Hayashibe


date: "2023-10-01T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *2024 International Conference on Robotics and Automation (ICRA)*
publication_short: In *2024 International Conference on Robotics and Automation (ICRA)*

abstract: The latest robot navigation methods for dynamic environments assume that the states of obstacles, including their geometries and trajectories, are fully observable. While it’s easy to obtain these states accurately in simulations, it’s exceedingly challenging in the real world. Therefore, a viable alternative is to directly map raw sensor observations into robot actions. However, acquiring skills from high-dimensional raw observations demands massive neural networks and extended training periods. Furthermore, there are discrepancies between simulated and real environments that impede real-world implementations. To overcome these limitations, we propose a Learning framework for robot Navigation in Dynamic environments that uses sequential Normalized LiDAR (LNDNL) scans. We employ long-short-term memory (LSTM) to propagate historical environmental information from the sequential LiDAR observations. Additionally, we customize a LiDAR-integrated simulator to speed up sampling and normalize the geometry of real-world obstacles to match that of simulated objects, thereby bridging the sim-to-real gap. Our extensive comparisons with state-of-the-art baselines and real-world implementations demonstrate the potentials of learning to navigate in dynamic environments using raw sensor observations and sim-to-real transfer.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/document/10611247'
url_code: 'https://github.com/zw199502/LSTM_EGO'
url_video: 'https://youtu.be/Eiyp8V8EjWo'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false
---



