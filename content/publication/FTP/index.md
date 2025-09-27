---
title: 'First Token Probability Guided RAG for Telecom Question Answering'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Tingwei Chen
  - Jiayi Chen
  - admin
  - Haolong Chen
  - Liang Zhang
  - Guangxu Zhu


# Author notes (optional)
author_notes:


date: '2025-01-14T00:00:00Z'
doi: 'https://doi.org/10.48550/arXiv.2501.06468'

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

abstract: Large Language Models (LLMs) have garnered significant attention for their impressive general-purpose capabilities. For applications requiring intricate domain knowledge, Retrieval-Augmented Generation (RAG) has shown a distinct advantage in incorporating domain-specific information into LLMs. However, existing RAG research has not fully addressed the challenges of Multiple Choice Question Answering (MCQA) in telecommunications, particularly in terms of retrieval quality and mitigating hallucinations. To tackle these challenges, we propose a novel first token probability guided RAG framework. This framework leverages confidence scores to optimize key hyperparameters, such as chunk number and chunk window size, while dynamically adjusting the context. Our method starts by retrieving the most relevant chunks and generates a single token as the potential answer. The probabilities of all options are then normalized to serve as confidence scores, which guide the dynamic adjustment of the context. By iteratively optimizing the hyperparameters based on these confidence scores, we can continuously improve RAG performance. We conducted experiments to validate the effectiveness of our framework, demonstrating its potential to enhance accuracy in domain-specific MCQA tasks.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: 
#   url: 

url_pdf: 'https://arxiv.org/abs/2501.06468'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''


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
