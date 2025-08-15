---
title: 'Does MMD Really Align? A Cross Domain Wireless Sensing Method via Local Distribution'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Zhijie Cai
  - Tingwei Chen
  - Xiaoyang Li
  - Hang Li
  - Qimei Chen
  - Guangxu Zhu

# Author notes (optional)
author_notes:


date: '2025-06-26T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *IEEE/CIC International Conference on Communications in China (ICCC) 2025*
publication_short: In *IEEE/CIC ICCC 2025*

abstract: In wireless sensing, Channel State Information (CSI) is commonly used for detecting human behavior, but its sensitivity to environmental changes can degrade performance when models trained in one environment are applied to another. To tackle this, Domain Alignment (DAL), particularly the Maximum Mean Discrepancy (MMD), is often employed to align the global distributions of source and target domains. However, DAL typically overlooks inter-category relationships, leading to misalignment even with global alignment. To address these limitations, we propose K-Nearest Neighbors Maximum Mean Discrepancy (KNN-MMD), a novel few-shot method for cross-domain wireless sensing. Our approach constructs a ``help set" using K-Nearest Neighbors (KNN) from the target domain, enabling local alignment within each category via MMD. We also address the instability often seen in cross-domain methods, where performance fluctuates between epochs, and the challenge of determining an optimal stopping point during training due to the lack of labeled data. Our method resolves this by excluding the support set from the target domain during training and uses it as a validation set for early stopping. We evaluate the effectiveness of KNN-MMD on cross-domain Wi-Fi gesture recognition and people identification tasks, achieving accuracy rates of 93.26% and 81.84% in one-shot scenarios. The dataset and code are publicly available at https://github.com/RS2002/KNN-MMD.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: 
#   url: 

url_pdf: ''
url_code: 'https://github.com/RS2002/KNN-MMD'
url_slides: 'projects/Adv-MidiBERT.pptx'

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
