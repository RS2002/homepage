---
title: 'Real-Time Order Assignment for Ride-Sharing Platforms with a Mixture of Pre-booked and On-Demand Requests'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Jing Gao
  - Sen Li


# Author notes (optional)
author_notes:


date: '2026-09-14T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Transportation Research Part C -- Emerging Technologies*
publication_short: In *Transportation Research Part C*

abstract: This paper addresses the real-time order assignment problem for ride-sharing platforms that serve a combination of pre-booked and on-demand requests. We consider a dynamic setting where both request types arrive continuously, may involve shared or non-shared rides, and must be assigned online to optimize overall system performance. To effectively manage their heterogeneous characteristics and operational interplay, we introduce a sequential two-stage assignment mechanism -- in each decision epoch, pre-booked orders are first assigned or reallocated among vehicles (pre-booked assignment stage), followed by the assignment of on-demand orders to the remaining available vehicles based on the updated system state (on-demand assignment stage). Building on this mechanism, we formulate a tailored Markov Decision Process (MDP) that embeds the proposed sequential two-stage assignment mechanism into the decision structure to explicitly capture the interactions between pre-booked and on-demand orders. A double deep Q-network (DDQN) is used to approximate vehicle-level action-values, and centralized assignments in both stages are obtained via bipartite matching under relevant feasibility constraints. We validate the proposed method through extensive numerical experiments, which demonstrate that our approach consistently outperforms both distance-based and myopic greedy baselines in terms of total system reward, while maintaining real-time computational efficiency. Notably, the two-stage mechanism with pre-booked order reassignment achieves a more favorable balance between pre-booked and on-demand services, yielding a 14\% improvement in total reward compared to a DDQN variant without reassignment. Further, leveraging the developed framework, we examine the impacts of pre-booked service under varying penetration rates and advance booking times. The results reveal that, perhaps surprisingly, the effect of increasing pre-booked penetration on system-wide performance is non-monotonic and critically depends on both lead time and the proportion of pre-booked orders. When the advance booking time is short (e.g., 15 minutes), increasing the pre-booked penetration rate reduces the overall platform reward almost monotonically. Even when lead times are longer (e.g., 20--30 minutes), increasing penetration initially decreases total reward at low penetration levels (e.g., below 40\%) before recovering as the share of pre-booked orders grows. This reveals a critical trade-off -- while pre-booked orders provide valuable advance information, they also introduce additional service-guarantee requirements that can offset these benefits. This nuanced insight has not been addressed in previous work.


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
