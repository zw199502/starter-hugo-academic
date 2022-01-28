---
title: "Reinforcement Learning based Hierarchical Control for Path Tracking of a Wheeled Bipedal Robot with Sim-to-Real Framework"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Fahad Raza
- and Mitsuhiro Hayashibe

date: "2022-01-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *2022 IEEE/SICE International Symposium on System Integration (SII 2022)*
publication_short: In *SII*

abstract: We propose a reinforcement learning (RL) based hierarchical control framework for path tracking of a wheeled bipedal robot. The framework consists of three control levels. 1) The high-level RL is used to obtain an optimal policy through trial and error in a simulated environment. 2) The middle-level Lyapunov-based non-linear controller is utilized to track a desired line with strong robustness and high stability. 3) The low-level PID-based controller is implemented to simultaneously achieve both balancing and velocity tracking for a physical wheeled bipedal robot in real world. Thanks to the middle-level controller, the offline trained policy in simulation can be directly employed on the physical robot in real time without tuning any parameters. Moreover, the high-level policy network is able to improve optimality and generality for the task of path tracking, as well to avoid the cumbersome process of manually tuning control gains. The experiment results in both simulation and real world demonstrate that the proposed hierarchical control framework can achieve quick, robust, and stable path tracking for a wheeled bipedal robot.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=B01vbc-Lx1Q'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false
---



