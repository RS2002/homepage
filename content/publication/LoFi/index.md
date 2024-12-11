---
title: 'LoFi: Vision-Aided Label Generator for Wi-Fi Localization and Tracking'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Tingwei Chen
  - Fanyi Meng
  - Zhijie Cai
  - Hang Li
  - Xiaoyang Li
  - Guangxu Zhu

# Author notes (optional)
author_notes:


date: '2024-12-09T00:00:00Z'
doi: 'https://doi.org/10.48550/arXiv.2412.05074'

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *under review*
publication_short: In *under review*

abstract: Wi-Fi localization and tracking has shown immense potential due to its privacy-friendliness, wide coverage, permeability, independence from lighting conditions, and low cost. Current methods can be broadly categorized as model-based and data-driven approaches, where data-driven methods show better performance and have less requirement for specialized devices, but struggle with limited datasets for training. Due to limitations in current data collection methods, most datasets only provide coarse-grained ground truth (GT) or limited amount of label points, which greatly hinders the development of data-driven methods. Even though lidar can provide accurate GT, their high cost makes them inaccessible to many users. To address these challenges, we propose LoFi, a vision-aided label generator for Wi-Fi localization and tracking, which can generate ground truth position coordinates solely based on 2D images. The easy and quick data collection method also helps data-driven based methods deploy in practice, since Wi-Fi is a low-generalization modality and when using relevant methods, it always requires fine-tuning the model using newly collected data. Based on our method, we also collect a Wi-Fi tracking and localization dataset using ESP32-S3 and a webcam. The dataset and code are publicly available at https://github.com/RS2002/LoFi.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: 
#   url: 

url_pdf: 'https://arxiv.org/abs/2412.05074'
url_code: 'https://github.com/RS2002/LoFi'

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
