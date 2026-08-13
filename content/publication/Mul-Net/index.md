---
title: 'Low-Interaction-Rank Learning: Unifying Multiplicative Dual-Encoder Heads'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Sen Li


# Author notes (optional)
author_notes:


date: '2026-08-12T00:00:00Z'
doi: 'https://doi.org/10.48550/arXiv.2608.11661'

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

abstract: A multiplicative dual-encoder network computes a real-valued output for a pair of inputs as the inner product of their separate encodings. This architecture has been developed independently in operator learning, bipartite matching, contrastive vision-language models, retrieval, and other areas, yet no unified theory guides the basic design decisions --- how many interaction modes to represent, how to normalize the encoders, and when the architecture should be avoided. We provide such a foundation by introducing the class of functions of low interaction rank, a class whose intrinsic complexity is measured by its interaction spectrum. Within this framework, approximation error decomposes into a spectral truncation term and an encoder-realization term; sample complexity is governed by the sum of the two encoder complexities rather than their product; and a usability criterion based on spectral decay determines when the architecture can succeed. The same framework exposes a central identifiability problem --- the encoders are defined only up to a linear gauge symmetry that leaves the learned coordinates arbitrary. We show that normalization is gauge fixing and that whitening pins the interaction modes up to permutation and sign, thereby explaining the uninterpretability of contrastive dimensions and providing a constructive remedy. Experiments on synthetic kernels, operator learning, and CLIP models validate the theoretical predictions --- spectral decay rates match the predicted scaling, whitening recovers the true modes, and independently trained CLIP models are related by a single rotation which, after removal by whitening, exposes interpretable concept axes.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: 
#   url: 

url_pdf: 'https://arxiv.org/abs/2608.11661'
url_code: 'https://github.com/RS2002/Mul-Net'
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
