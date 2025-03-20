---
title: 'Let Network Decide What to Learn: Symbolic Music Understanding Model Based on Large-scale Adversarial Pre-training'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin

# Author notes (optional)
author_notes:


date: '2024-07-11T00:00:00Z'
doi: '10.48550/arXiv.2407.08306'

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *under review*
publication_short: In *under review*

abstract: As a crucial aspect of Music Information Retrieval (MIR), Symbolic Music Understanding (SMU) has garnered significant attention for its potential to assist both musicians and enthusiasts in learning and creating music. Recently, pre-trained language models have been widely adopted in SMU due to the substantial similarities between symbolic music and natural language, as well as the ability of these models to leverage limited music data effectively. However, some studies have shown the common pre-trained methods like Mask Language Model (MLM) may introduce bias issues like racism discrimination in Natural Language Process (NLP) and affects the performance of downstream tasks, which also happens in SMU. This bias often arises when masked tokens cannot be inferred from their context, forcing the model to overfit the training set instead of generalizing. To address this challenge, we propose Adversarial-MidiBERT for SMU, which adaptively determines what to mask during MLM via a masker network, rather than employing random masking. By avoiding the masking of tokens that are difficult to infer from context, our model is better equipped to capture contextual structures and relationships, rather than merely conforming to the training data distribution. We evaluate our method across four SMU tasks, and our approach demonstrates excellent performance in all cases. The code for our model is publicly available at https://github.com/RS2002/Adversarial-MidiBERT.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: 
#   url: 

url_pdf: 'https://arxiv.org/abs/2407.08306'
url_code: 'https://github.com/RS2002/Adversarial-MidiBERT'
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
