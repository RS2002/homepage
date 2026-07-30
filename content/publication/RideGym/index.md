---
title: 'RideGym: A Standardized Interface for Real-World Large-Scale Ride-Sharing System'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Yulong Hu
  - Sen Li


# Author notes (optional)
author_notes:


date: '2026-07-11T00:00:00Z'
doi: 'https://doi.org/10.48550/arXiv.2607.10173'

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

abstract: Ride-sharing has become an essential component of modern urban transportation and has attracted significant attention across computer science, transportation, and management science. While the field spans a broad range of problems, such as driver relocation, dynamic pricing, and vehicle charging or fueling dispatch, the core challenge remains order assignment and trip bundling, which directly affect urban traffic efficiency and carbon emissions. Despite its importance, existing simulation platforms are typically tailored to specific operational studies or tightly coupled to a particular dispatch algorithm, and rarely expose a standardized, learning-friendly interface. As a result, most researchers still build customized environments from scratch, raising serious concerns about reproducibility and fair comparison, and incurring substantial redundant effort. To address this gap, we present RideGym, the first open-source, standardized Gym-style interface tailored to Multi-Agent Reinforcement Learning (MARL)-based order dispatch in real-world ride-sharing systems. By fully decoupling the environment from the dispatch algorithm, RideGym enables diverse learning-based and model-based methods to be developed and compared under identical, fully specified conditions. It supports efficient, large-scale city-level simulations on real road networks, and offers flexible configurations for vehicle attributes (e.g., personalized speeds and capacities), order specifications (e.g., multiple passengers per order), and automatic shortest-path routing. We validate RideGym by reproducing several baselines, and demonstrate its high efficiency, with a one-hour simulation involving thousands of vehicles and tens of thousands of orders completed within one minute across all methods. Moreover, we reveal that the choice of exploration noise can significantly affect both the performance and the relative ranking of MARL solutions, an aspect often overlooked in prior work. Our code is available at https://github.com/RS2002/RideGym, and the Python package can be installed via pip install ride-gym.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: 
#   url: 

url_pdf: 'https://arxiv.org/abs/2607.10173'
url_code: 'https://github.com/RS2002/RideGym'
url_dataset: ''
url_poster: ''
url_project: 'https://pypi.org/project/ride-gym/'
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
