---
title: 'Modelling the 5G Energy Consumption using Real-world Data: Energy Fingerprint is All You Need'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Tingwei Chen
  - Yantao Wang
  - Hanzhi Chen
  - admin
  - Xinhao Li
  - Nicola Piovesan
  - Guangxu Zhu
  - Qingjiang Shi

# Author notes (optional)
author_notes:


date: '2024-06-13T00:00:00Z'
doi: 'https://doi.org/10.48550/arXiv.2406.16929'

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

abstract: The introduction of fifth-generation (5G) radio technology has revolutionized communications, bringing unprecedented automation, capacity, connectivity, and ultra-fast, reliable communications. However, this technological leap comes with a substantial increase in energy consumption, presenting a significant challenge. To improve the energy efficiency of 5G networks, it is imperative to develop sophisticated models that accurately reflect the influence of base station (BS) attributes and operational conditions on energy usage.Importantly, addressing the complexity and interdependencies of these diverse features is particularly challenging, both in terms of data processing and model architecture design. This paper proposes a novel 5G base stations energy consumption modelling method by learning from a real-world dataset used in the ITU 5G Base Station Energy Consumption Modelling Challenge in which our model ranked second. Unlike existing methods that omit the Base Station Identifier (BSID) information and thus fail to capture the unique energy fingerprint in different base stations, we incorporate the BSID into the input features and encoding it with an embedding layer for precise representation. Additionally, we introduce a novel masked training method alongside an attention mechanism to further boost the model's generalization capabilities and accuracy. After evaluation, our method demonstrates significant improvements over existing models, reducing Mean Absolute Percentage Error (MAPE) from 12.75% to 4.98%, leading to a performance gain of more than 60%.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: 
#   url: 

url_pdf: 'https://arxiv.org/abs/2406.16929'
url_code: 'https://github.com/RS2002/ARL'

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
