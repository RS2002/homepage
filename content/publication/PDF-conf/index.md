---
title: 'Multi-Agent Reinforcement Learning for Order Assignment and Payment Setting on Food-Delivery Platforms: The Implicit Algorithmic Biases'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Sen Li


# Author notes (optional)
author_notes:


date: '2025-04-16T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *International Symposium on Transportation Data & Modelling 2025*
publication_short: In *ISTDM 2025*

abstract: This paper examines discriminatory order-assignment and payment-setting strategies for on-demand food-delivery platforms. We consider a platform that maximizes its profits by strategically bundling orders, assigning them to couriers, and setting personalized payments to couriers based on individual behavioral data accrued from past interactions with the platform. A novel multi-action, multi-agent deep reinforcement learning framework is proposed, where a Double Deep Q-Network is employed to develop discrete order-assignment strategies, and a Proximal Policy Optimization is utilized to determine continuous payment decisions. Our proposed method is validated through a case study using real-world food-delivery data from Hong Kong. Surprisingly, we find that couriers with higher reservation values and, consequently, higher order rejection rates actually receive more orders during peak hours but earn lower wages. The reasons for these counterintuitive results are identified, which expose implicit biases within the discriminatory algorithms employed by profit-maximizing platforms and underscore potential areas for regulatory intervention.

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
url_code: ''
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
