---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: light
      background:
        color: white
        image:
          # Add your image background to `assets/media/`.
          filename: ''
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    id: overview
    content:
      title: 'Featured Research Overview'
      subtitle: ''
      text: |-
        #### <mark>Circuit Foundation Model</mark>
          - Survey on Circuit Foundation Models [[Paper](https://arxiv.org/abs/2504.03711)]
          - Multimodal netlist encoder [DAC'25]
          - Multimodal RTL encoder [[ICLR'25](https://openreview.net/forum?id=rbnf7oe6JQ)]
          - RTL-netlist encoder alignment [[ASPDAC'25](https://dl.acm.org/doi/abs/10.1145/3658617.3697597)]
          - Large Circuit Model [[SCIS'24](https://link.springer.com/journal/11432)]
          
        #### <mark>Circuit Design Quality Evaluation & Optimization</mark>
          - RTL-stage fine-grained timing slack prediction [[DAC'24](https://dl.acm.org/doi/abs/10.1145/3649329.3655671)]
          - RTL-stage overall PPA prediction [[TCAD'24](https://ieeexplore.ieee.org/abstract/document/10577671/)]&[[ICCAD'23](https://ieeexplore.ieee.org/abstract/document/10323951)]
        
        #### <mark>Hardware Formal Verification</mark>
          - LLM-aided assertion generation [[ASPDAC'25]](https://arxiv.org/abs/2402.00386)&[[ICCAD'24]](https://zhiyaoxie.com/files/ICCAD24_OpenLLM.pdf)
          - CPU symbolic simulation [[TACAS'23](https://link.springer.com/chapter/10.1007/978-3-031-30820-8_2)]&[[TCAD'23](https://ieeexplore.ieee.org/abstract/document/10178019/)]

    design:
      columns: '1'
      css_class: light
      background:
        color: '#F7F7F7'
  # - block: collection
  #   id: project
  #   content:
  #     title: Research Projects
  #     filters:
  #       folders:
  #         - project
  #       featured_only: true
  #   design:
  #     view: article-grid
  #     columns: 3
  - block: collection
    id: publication
    content:
      title: Publications
      class: author-notes
      text: "(Co-)First-authored publications are <mark>highlighted</mark>."
      count: 100
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation

  # - block: markdown
  #  id: experience
  #  content:
  #    title: 'Experience'
  #    subtitle: ''
  #    text: |-
  #      * TA of MICS6000H Logic Design Automation of Digital Systems, HKUST(GZ)
  #  design:
  #    columns: '1'

    # content:
    #   title: 'Experience'
    #   # Date format for experience
    #   #   Refer to https://wowchemy.com/docs/customization/#date-format
    #   date_format: Jan 2006
    #   # Experiences.
    #   #   Add/remove as many experience `items` below as you like.
    #   #   Required fields are `title`, `company`, and `date_start`.
    #   #   Leave `date_end` empty if it's your current employer.
    #   #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
    #   items:
    #     - title: Intern
    #       company: Peng Cheng National Laboratory
    #       company_url: ''
    #       company_logo: pcl
    #       location: Shenzhen
    #       date_start: '2021-01-01'
    #       date_end: ''
    #       description: |2-
    #           Responsibilities include:

    #           * Analysing
    #           * Modelling
    #           * Deploying
  - block: markdown
    id: experience
    content:
      title: 'Experience'
      subtitle: ''
      text: |-
        * **Research Assistant, [HKUST(GZ)](https://www.hkust-gz.edu.cn/)**
          - Mentor: [Prof. Hongce Zhang](https://hongcezh.people.ust.hk/)
          - Developed an symbolic simulator for CPU formal verification
          - Dec 2021 - July 2022
        * **VLSI Physical Design Intern, [Peng Cheng Laboratory](https://www.pcl.ac.cn/)**
          - Mentor: [Dr. Biwei Xie](https://cn.linkedin.com/in/biwei-xie-90846236?trk=people-guest_people_search-card) & [Prof. Yungang Bao](http://english.ict.cas.cn/people/scien/bln/202303/t20230321_328543.html)
          - "One Student One Chip" Project
          - Completed the entire RTL-to-GDSII flow of an SoC
          - July 2021 - Dec 2021
        
    design:
      columns: '1'
      css_class: light
      background:
        color: '#F7F7F7'
  - block: markdown
    id: awards
    content:
      title: 'Awards'
      subtitle: ''
      text: |-
        * IEEE CEDA Student Travel Grant, 2025
        * DAC Young Fellow, 2024
        * ISLAD Best Paper Nomination, 2024
        * ISLAD Travel Grant, 2024
        * Full Postgraduate Studentship of HKUST, 2024-Now
        * ICCAD Student Scholar Program Grant, 2023
        * 3rd Place Award of [EDAthon Contest](https://sites.google.com/view/ceda-hk/edathon-2023), 2023
        * Full Postgraduate Studentship of HKUST(GZ), 2022-2024
        * Infineon Technology Scholarship, 2020
        * First Class Scholarship of NUAA, 2017-2021
    design:
      columns: '1'
    
  - block: markdown
    id: teaching
    content:
      title: 'Teaching'
      subtitle: ''
      text: |-
        * TA of Electronic Design Automation for VLSI Design, HKUST
        * TA of Logic Design Automation of Digital Systems, HKUST(GZ)
        
    design:
      columns: '1'
      css_class: light
      background:
        color: '#F7F7F7'  
        
    # design:
    #   columns: '1'
  # - block: markdown
  #   id: pub
  #   content:
  #     title: 'Pub'
  #     subtitle: ''
  #     text: |-
  #       * [c10] aaa
  #       * [c9] bbb
  #   design:
  #     columns: '1'

  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     view: article-grid
  #     columns: 1
  # - block: collection
  #   id: news
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: post
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: date-title-summary
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]
  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

        Easily build anything with blocks - no-code required!
        
        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
