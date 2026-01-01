---
title: 'AutoFed: Manual-Free Federated Traffic Prediction via Personalized Prompt'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Yitong Shang
  - Sen Li


# Author notes (optional)
author_notes:


date: '2025-12-31T00:00:00Z'
doi: 'https://doi.org/10.48550/arXiv.2512.24625'

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

abstract: Accurate traffic prediction is essential for Intelligent Transportation Systems, including ride-hailing, urban road planning, and vehicle fleet management. However, due to significant privacy concerns surrounding traffic data, most existing methods rely on local training, resulting in data silos and limited knowledge sharing. Federated Learning (FL) offers an efficient solution through privacy-preserving collaborative training, however, standard FL struggles with the non-independent and identically distributed (non-IID) problem among clients. This challenge has led to the emergence of Personalized Federated Learning (PFL) as a promising paradigm. Nevertheless, current PFL frameworks require further adaptation for traffic prediction tasks, such as specialized graph feature engineering, data processing, and network architecture design. A notable limitation of many prior studies is their reliance on hyper-parameter optimization across datasets-information that is often unavailable in real-world scenarios-thus impeding practical deployment. To address this challenge, we propose AutoFed, a novel PFL framework for traffic prediction that eliminates the need for manual hyper-parameter tuning. Inspired by prompt learning, AutoFed introduces a federated representor that employs a client-aligned adapter to distill local data into a compact, globally shared prompt matrix. This prompt then conditions a personalized predictor, allowing each client to benefit from cross-client knowledge while maintaining local specificity. Extensive experiments on real-world datasets demonstrate that AutoFed consistently achieves superior performance across diverse scenarios. The code of this paper is provided at https://github.com/RS2002/AutoFed .

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: 
#   url: 

url_pdf: 'https://arxiv.org/abs/2512.24625'
url_code: 'https://github.com/RS2002/AutoFed'
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
