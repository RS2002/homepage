---
title: 'Stage Light is Sequence²: Multi-Light Control via Imitation Learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Dian Jin
  - Zijing Zhou
  - Xiaoyu Zhang


# Author notes (optional)
author_notes:


date: '2026-05-05T00:00:00Z'
doi: 'https://doi.org/10.48550/arXiv.2605.03660'

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

abstract: Music-inspired Automatic Stage Lighting Control (ASLC) has gained increasing attention in recent years due to the substantial time and financial costs associated with hiring and training professional lighting engineers. However, existing methods suffer from several notable limitations: the low interpretability of rule-based approaches, the restriction to single-primary-light control in music-to-color-space methods, and the limited transferability of music-to-controlling-parameter frameworks. To address these gaps, we propose SeqLight, a hierarchical deep learning framework that maps music to multi-light Hue-Saturation-Value (HSV) space. Our approach first customizes SkipBART, an end-to-end single primary light generation model, to predict the full light color distribution for each frame, followed by hybrid Imitation Learning (IL) techniques to derive an effective decomposition strategy that distributes the global color distribution among individual lights. Notably, the light decomposition module can be trained under varying venue-specific lighting configurations using only mixed light data and no professional demonstrations, thereby flexibly adapting across diverse venues. In this stage, we formulate the light decomposition task as a Goal-Conditioned Markov Decision Process (GCMDP), construct an expert demonstration set inspired by Hindsight Experience Replay (HER), and introduce a three-phase IL training pipeline, achieving strong generalization capability. To validate our IL solution for the proposed GCMDP, we conduct quantitative analysis to compare model performance across different training phases, demonstrating that our design effectively improves performance and generalization capacity. Furthermore, we also conduct a human study to evaluate SeqLight by comparing it with competitive baselines on music-conditioned light generation tasks across different music styles. The results show that SeqLight achieves the best overall preference scores in both in-domain and out-of-domain settings. The code and trained parameters are provided at https://github.com/RS2002/SeqLight .

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: 
#   url: 

url_pdf: 'https://arxiv.org/abs/2605.03660'
url_code: 'https://github.com/RS2002/SeqLight'
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
