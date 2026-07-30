---
title: 'Aggregate in the Advantage, Not the Ratio: A Canonical-Form Analysis of Cooperative Multi-Agent Policy Optimization'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Sen Li


# Author notes (optional)
author_notes:


date: '2026-07-20T00:00:00Z'
doi: 'https://doi.org/10.48550/arXiv.2607.17924'

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

abstract: Multi-agent policy optimization, exemplified by PPO-based methods, is a key branch of cooperative Multi-Agent Reinforcement Learning (MARL). A central design question is how many neighboring agents to aggregate in order to effectively utilize global information for cooperation. This decision must be made along two dimensions -- in the advantage (which agents' rewards contribute to the credit signal) and in the ratio (which agents' likelihood ratios form the clipped importance weight). Existing methods occupy scattered, underexplored points on these two axes -- IPPO treats both separately; MAPPO pairs a team-level advantage with per-agent ratios; HAPPO employs sequential ratios with per-agent advantages; and single-agent reductions operating on factorized joint policies aggregate both into fully joint products. We formalize these two design choices as support matrices $\SA$ and $\SR$, and prove a canonical structure -- the expected multi-agent policy optimization objective depends on the pair $(\SA,\SR)$ only through their matrix product $\tS=\SR\SA$. This yields two key consequences (i) Redundancy -- the two support matrices are interchangeable with respect to the signal, meaning neither aggregation pattern is inherently superior.(ii) Variance Ordering -- the advantage aggregates rewards as a sum (additive variance with an interior bias-variance optimum at the coupling neighborhood), whereas the ratio aggregates likelihood ratios as a product (multiplicative variance that grows exponentially with support size, with no accompanying bias reduction). The resulting design principle is unambiguous -- aggregate neighbors in the advantage, sized to the coupling neighborhood, and keep the ratio per-agent.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: 
#   url: 

url_pdf: 'https://arxiv.org/abs/2607.17924'
url_code: 'https://github.com/RS2002/MAPO'
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
