---
title: 'Beyond Left-to-Right: A Survey of Decoding Schedulers in Diffusion Language Models'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Xialiang Tong
  - Sen Li
  - Mingxuan Yuan

# Author notes (optional)
author_notes:


date: '2026-09-02T00:00:00Z'
doi: 'https://dx.doi.org/10.2139/ssrn.7393940'

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

abstract: Autoregressive language models decode one token at a time, a sequential bottleneck that caps throughput and compounds errors as generation proceeds. Diffusion language models (dLLMs) promise a way out -- they start from a fully masked sequence and recover tokens in parallel under bidirectional attention, making the order of token revelation a choice rather than an architectural fate. But this flexibility conceals a trap -- the inference-time schedule strongly shapes final quality, yet the training objective is order-agnostic and never specifies what schedule to follow. The scheduler, the component that makes these decisions, is thus both critical and routinely overlooked. In this survey, we separate the scheduler, which selects the positions to denoise, from the denoiser, which predicts the tokens, and we classify schedulers by five dimensions -- the signal used to choose positions, whether the scheduler is trained, the granularity of the decision, the decoding budget, and whether decoded tokens may be remasked. Beyond taxonomy, we ask what a scheduler can fundamentally achieve. An oracle order defines an upper bound but remains a diagnostic. An information-geometric bound reveals that good schedules are cheap with prior knowledge but require linear cost without it. And even with a perfect denoiser, a sampler can deviate from the model's intended distribution, which makes standard quality metrics misleading. We identify attribution, whether the remaining gap belongs to the scheduler or the backbone, as the main open question. To the best of our knowledge, this is the first survey to treat the inference-time scheduler as the primary subject of analysis, providing guidance on how results should be interpreted and compared in dLLMs.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: 
#   url: 

url_pdf: 'https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7393940'
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
