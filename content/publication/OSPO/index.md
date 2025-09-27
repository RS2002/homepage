---
title: 'One Step is Enough: Multi-Agent Reinforcement Learning based on One-Step Policy Optimization for Order Dispatch on Ride-Sharing Platforms'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Sen Li


# Author notes (optional)
author_notes:


date: '2025-07-22T00:00:00Z'
doi: 'https://doi.org/10.48550/arXiv.2507.15351'

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: In *under review*
publication_short: In *under review*

abstract: On-demand ride-sharing platforms face the fundamental challenge of dynamically bundling passengers with diverse origins and destinations and matching them with vehicles in real time, all under significant uncertainty. Recently, MARL has emerged as a promising solution for this problem, leveraging decentralized learning to address the curse of dimensionality caused by the large number of agents in the ride-hailing market and the resulting expansive state and action spaces. However, conventional MARL-based ride-sharing approaches heavily rely on the accurate estimation of Q-values or V-values, which becomes problematic in large-scale, highly uncertain environments. Specifically, most of these approaches adopt an independent paradigm, exacerbating this issue, as each agent treats others as part of the environment, leading to unstable training and substantial estimation bias in value functions. To address these challenges, we propose two novel alternative methods that bypass value function estimation. First, we adapt GRPO to ride-sharing, replacing the PPO baseline with the group average reward to eliminate critic estimation errors and reduce training bias. Second, inspired by GRPO's full utilization of group reward information, we customize the PPO framework for ride-sharing platforms and show that, under a homogeneous fleet, the optimal policy can be trained using only one-step rewards - a method we term One-Step Policy Optimization (OSPO). Experiments on a real-world Manhattan ride-hailing dataset demonstrate that both GRPO and OSPO achieve superior performance across most scenarios, efficiently optimizing pickup times and the number of served orders using simple MLP networks. Our code, trained models, and processed data are publicly available at therepository https://github.com/RS2002/OSPO .

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: 
#   url: 

url_pdf: 'https://arxiv.org/abs/2507.15351'
url_code: 'https://github.com/RS2002/OSPO'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: 
---
