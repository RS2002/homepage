---
title: 'Optimizing Denoising Trajectories in dLLMs: A Lightweight Evolutionary Heuristic Approach'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Dian Jin
  - Xialiang Tong
  - Sen Li
  - Mingxuan Yuan


# Author notes (optional)
author_notes:


date: '2026-07-15T00:00:00Z'
doi: ''

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

abstract: Diffusion Large Language Models (dLLMs) have recently emerged as a promising alternative to conventional Auto-Regressive (AR) Large Language Models (LLMs). By leveraging bidirectional attention and parallel decoding, dLLMs enable more efficient generation. However, they require a carefully designed denoising scheduler at inference time (absent during training) whose choice significantly impacts generation quality. While confidence-based heuristic schedulers have shown strong empirical performance, they suffer from two critical failure modes -- EOS Overflow and Proximal Bias. Through in-depth analysis of the Transformer's attention patterns, we reveal that these failures stem from certain positions assigning disproportionately high attention weights to invalid tokens (e.g., [MASK] and [EOS]), which produce misleading confidence signals. Building on this insight, empirical evidence shows that valid attention scores can provide complementary guidance to conventional confidence-based heuristics, yet no single metric consistently excels across all scenarios, implying that the optimal denoising trajectory is highly context-dependent. To address this problem, we propose a lightweight evolutionary heuristic scheduler optimized using the Covariance Matrix Adaptation Evolution Strategy (CMA-ES). Our scheduler dynamically integrates multiple heuristic features with a contextual mean-field embedding, while requiring only 393 trainable parameters. Evaluated on LLaDA and Dream across four reasoning and planning benchmarks, our method consistently outperforms strong baselines, including conventional heuristics, block auto-regressive methods, and recent State-Of-The-Art (SOTA) approaches. To the best of our knowledge, it represents the most parameter-efficient neural scheduler to date. Our code is available at https://github.com/RS2002/Evo-Denoise .

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
url_code: 'https://github.com/RS2002/Evo-Denoise'
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
