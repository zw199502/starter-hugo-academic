---
title: "A Path-Integral-Based Reinforcement Learning Algorithm for Path Following of an Auto-Assembly Mobile Robot"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Xian Guo
- Yongchun Fang
- and Xueyou Zhang

date: "2020-11-01T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Neural Networks and Learning Systems (TNNLS)*
publication_short: In *IEEE Transactions on Neural Networks and Learning Systems (TNNLS)*

abstract: Reinforcement learning (RL) combined with deep neural networks has led to a number of great achievements for robot control in virtual computer environments, where sufficient data can be obtained without any difficulty to train various models. However, thus far, only few and relatively simple tasks have been accomplished for practical robots, which is mainly caused by the following two reasons. First, training with real robots, especially with dynamic systems, is too complicated to be fully and accurately represented in simulations. Second, it is very costly to obtain training data from real systems. To address these two problems effectively, in this article, a path-integral-based RL algorithm is proposed for the task of path following of an autoassembly mobile robot, wherein three kernel techniques are introduced. First, a generalized path-integral-control approach is proposed to obtain the numerical solution of a stochastic dynamical system, wherein the calculation of the gradient and kinematics inverse is avoided to ensure fast and reliable training convergence. Second, a novel parameterization method using Lyapunov techniques is introduced into the RL algorithm to ensure good performance of the system when directly transferring simulation results into practical systems. Third, the optimal parameters for all discrete initial states are first learned offline and then tuned online to improve the generalization and real-time performance. In addition to the optimization control for the mobile robot, the proposed method also possesses general applicability for a class of nonlinear systems such as crane systems. Simulation and experimental results are included and analyzed to illustrate the superior performance of the proposed algorithm.


tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/8941307'
url_code: 'https://github.com/zw199502/path_integral_reinforcement_learning'
url_video: 'https://youtu.be/JoDzcbL7mfo'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false
---



