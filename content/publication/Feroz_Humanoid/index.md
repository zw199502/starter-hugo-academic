---
title: "Body-Aware Semantic Topological Representation for Humanoid Robot Spatial Understanding"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Feroz Fernando
- Mitsuhiro Hayashibe
- admin

date: "2026-09-02T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE-RAS International Conference on Humanoid Robots*
publication_short: In *IEEE-Humanoid*

abstract: A humanoid working in human environments requires spatial understanding to know where objects are and which passages its body can physically traverse. Traditional 3D scene graphs address the environment side, but fail humanoids in two ways -- per-frame mapping latency grows as the map accumulates and purely environment-centric maps read duckable passages as solid walls. We present a bodyaware spatial representation addressing both limitations. Perframe work is bounded to a local active window, fusing frames into distance fields and condensing them into a sparse freespace graph. Edges retain clearance-versus-height profiles to derive necessary postures (walk, duck, hop, sidestep) and separate observed obstacles from unobserved space. Across 18 timing runs, our per-frame latency remains within a 1.5x band despite 35x map growth, versus 3.3x-42x growth for Hydra. In simulated trials with a Unitree G1, our posture-labeled memory achieves route success rates of 0.78 (24 procedural buildings) and 0.59 (55 room-to-room home tasks), compared to 0.26 and 0.43 for 2D maps. The persistent profiles also handle posttour queries—for modified body dimensions, lost postures, or language goals—without new observation.


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



