---
title: 'Finding the Missing Data: A BERT-inspired Approach Against Package Loss in Wireless Sensing'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Tingwei Chen
  - Fanyi Meng
  - Hang Li
  - Xiaoyang Li
  - Guangxu Zhu

# Author notes (optional)
author_notes:


date: '2024-02-06T00:00:00Z'
doi: 'https://doi.org/10.48550/arXiv.2403.12400'

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Conference on Computer Communications Deepwireless Workshop 2024*
publication_short: In *IEEE INFOCOM Deepwireless Workshop 2024*

abstract: Despite the development of various deep learning methods for Wi-Fi sensing, package loss often results in noncontinuous estimation of the Channel State Information (CSI), which negatively impacts the performance of the learning models. To overcome this challenge, we propose a deep learning model based on Bidirectional Encoder Representations from Transformers (BERT) for CSI recovery, named CSI-BERT. CSI-BERT can be trained in an self-supervised manner on the target dataset without the need for additional data. Furthermore, unlike traditional interpolation methods that focus on one subcarrier at a time, CSI-BERT captures the sequential relationships across different subcarriers. Experimental results demonstrate that CSIBERT achieves lower error rates and faster speed compared to traditional interpolation methods, even when facing with high loss rates. Moreover, by harnessing the recovered CSI obtained from CSI-BERT, other deep learning models like Residual Network and Recurrent Neural Network can achieve an average increase in accuracy of approximately 15% in Wi-Fi sensing tasks. The collected dataset WiGesture and code for our model are publicly available at https://github.com/RS2002/CSI-BERT.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: 
#   url: 

url_pdf: 'http://arxiv.org/abs/2403.12400'
url_code: 'https://paperswithcode.com/dataset/wigesture'
url_dataset: 'https://github.com/RS2002/CSI-BERT'
url_poster: ''
url_project: ''
url_slides: 'https://docs.google.com/presentation/d/15aNURPf3LMXQikXKkN5b7Pp9HWV1kWIJ/edit?usp=sharing&ouid=115821974896546102715&rtpof=true&sd=true'
url_source: ''
url_video: 'https://drive.google.com/file/d/1VNZY2ewpXjNyfwkRmjh1cKLGg_a1nTLw/view?usp=drive_link'

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
projects:
  - content/project/CSI-BERT/index.md

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: 
---
