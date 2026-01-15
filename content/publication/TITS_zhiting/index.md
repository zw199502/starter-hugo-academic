---
title: "Local Collision Avoidance for Unmanned Surface Vehicles based on an End-to-End Planner with a LiDAR Beam Map"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Zhiting Yao
- Xiyuan Chen
- Mitsuhiro Hayashibe
- admin
- and Ninghui Xu

date: "2025-08-01T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Intelligent Transportation Systems (TITS)*
publication_short: In *IEEE Transactions on Intelligent Transportation Systems (TITS, IF7.9)*

abstract: Collision avoidance is critical for ensuring the safe navigation of unmanned surface vehicles (USVs). This paper presents an end-to-end solution for local path planning of USVs, focusing on enhanced obstacle evasion and smoother navigation. By leveraging deep reinforcement learning (DRL), we enable direct translation of relative distance states into navigational actions, eliminating the need for cumbersome map maintenance and complex feature extraction. A novel observation modality, the beam map, is designed to accurately perceive obstacles in all directions, mimicking the functionality of an onboard LiDAR system. To further refine collision avoidance maneuver, a warning zone is introduced, adjusting the agent’s sensitivity to obstacles and allowing ample time and space for decision-making. Additionally, we propose a continuous-time short-distance constraint to calculate the International Regulations for Preventing Collision at Sea (COLREGs) adherence rewards, enabling legal and rational navigation without requiring prior knowledge of the encounter situation. Extensive experimental results, comparing various RL policies and classical methods, demonstrate the planner’s exceptional obstacle avoidance capability and adaptability to changing environments. Using real-world inland ship navigation data, four steering scenarios are designed to further validate the efficacy of the proposed method.


tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/10959017'


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false
---



