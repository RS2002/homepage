---
title: 'KNN-MMD: Cross Domain Wireless Sensing via Local Distribution Alignment'

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


date: '2024-12-09T00:00:00Z'
doi: 'https://doi.org/10.48550/arXiv.2412.04783'

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

abstract: Wireless sensing has recently found widespread applications in diverse environments, including homes, offices, and public spaces. By analyzing patterns in channel state information (CSI), it is possible to infer human actions for tasks such as person identification, gesture recognition, and fall detection. However, CSI is highly sensitive to environmental changes, where even minor alterations can significantly distort the CSI patterns. This sensitivity often leads to performance degradation or outright failure when applying wireless sensing models trained in one environment to another. To address this challenge, Domain Alignment (DAL) has been widely adopted for cross-domain classification tasks, as it focuses on aligning the global distributions of the source and target domains in feature space. Despite its popularity, DAL often neglects inter-category relationships, which can lead to misalignment between categories across domains, even when global alignment is achieved. To overcome these limitations, we propose K-Nearest Neighbors Maximum Mean Discrepancy (KNN-MMD), a novel few-shot method for cross-domain wireless sensing. Our approach begins by constructing a ``help set" using K-Nearest Neighbors (KNN) from the target domain, enabling local alignment between the source and target domains within each category using Maximum Mean Discrepancy (MMD). Additionally, we address a key instability issue commonly observed in cross-domain methods, where model performance fluctuates sharply between epochs. Further, most existing methods struggle to determine an optimal stopping point during training due to the absence of labeled data from the target domain. Our method resolves this by excluding the support set from the target domain during training and employing it as a validation set to determine the stopping criterion. We evaluate the effectiveness of the proposed method across several cross-domain Wi-Fi sensing tasks, including gesture recognition, person identification, fall detection, and action recognition, using both a public dataset and a self-collected dataset. In a one-shot scenario, our method achieves accuracy rates of 93.26%, 81.84%, 77.62%, and 75.30% for the respective tasks. To support future research, we will release our code and dataset to the public upon publication. The dataset and code are publicly available at https://github.com/RS2002/KNN-MMD.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: 
#   url: 

url_pdf: 'https://arxiv.org/abs/2412.04783'
url_code: 'https://github.com/RS2002/KNN-MMD'

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
