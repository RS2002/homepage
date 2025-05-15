---
title: 'Mining Limited Data Sufficiently: A BERT-inspired Approach for CSI Time Series Application in Wireless Communication and Sensing'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Fanyi Meng
  - Hang Li
  - Xiaoyang Li
  - Guangxu Zhu

# Author notes (optional)
author_notes:


date: '2024-12-11T00:00:00Z'
doi: 'https://doi.org/10.48550/arXiv.2412.06861'

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

abstract: Channel State Information (CSI) is the cornerstone in both wireless communication and sensing systems. In wireless communication systems, CSI provides essential insights into channel conditions, enabling system optimizations like channel compensation and dynamic resource allocation. However, the high computational complexity of CSI estimation algorithms necessitates the development of fast deep learning methods for CSI prediction. In wireless sensing systems, CSI can be leveraged to infer environmental changes, facilitating various functions, including gesture recognition and people identification. Deep learning methods have demonstrated significant advantages over model-based approaches in these fine-grained CSI classification tasks, particularly when classes vary across different scenarios. However, a major challenge in training deep learning networks for wireless systems is the limited availability of data, further complicated by the diverse formats of many public datasets, which hinder integration. Additionally, collecting CSI data can be resource-intensive, requiring considerable time and manpower. To address these challenges, we propose CSI-BERT2 for CSI prediction and classification tasks, effectively utilizing limited data through a pre-training and fine-tuning approach. Building on CSI-BERT1, we enhance the model architecture by introducing an Adaptive Re-Weighting Layer (ARL) and a Multi-Layer Perceptron (MLP) to better capture sub-carrier and timestamp information, effectively addressing the permutation-invariance problem. Furthermore, we propose a Mask Prediction Model (MPM) fine-tuning method to improve the model's adaptability for CSI prediction tasks. Experimental results demonstrate that CSI-BERT2 achieves state-of-the-art performance across all tasks with relatively fast computation speeds. To facilitate future research, we will make our code and dataset publicly available upon publication. The dataset and code are publicly available at https://github.com/RS2002/CSI-BERT2.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: 
#   url: 

url_pdf: 'https://arxiv.org/abs/2412.06861'
url_code: 'https://github.com/RS2002/CSI-BERT2'

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
