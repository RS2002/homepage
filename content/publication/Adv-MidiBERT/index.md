---
title: 'Adversarial-MidiBERT: Symbolic Music Understanding Model Based on Unbias Pre-training and Mask Fine-tuning'

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

abstract: As an important part of Music Information Retrieval (MIR), Symbolic Music Understanding (SMU) has gained substantial attention, as it can assist musicians and amateurs in learning and creating music. Recently, pre-trained language models have been widely adopted in SMU because the symbolic music shares a huge similarity with natural language, and the pre-trained manner also helps make full use of limited music data. However, the issue of bias, such as sexism, ageism, and racism, has been observed in pre-trained language models, which is attributed to the imbalanced distribution of training data. It also has a significant influence on the performance of downstream tasks, which also happens in SMU. To address this challenge, we propose Adversarial-MidiBERT, a symbolic music understanding model based on Bidirectional Encoder Representations from Transformers (BERT). We introduce an unbiased pre-training method based on adversarial learning to minimize the participation of tokens that lead to biases during training. Furthermore, we propose a mask fine-tuning method to narrow the data gap between pre-training and fine-tuning, which can help the model converge faster and perform better. We evaluate our method on four music understanding tasks, and our approach demonstrates excellent performance in all of them. The code for our model is publicly available at https://github.com/RS2002/Adversarial-MidiBERT.

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
projects:
  - content/project/Adversarial-MidiBERT/index.md

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: 
---
