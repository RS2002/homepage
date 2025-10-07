---
title: 'Zero-Effort Image-to-Music Generation: An Interpretable RAG-Based VLM Approach'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Dian Jin
  - Zijing Zhou

# Author notes (optional)
author_notes:


date: '2025-09-26T00:00:00Z'
doi: 'https://doi.org/10.48550/arXiv.2509.22378'

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

abstract: Recently, Image-to-Music (I2M) generation has garnered significant attention, with potential applications in fields such as gaming, advertising, and multi-modal art creation. However, due to the ambiguous and subjective nature of I2M tasks, most end-to-end methods lack interpretability, leaving users puzzled about the generation results. Even methods based on emotion mapping face controversy, as emotion represents only a singular aspect of art. Additionally, most learning-based methods require substantial computational resources and large datasets for training, hindering accessibility for common users. To address these challenges, we propose the first Vision Language Model (VLM)-based I2M framework that offers high interpretability and low computational cost. Specifically, we utilize ABC notation to bridge the text and music modalities, enabling the VLM to generate music using natural language. We then apply multi-modal Retrieval-Augmented Generation (RAG) and self-refinement techniques to allow the VLM to produce high-quality music without external training. Furthermore, we leverage the generated motivations in text and the attention maps from the VLM to provide explanations for the generated results in both text and image modalities. To validate our method, we conduct both human studies and machine evaluations, where our method outperforms others in terms of music quality and music-image consistency, indicating promising results. Our code is available at https://github.com/RS2002/Image2Music .

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: 
#   url: 

url_pdf: 'https://arxiv.org/abs/2509.22378'
url_code: 'https://github.com/RS2002/Image2Music'
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
