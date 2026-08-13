---
title: 'Is Per-Agent Policy Composition Safe? Rethinking Successor-Feature Transfer in Cooperative Multi-Agent Reinforcement Learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Sen Li


# Author notes (optional)
author_notes:


date: '2026-08-12T00:00:00Z'
doi: 'https://doi.org/10.48550/arXiv.2608.11658'

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

abstract: Many reinforcement learning systems, from fleet management to traffic signal control, must serve an objective that changes dynamically after deployment, and retraining a policy for each new objective is prohibitively expensive. For a single agent, this problem is well understood --- successor features with generalized policy improvement, together with their universal extension, recombine a library of learned policies into a policy for any new objective, with a guarantee that the result is never worse than any policy in the library. However, multi-agent transfer has received far less attention, and the common practice of letting each agent recombine its own library independently inherits the recipe but not the guarantee. We prove that this independent composition can produce joint behavior strictly worse than every policy in the library, because recombining teammates changes the environment each agent faces and invalidates the values it relies on, a failure with no single-agent counterpart. We further show that the only unconditionally safe fixed rule is synchronized composition, which moves the whole team to one jointly trained policy but cannot serve objectives that assign different goals to different agents. To attain safety and flexibility at once, we propose MA-USFA, a hierarchical method with two layers --- a lower layer of universal successor feature approximators that predicts each agent's successor features while conditioned on its teammates' objectives, and an upper composer that selects, across agents, which library entry each agent should follow and supplies the cross-agent correction a per-agent value cannot represent. Trained once over the distribution of objectives, it is applied at deployment with no per-task adaptation.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: 
#   url: 

url_pdf: 'https://arxiv.org/abs/2608.11658'
url_code: 'https://github.com/RS2002/MA-USFA'
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
