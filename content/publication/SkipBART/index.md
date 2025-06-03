---
title: 'Automatic Stage Lighting Control: Is it a Rule-Driven Process or Generative Task?'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Dian Jin
  - Zijing Zhou
  - Xiaoyu Zhang


# Author notes (optional)
author_notes:


date: '2025-06-02T00:00:00Z'
doi: 'https://doi.org/10.48550/arXiv.2506.01482'

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *under review*
publication_short: In *under review*

abstract: Stage lighting plays an essential role in live music performances, influencing the engaging experience of both musicians and audiences. Given the high costs associated with hiring or training professional lighting engineers, Automatic Stage Lighting Control (ASLC) has gained increasing attention. However, most existing approaches only classify music into limited categories and map them to predefined light patterns, resulting in formulaic and monotonous outcomes that lack rationality. To address this issue, this paper presents an end-to-end solution that directly learns from experienced lighting engineers -- Skip-BART. To the best of our knowledge, this is the first work to conceptualize ASLC as a generative task rather than merely a classification problem. Our method modifies the BART model to take audio music as input and produce light hue and value (intensity) as output, incorporating a novel skip connection mechanism to enhance the relationship between music and light within the frame grid. We validate our method through both quantitative analysis and an human evaluation, demonstrating that Skip-BART outperforms conventional rule-based methods across all evaluation metrics and shows only a limited gap compared to real lighting engineers. Specifically, our method yields a p-value of 0.72 in a statistical comparison based on human evaluations with human lighting engineers, suggesting that the proposed approach closely matches human lighting engineering performance. To support further research, we have made our self-collected dataset, code, and trained model parameters available at https://github.com/RS2002/Skip-BART.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: 
#   url: 

url_pdf: 'https://arxiv.org/abs/2506.01482'
url_code: 'https://github.com/RS2002/Skip-BART'
url_dataset: 'https://zenodo.org/records/14854217'
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
