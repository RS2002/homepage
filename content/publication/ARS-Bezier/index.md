---
title: 'A Trajectory-based Reinforcement Learning Approach for Autonomous Locomotion of a Rat Robot'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Zitao Zhang
  - Kai Huang

# Author notes (optional)
author_notes:


date: '2024-06-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['4']

# Publication name and optional abbreviated publication name.
publication: In *ArXiv Technical Report*
publication_short: In *ArXiv Technical Report*

abstract: Developing effective strategies in complex environments has long been a challenge for small robots. Due to limited space, small robots often have scarce sensing and computation resources, making it difficult for them to comprehend the intricate nature of nonlinear dynamics and learn motion strategy from scratch. In this paper, we propose a novel lightweight trajectory-based reinforcement learning approach for enabling robots to learn adaptive motion in complex terrains. Our method leverages the Augmented Random Search (ARS) algorithm to optimize control parameters for Bezier curves, which in turn generate motion trajectories for the robot. The Bezier curves provide prior knowledge to decrease the learning difficulty, while ARS provides an efficient optimization strategy with small computation cost. Additionally, we design a simple environment randomization method that trains the robot in diverse environments, enabling it to learn a general strategy for walking and navigating obstacles instead of being limited to a specific scenario. We evaluate our method in various scenarios with different obstacles, and the experimental results demonstrate its superior performance with minimal computational cost.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: 
#   url: 

url_pdf: 'https://github.com/RS2002/ARS-Bezier/blob/main/ARS_Bezier.pdf'
url_code: 'https://github.com/RS2002/ARS-Bezier'
url_dataset: ''
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
