---
title: 'Towards Advanced Mathematical Reasoning for LLMs via First-Order Logic Theorem Proving'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Chuxue Cao
  - Mengze Li
  - Juntao Dai
  - Jinluan Yang
  - admin
  - Shengyu Zhang
  - Weijie Shi
  - Chengzhogn Liu
  - Sirui Han
  - Yike Guo

# Author notes (optional)
author_notes:


date: '2025-06-20T00:00:00Z'
doi: '10.18653/v1/2025.emnlp-main.628'

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Conference on Empirical Methods in Natural Language Processing 2025*
publication_short: In *EMNLP 2025*

abstract: Large language models (LLMs) have shown promising first-order logic (FOL) reasoning capabilities with applications in various areas. However, their effectiveness in complex mathematical reasoning involving multi-step FOL deductions is still under-researched. While LLMs perform competitively on established mathematical reasoning benchmarks, they struggle with multi-step FOL tasks, as demonstrated by Deepseek-Prover-V2-7B's low accuracy (4.2%) on our proposed theorem proving dataset. This issue arises from the limited exploration of diverse proof strategies and the potential for early reasoning mistakes to undermine entire proofs. To address these issues, we propose DREAM, a self-adaptive solution that enhances the Diversity and REAsonability of LLMs' generation strategies. DREAM incorporates an Axiom-Driven Strategy Diversification mechanism to promote varied strategic outcomes and a Sub-Proposition Error Feedback to help LLMs reflect on and correct their proofs. Our contributions include pioneering advancements in LLMs' mathematical reasoning through FOL theorem proving, introducing a novel inference stage solution that improves performance by 0.6% to 6.4%, and providing a curated dataset of 447 mathematical theorems in Lean 4 format for evaluation.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: 
#   url: 

url_pdf: 'https://aclanthology.org/2025.emnlp-main.628/'
url_code: 'https://github.com/chuxuecao/dream-fol-prover'
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
