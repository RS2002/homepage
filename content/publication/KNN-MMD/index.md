---
title: 'KNN-MMD: Cross Domain Wi-Fi Sensing Based on Local Distribution Alignment'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Zhijie Cai
  - Tingwei Chen
  - Xiaoyang Li
  - Hang Li
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

abstract: As a key technology in Integrated Sensing and Communications (ISAC), Wi-Fi sensing has gained widespread application in various settings such as homes, offices, and public spaces. By analyzing the patterns of Channel State Information (CSI), we can obtain information about people's actions for tasks like person identification, gesture recognition, and fall detection. However, the CSI is heavily influenced by the environment, such that even minor environmental changes can significantly alter the CSI patterns. This will cause the performance deterioration and even failure when applying the Wi-Fi sensing model trained in one environment to another. To address this problem, we introduce a K-Nearest Neighbors Maximum Mean Discrepancy (KNN-MMD) model, a few-shot method for cross-domain Wi-Fi sensing. We propose a local distribution alignment method within each category, which outperforms traditional Domain Adaptation (DA) methods based on global alignment. Besides, our method can determine when to stop training, which cannot be realized by most DA methods. As a result, our method is more stable and can be better used in practice. The effectiveness of our method are evaluated in several cross-domain Wi-Fi sensing tasks, including gesture recognition, person identification, fall detection, and action recognition, using both a public dataset and a self-collected dataset. In one-shot scenario, our method achieves accuracy of 93.26%, 81.84%, 77.62%, and 75.30% in the four tasks respectively. The dataset and code are publicly available at https://github.com/RS2002/KNN-MMD.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: true

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
