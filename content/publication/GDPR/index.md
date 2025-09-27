---
title: 'The Impacts of Data Privacy Regulations on Food-Delivery Platforms", Transportation Research Part C: Emerging Technologies (TR\_C), 2025 (JCR-Q1) \href{}{[{\color'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Sen Li


# Author notes (optional)
author_notes:


date: '2025-09-27T00:00:00Z'
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

abstract: This paper examines the impacts of data privacy regulations (such as the General Data Protection Regulation), on the on-demand food-delivery market. Specifically, we consider a food-delivery platform that determines order bundling, order assignment, and courier payments at each step, alongside a group of couriers who make short-term decisions on whether to accept assigned orders and long-term decisions on whether to allow the platform to use their historical behavioral data (e.g., order acceptance and rejection history) for operational decision-making. We formulate a Markov Decision Process (MDP) to simulate the platform’s operational strategies and a Multi-Agent Contextual Multi-Armed Bandit (MA-CMAB) framework to simulate the couriers’ decisions under the data privacy regulation. The platform’s MDP involves mixed-integer decisions, and a novel hybrid multi-agent reinforcement learning framework is proposed to combine a Double Deep Q-Network (DDQN) for discrete order assignment strategies and Proximal Policy Optimization with KL and CLIP (PPO-KL-CLIP) for continuous payment decisions. For the couriers, we develop a Maximum Likelihood Estimation (MLE)-based Thompson Sampling method to derive their optimal strategies. To address the interaction between the platform and the couriers, we employ a two-stage training framework: the first stage trains a general policy for the platform that adapts to any courier strategy, while the second stage derives the optimal strategies for the couriers. The proposed model and algorithm are validated using real-world food-delivery data from Hong Kong, comparing scenarios under data privacy regulations with a benchmark case without such regulations. Interestingly, the findings reveal that, contrary to initial expectations, data privacy regulations not only protect couriers but may also result in higher platform profits and improved customer experiences. By giving couriers the flexibility to decide whether to share their work-related data for order assignments and payment decisions, the regulations attract more active couriers, thereby improving overall system performance. Specifically, the number of active couriers increases under regulation, particularly during peak hours, leading to more food-delivery orders served and higher platform profits. Customers also benefit from shorter delivery times and lower overtime rates. These findings highlight the potential of data privacy regulations to reshape labor dynamics in the gig economy, creating a win-win scenario for platforms, couriers, and customers. The code of this paper is publicly available at https://github.com/RS2002/GDPR-Food-Delivery .


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
url_code: 'https://github.com/RS2002/GDPR-Food-Delivery'
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
