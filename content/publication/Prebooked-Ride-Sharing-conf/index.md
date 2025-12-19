---
title: 'Ride-Hailing Order Dispatching with A Mixture of On-Demand and Pre-Booked Requests via Reinforcement Learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Jing Gao
  - Sen Li

# Author notes (optional)
author_notes:


date: '2026-07-13T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *COTA International Conference of Transportation Professionals 2026*
publication_short: In *CICTP 2026*

abstract: This paper addresses the order dispatch problem in ride-hailing systems with a mixture of on-demand and pre-booked requests using a multi-agent reinforcement learning approach. We consider a ride-hailing platform that assigns both on-demand and pre-booked orders to drivers in real time, optimizing a balanced objective that accounts for the interests of passengers and the platform while satisfying operational constraints. To fully leverage prebooked requests, we introduce an order swapping mechanism that allows reassignment of prebooked orders among drivers. The order dispatching problem for each driver is formulated as a Markov Decision Process (MDP) with action decomposition that pre-booked order dispatch is executed first, followed by system state updates and on-demand order dispatch at each time step. To efficiently solve the system-level dispatch problem, we employ a multi-agent reinforcement learning framework with centralized learning and decentralized decision making. Specifically, we use a double deep Q-network (DDQN) to estimate state-action (Q) values for each driver and apply bipartite matching to determine the optimal order assignment that maximizes the global Q value. We validate the proposed approach through extensive numerical experiments using realistic ride-hailing trip data from New York City, benchmarking against an optimization-based method and a heuristic dispatch method. Results demonstrate that the DDQN approach outperforms both benchmarks in total reward and computational efficiency. Furthermore, the order swapping mechanism yields a 17% increase in total reward. Managerial insights are also derived to inform platform operations and policy design.

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
url_code: 'https://github.com/RS2002/Prebooked-Ride-Sharing'
url_slides: ''
url_source: ''

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
