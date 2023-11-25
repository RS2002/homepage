---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin

  - block: features
    content:
      title: Skills
      items:
        - name: Code
          description: "Proficient in: C/C++ (CCF-CSP:320, Top 0.8%), Python, Matlab, Pytorch<br>Familiar with: Java, MySQL, Git, Linux, TensorFlow<br>Knowledgeable in: Assembly, Verilog, Web Scraping, Flask, QT, Docker, Raspberry Pi, ESP32"
          icon: code
          icon_pack: fas
        - name: Music
          description: "Proficient in: Electric Guitar, Acoustic Guitar, Electronic Keyboard(Grade 10), Music Theory(Grade C)<br>Familiar with: Songwriting, Extreme Vocals, Electric Bass, Piano, Drums, Ukulele, Harmonica, Hulusi"
          icon: music
          icon_pack: fas
        - name: Language
          description: "English (IELTS:6.5, CET-4:605, CET-6: 561)<br>Chinese (mother tongue)"
          icon: book
          icon_pack: fas

  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:

#        - title: Ph.D. 
#          company: Department of Civil and Environmental Engineering, The Hong Kong University of Science and Technology
#          company_url: 'https://www.ce.ust.hk/'
#          company_logo: HKUST-SENG
#          location: Hong Kong, Full-time
#          date_start: '2024-09-01'
#          date_end: ''
#          description:
        - title: Writing Consultant & Graduate Application Mentor
          company: FLY Education; Compass Education
          company_url: 'https://www.linkedin.com/company/fly-education-ltd/'
          company_logo: FLY
          location: Online, Part-time
          date_start: '2023-11-01'
          date_end: ''
          description:
        - title: Visiting Student 
          company: Shenzhen Research Institute of Big Data
          company_url: 'http://www.sribd.cn/'
          company_logo: SRIBD
          location: Shenzhen, Full-time
          date_start: '2023-08-01'
          date_end: '2024-08-01'
          description: 'associated with the Chinese University of Hong Kong, Shenzhen'
        - title: B.Eng. (2rd~4th)
          company: School of Computer Science and Engineering, Sun Yat-sen University
          company_url: 'https://cse.sysu.edu.cn/'
          company_logo: SYSU-CS
          location: Guangzhou, Full-time
          date_start: '2021-07-01'
          date_end: '2024-07-01'
          description: 
        - title: Tutor
          company: Zhangmen Education; Yousi Education
          company_url: 'http://zhangmentalent.com/'
          company_logo: ZM
          location: Online, Part-time
          date_start: '2020-12-01'
          date_end: '2021-09-01'
          description: 
        - title: B.Eng. (1st)
          company: School of Electronics and Communication Engineering, Sun Yat-sen University
          company_url: 'https://sece.sysu.edu.cn/'
          company_logo: SYSU
          location: Shenzhen, Full-time
          date_start: '2020-09-01'
          date_end: '2021-07-01'
          description: 


    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:

        - certificate_url: 
          date_end: ''
          date_start: '2023-11-01'
          description: 'Rank: 6/287 (reached the final); Bonus: 20,000 CNY; Team Member: Tingwei Chen (team leader), Zhijie Cai, Yihang Jiang, Fanyi Meng, Zijian Zhao; Supervisor: Dr. Guangxu Zhu, Dr. Hang Li, Dr. Xiaoyang Li'
          organization: Huawei, IEEE ISAC-ETI (Integrated Sensing and Communication Emerging Technology Initiative), China Institute of Communications, Huang Danian Chaspark
          organization_url: https://www.huaweicloud.com/
          title: Thrid Prize in The First Wi-Fi Sensing Contest by Huawei
          url: 'https://mp.weixin.qq.com/s/16cauCbcHotlCYzBtyT0DQ'
