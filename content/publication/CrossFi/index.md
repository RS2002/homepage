---
title: 'CrossFi: A Cross Domain Wi-Fi Sensing Framework Based on Siamese Network'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Tingwei Chen
  - Zhijie Cai
  - Xinhao Li
  - Hang Li
  - Qimei Chen
  - Guangxu Zhu

# Author notes (optional)
author_notes:


date: '2024-08-21T00:00:00Z'
doi: 'https://doi.org/10.48550/arXiv.2408.10919'

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

abstract: In recent years, Wi-Fi sensing has garnered significant attention due to its numerous benefits, such as privacy protection, low cost, and penetration ability. Extensive research has been conducted in this field, focusing on areas such as gesture recognition, people identification, and fall detection. However, many data-driven methods encounter challenges related to domain shift, where the model fails to perform well in environments different from the training data. One major factor contributing to this issue is the limited availability of Wi-Fi sensing datasets, which makes models learn excessive irrelevant information and over-fit to the training set. Unfortunately, collecting large-scale Wi-Fi sensing datasets across diverse scenarios is a challenging task. To address this problem, we propose CrossFi, a siamese network-based approach that excels in both in-domain scenario and cross-domain scenario, including few-shot, zero-shot scenarios, and even works in few-shot new-class scenario where testing set contains new categories. The core component of CrossFi is a sample-similarity calculation network called CSi-Net, which improves the structure of the siamese network by using an attention mechanism to capture similarity information, instead of simply calculating the distance or cosine similarity. Based on it, we develop an extra Weight-Net that can generate a template for each class, so that our CrossFi can work in different scenarios. Experimental results demonstrate that our CrossFi achieves state-of-the-art performance across various scenarios. In gesture recognition task, our CrossFi achieves an accuracy of 98.17% in in-domain scenario, 91.72% in one-shot cross-domain scenario, 64.81% in zero-shot cross-domain scenario, and 84.75% in one-shot new-class scenario. he code for our model is publicly available at https://github.com/RS2002/CrossFi.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: 
#   url: 

url_pdf: 'https://arxiv.org/abs/2408.10919v1'
url_code: 'https://github.com/RS2002/CrossFi'

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
projects:
  - content/project/CrossFi/index.md

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: 
---
