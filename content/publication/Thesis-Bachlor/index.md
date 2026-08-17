---
title: 'Motion Control Method for Small Quadruped Robots Based on Trajectory Modulation and Reinforcement Learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin

# Author notes (optional)
author_notes:


date: '2024-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['7']

# Publication name and optional abbreviated publication name.
publication: In *Sun Yat-Sen University Bachlor Thesis*
publication_short: In *SYSU B.Eng. Thesis*

abstract: Quadruped robots have gained significant attention in various fields, including scientific research, military applications, and rescue operations, due to their stability and flexibility. As a result, motion control for quadruped robots has become a popular research topic in the field of robotics. Currently, there are two common approaches to control quadruped robots --- model-based methods and reinforcement learning-based methods. Model-based methods often require extensive expert knowledge, computation, and debugging. Moreover, these methods lack transferability and require designing different approaches for different scenarios. In contrast, reinforcement learning methods have attracted significant interest as they enable robots to interact adaptively with the environment and learn suitable motion strategies. However, previous reinforcement learning methods often have high hardware requirements, substantial computational costs during training, and perform poorly on small robots with limited computational and perceptual capabilities. To address these challenges, we propose the ARS-Bezier method based on the light-weight Augmented Random Search (ARS) algorithm. The ARS-Bezier method combines the ARS algorithm with Bezier curves to enhance the model's learning ability, improve learning efficiency, and reduce learning difficulty. Additionally, we introduce the method of environment randomization to enhance the transferability of learned policies. The main contributions of this paper are as follows. Firstly, we focus on the motion control methods of the self-developed robot mouse NeRmo. This includes the modeling of forward and inverse kinematics. Next, we analyze the fundamental properties of Bezier curves and provide a simple proof. Then we deploy Bezier trajectories on the robot mouse. Subsequently, based on the robot mouse's structure, we design the ARS framework and propose the ARS-Bezier control method, which utilizes Bezier curves to enhance the model's learning ability. Additionally, we introduce an environment randomization method to enable the robot to learn more versatile motion strategies. Then, we conduct a series of experiments in both simulation and real environments to demonstrate the effectiveness of the ARS-Bezier method. We compare the experimental results and analyze the performance of learned motion strategies through environment randomization in different scenarios. Furthermore, we showcase the process of building the actual robot mouse, burning the algorithm, and verify the effectiveness of the motion strategies in real-world scenarios.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: 
#   url: 

url_pdf: 'https://github.com/RS2002/RL-Rat/blob/main/thesis.pdfhttps://github.com/RS2002/RL-Rat/blob/main/thesis.pdf'
url_code: 'https://github.com/RS2002/RL-Rat'
url_dataset: ''
url_project: ''
url_video: 
url_slides: 

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
