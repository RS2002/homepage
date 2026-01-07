---
title: 'Discriminatory Order Assignment and Payment-Setting on Food-Delivery Platforms: A Multi-Action and Multi-Agent Reinforcement Learning Framework'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Sen Li


# Author notes (optional)
author_notes:


date: '2026-01-06T00:00:00Z'
doi: 'https://doi.org/10.1016/j.tre.2025.104653'

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Transportation Research Part E -- Logistics and Transportation Review*
publication_short: In *Transportation Research Part E*

abstract: This paper studies the discriminatory order assignment and payment-setting strategies for on-demand food-delivery platforms. We consider an on-demand food-delivery platform that coordinates customers, couriers, and restaurants to maximize the profit. It determines how to bundle orders, assign orders to couriers, and set payments to couriers in real-time. These decisions are made in a personalized manner, depending on the historical data collected from each of the couriers, such as the order acceptance and rejection rates under distinct scenarios of order assignment and payment values. A Markov Decision Process is formulated for the courier, capturing the decisions of the platform (including differentiated order assignment/bundling strategies and the discriminatory payment-settings decisions) while considering its dependence on the personalized work-related data of each individual courier. To derive the optimal policies, we propose a novel multi-action and multi-agent deep reinforcement learning framework, where a double Deep Q-Network is employed to develop discrete order assignment strategies, and double Proximal Policy Optimization is utilized to determine continuous payment decisions. Within this learning framework, we introduce a novel neural network architecture that leverages the Query-Key attention mechanism to transform multiplicative time complexities into additive computation complexity for order assignment, and we adopt a variable-length Bi-LSTM module that compresses variable-length order sequence into a fixed-dimensional feature space to enhance scalability. The proposed neural network and algorithmic framework was validated in a case study using real-world food-delivery data from Hong Kong. By comparing the proposed method with a vanilla MLP-based neural network architecture, we find that the proposed neural network architecture significantly enhances platform performance that it increases the number of orders served by 5.25%, reduces platform expenses by 10%, and improves the overall reward of the platform by over 50%. Additionally, our results reveal that couriers with higher order rejection rates receive more orders during peak hours but earn lower wages. This counterintuitive finding is attributed to a strategic approach by the platform to differentiate order allocation that instead of simply allocating fewer orders to couriers with higher rejection rates, the platform preferentially assigns longer-distance trips to couriers with a higher likelihood of order acceptance. These findings expose the implicit biases in the discriminatory algorithms used by the profit-maximizing platform and highlight potential areas for governmental regulatory intervention. The code for our model is publicly available at https://github.com/RS2002/Discriminatory-Food-Delivery . 

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: 
#   url: 

url_pdf: 'https://www.sciencedirect.com/science/article/pii/S1366554525006751'
url_code: 'https://github.com/RS2002/Discriminatory-Food-Delivery'
url_dataset: https://github.com/RS2002/Discriminatory-Food-Delivery/main/data''
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
