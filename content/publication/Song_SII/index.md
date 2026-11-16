---
title: "Small Dataset Imitation Learning for Humanoid Locomotion via Weight Curriculum Adversarial Motion Priors"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Xinyu Song
- admin
- and Mitsuhiro Hayashibe

date: "2026-11-02T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE/SICE International Symposium on System Integration (SII)*
publication_short: In *IEEE/SICE International Symposium on System Integration (SII)*

abstract: Developing humanoid robots capable of robust and generalizable locomotion from limited demonstration data remains a significant challenge. While Adversarial Motion Priors (AMP) effectively learn natural motion styles from human data, their performance in data-scarce regimes is often limited by poor extrapolation beyond the reference motions and an unstable trade-off between task performance and style fidelity. Manual tuning of reward weights in AMP can further lead to large policy-loss oscillations, hindering convergence. To address these issues, we propose Weight Curriculum AMP, a lightweight AMP variant designed for small-dataset training. Our method incorporates three key modifications -- (1) removing ankle-joint references from expert motions to decouple potentially destabilizing imitation from balance learning, (2) introducing a symmetry loss to promote stable, bilaterally symmetric gaits, and (3) using a fixed-increment schedule that shifts emphasis from style to task during an initial training phase. In the reported comparisons, our method achieves the lowest FID and symmetry loss among the evaluated baselines while retaining strong command tracking. Furthermore, a stress test of fixed-weight AMP on 15 million heterogeneous walking frames demonstrates that simply scaling up data does not inherently resolve the trade-offs among motion similarity, tracking, and symmetry. Finally, zero-shot deployment on a physical Unitree G1 humanoid validates the sim-to-real transferability of our learned policies.


tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_video: 'https://youtu.be/9xEgzlLs4qs'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false
---