#        - certificate_url: 
#          date_end: ''
#          date_start: '2023-10-01'
#          description: 'Team Member: Tingwei Chen (team leader), Yantao Wang, Hanzhi Chen, Zijian Zhao, Xinhao Li; Supervisor: Dr. Guangxu Zhu'
#          organization: International Telecommunication Union (ITU)
#          organization_url: https://itu.edu/
#          title: No.3 (out of 713 teams) in AI/ML for 5G-Energy Consumption Modelling by ITU AI/ML in 5G Challenge
#          url: 'https://neuralnetwork.aiforgood.itu.int/event/ai-for-good/auditorium-archive/618bd56f1ca6ce6ae07960c9/timeslot/6527edd310600a0024ff61a0'
        - certificate_url: 
          date_end: ''
          date_start: '2023-10-01'
          description: 'Bonus: 2,000 CNY'
          organization: Sun Yat-sen University
          organization_url: https://www.sysu.edu.cn/
          title: Third-class Scholarship for Outstanding Student of Sun Yat-sen University
          url: ''
        - certificate_url:
          date_end: ''
          date_start: '2023-07-01'
          description: 'Team Member: Zijian Zhao (team leader, supervisor), Siyuan Zuo,Fupeng He'
          organization: Consortium for Mathematics and Its Application
          organization_url: https://www.comap.com/
          title: Meritorious Winner in the Mathematical Contest in Modeling
          url: 'https://www.comap.com/contests/mcm-icm'
        - certificate_url: 
          date_end: ''
          date_start: '2023-02-01'
          description: 'Bonus: 300 CNY'
          organization: Sun Yat-sen University
          organization_url: https://mp.weixin.qq.com/s/fffquCEoXELl6vt4LEPMGg
          title: Third Prize and Outstanding Resume Award in Sun Yat-sen University Future Job Hunting Competition
        - certificate_url:
          date_end: ''
          date_start: '2023-02-01'
          description: 'Team Member: Zijian Zhao (team leader), Che Zhou, Yiqi Liu; Supervisor: Prof. Chuanxian Ren'
          organization: Consortium for Mathematics and Its Application
          organization_url: https://www.comap.com/
          title: Successful Participant in the Mathematical Contest in Modeling
          url: 'https://www.comap.com/contests/mcm-icm'
          url: 'https://mp.weixin.qq.com/s/iQtjBspi3h9zodZayHlj9Q'
        - certificate_url:
          date_end: ''
          date_start: '2022-12-01'
          description: ''
          organization: Association of Fundamental Computing Education in Chinese Universities
          organization_url: http://www.beidouedu.net/
          title:  Third Prize in the National College Students’ IT Skills Competition of Chuanzhi Cup
          url: 'http://www.afcec.com/'
        - certificate_url:
          date_end: ''
          date_start: '2022-12-01'
          description: ''
          organization: Shandong Beidou Education Research Institute, Jilin Provincial Association for Science and Technology Education
          organization_url: http://www.beidouedu.net/
          title:  Provincial Third Prize in the National College Students’ Mathematics Competition of Huajiao Cup
          url: 'http://www.cecmath.com/'
        - certificate_url:
          date_end: ''
          date_start: '2022-11-01'
          description: ''
          organization: Chinese Mathematical Society
          organization_url: http://www.cms.org.cn/ 
          title: Provincial First Prize in the Chinese Mathematics Competitions
          url: 'http://www.cmathc.cn/'
        - certificate_url:
          date_end: ''
          date_start: '2022-10-01'
          description: ''
          organization: China Society for Futures Studies
          organization_url: http://www.csfs.org.cn/
          title: Bronze Award in China College Algorithm Design & Program Challenge Contest
          url: ''
        - certificate_url:
          date_end: ''
          date_start: '2022-10-01'
          description: 'Team Member: Zijian Zhao (team leader), Fanqi Zhang, Jiali Liu; Supervisor: Prof. Zhihong Luo'
          organization: China Society for Industrial and Applied Mathematics, Education Department of Guangdong Province
          organization_url: https://www.csiam.org.cn/
          title: Provincial Third Prize in the Chinese Mathematics Competitions 
          url: 'http://www.mcm.edu.cn/'
        - certificate_url:
          date_end: ''
          date_start: '2022-10-01'
          description: 'Bonus: 3,000 CNY'
          organization: Sun Yat-sen University
          organization_url: https://www.sysu.edu.cn/
          title: Second-class Scholarship for Outstanding Student of Sun Yat-sen University
          url: ''
        - certificate_url:
          date_end: ''
          date_start: '2022-07-01'
          description: 'Team Member: Haoyao He (team leader), Xiangyu Tan, Zijian Zhao; Supervisor: Prof. Qi Liang, Prof. Ruyu Wang'
          organization: Statistical Education Society of China
          organization_url: http://www.stats.gov.cn/zt_18555/xhwz/tjjyxh/
          title: Provincial Second Prize in SPSS University Contest in Modeling
          url: 'http://tjjmds.ai-learning.net/'
        - certificate_url:
          date_end: ''
          date_start: '2022-04-01'
          description: 'Team Member: Zijian Zhao (team leader), Weichao Zeng, Fupeng He'
          organization: School of Computer Science and Engineering, Sun Yat-sen University
          organization_url: https://cse.sysu.edu.cn/
          title: First Prize in Sun Yat-sen University Novice Programming Competition
          url: ''
        - certificate_url:
          date_end: ''
          date_start: '2022-02-01'
          description: 'Team Member: Zijian Zhao (team leader), Fanqi Zhang, Jiali Liu'
          organization: Consortium for Mathematics and Its Application
          organization_url: https://www.comap.com/
          title: Successful Participant in the Mathematical Contest in Modeling
          url: 'https://www.comap.com/contests/mcm-icm'
        - certificate_url:
          date_end: ''
          date_start: '2022-02-01'
          description: ''
          organization: China Society for Futures Studies
          organization_url: http://www.csfs.org.cn/
          title: Successful Participant in China College Algorithm Design & Program Challenge Contest
          url: ''
        - certificate_url:
          date_end: ''
          date_start: '2021-12-01'
          description: 'Team Member: Zijian Zhao (team leader), Haoyao He, Fanqi Zhang'
          organization: Beijing Society of Image and Graphics, APMCM Organizing Committee
          organization_url: http://www.bsig.org.cn/
          title: Second Prize in Asia and Pacific Mathematical Contest in Modeling
          url: 'http://www.apmcm.org/'
        - certificate_url:
          date_end: ''
          date_start: '2021-10-01'
          description: ''
          organization: Chinese Mathematical Society
          organization_url: http://www.cms.org.cn/
          title: Provincial First Prize in the Chinese Mathematics Competitions
          url: 'http://www.cmathc.cn/'
        - certificate_url:
          date_end: ''
          date_start: '2021-10-01'
          description: 'Team Member: Zijian Zhao (team leader), Yifeng Zhao, Ziwan Liu; Supervisor: Prof. Bingpeng Zhou'
          organization: China Society for Industrial and Applied Mathematics, Education Department of Guangdong Province
          organization_url: https://www.csiam.org.cn/
          title: Provincial Third Prize in the Chinese Mathematics Competitions 
          url: 'http://www.mcm.edu.cn/'
        - certificate_url:
          date_end: ''
          date_start: '2021-10-01'
          description: 'Bonus: 4,000 CNY'
          organization: Sun Yat-sen University
          organization_url: https://www.sysu.edu.cn/
          title: First-class Scholarship for Outstanding Student of Sun Yat-sen University
          url: ''
        - certificate_url:
          date_end: ''
          date_start: '2021-05-01'
          description: 'Team Member: Zijian Zhao (team leader), Diang Zhao, Kang Zhou'
          organization: School of Computer Science and Engineering, Sun Yat-sen University
          organization_url: https://cse.sysu.edu.cn/
          title: Third Prize in Sun Yat-sen University Novice Programming Competition
          url: ''
        - certificate_url:
          date_end: ''
          date_start: '2020-11-01'
          description: 'Team Member: Zijian Zhao (team leader), Quan Zhang, Ziwan Liu'
          organization: School of Electronics and Communication Engineering, Sun Yat-sen University
          organization_url: https://sece.sysu.edu.cn/
          title: Excellence Award in Sun Yat-sen University Electronic Design Creative Competition
          url: ''
        - certificate_url:
          date_end: ''
          date_start: '2019-09-01'
          description: ''
          organization: Chinese Mathematical Society
          organization_url: http://www.cms.org.cn/
          title: Second Prize & Provincial First Prize in National High School Mathematics League
          url: 'http://www.cms.org.cn/en/Home/comp/comp/13.html'
        - certificate_url:
          date_end: ''
          date_start: '2018-09-01'
          description: ''
          organization: Chinese Mathematical Society
          organization_url: http://www.cms.org.cn/
          title: Provincial Third Prize in National High School Mathematics League
          url: 'http://www.cms.org.cn/en/Home/comp/comp/13.html'
        - certificate_url:
          date_end: ''
          date_start: '2017-10-01'
          description: ''
          organization: Harbin NO.3 High School
          organization_url: http://www.hrb3z.net/
          title:  Bronze Award in the Mathematics Competition by Harbin NO.3 High School
          url: ''
        - certificate_url:
          date_end: ''
          date_start: '2017-10-01'
          description: ''
          organization: Harbin NO.3 High School
          organization_url: http://www.hrb3z.net/
          title:  Third Prize in the Physics Competition by Harbin NO.3 High School
          url: ''




    design:
      columns: '2'
 
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Music Information Retrieval
          tag: Music Information Retrieval
        - name: Robot Reinforcement Learning
          tag: Robot Reinforcement Learning
        - name: Other
          tag: Other
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: collection
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation

  - block: collection
    id: patent
    content:
      title: Patents
      filters:
        folders:
          - patent
    design:
      columns: '2'
      view: citation

  - block: collection
    id: talk
    content:
      title: Talks
      filters:
        folders:
          - talk
    design:
      columns: '2'
      view: compact

  - block: portfolio
    id: music
    content:
      title: Music
      filters:
        folders:
          - music
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: NEWS
          tag: NEWS
        - name: Rights of Lethe
          tag: Rights of Lethe
        - name: Other
          tag: other
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false

  - block: collection
    id: live
    content:
      title: Live
      filters:
        folders:
          - live
    design:
      columns: '2'
      view: compact

#   - block: markdown
#     content:
#       title: Gallery
#       subtitle: ''
#       text: |-
#         {{< gallery album="demo" >}}
#     design:
#       columns: '1'
---



