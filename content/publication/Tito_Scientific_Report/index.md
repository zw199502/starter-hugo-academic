---
title: "Synergy of Postural Adaptation and Exteroception for Robust CPG-driven Quadrupedal Locomotion"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Irfan Tito Kurniawan
- admin
- Dai Owaki
- and Mitsuhiro Hayashibe

date: "2026-06-02T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Scientific Reports*
publication_short: In *Scientific Reports*

abstract: Reinforcement learning (RL)-based controllers for quadrupedal locomotion often learn unnatural, uncoordinated gaits that are unsuitable for real-world deployment, necessitating laborious reward shaping. Central pattern generator (CPG)-RL approaches alleviate these issues by utilizing biologically inspired CPGs to generate rhythmic foot trajectories modulated by learned policies. While previous CPG-RL works have employed postural adaptation and exteroception to modify gait, their exact functional roles and distinct adjustment strategies remain largely unexplored. To systematically investigate the roles of these mechanisms, we augment CPG-RL with exteroception via terrain elevation samples and postural adaptation through direct joint angle corrections. Ablation experiments reveal that while exteroception facilitates energy-efficient anticipatory planning and accelerates balance recovery, its benefits are constrained by the rigidity of CPG modulation. Postural adaptation resolves this limitation, enabling the flexible limb motions required to translate terrain awareness into robust, stable, and accurate locomotion. We observe distinct emergent gait strategies -- exteroception drives precise, shorter steps to minimize collisions, whereas postural adaptation reduces step clearance for efficiency, relying on rapid reactions to maintain stability. The resulting synergy yields superior robustness compared to an end-to-end RL baseline, achieves a natural trot without gait-shaping rewards, and generalizes well to out-of-distribution conditions, establishing a foundation for configurable and reliable quadrupedal locomotion.


tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.nature.com/articles/s41598-026-55491-z'


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false
---



