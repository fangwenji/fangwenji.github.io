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
      headings:
        about: About Me
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle
  - block: markdown
    id: overview
    content:
      title: ''
      subtitle: ''
      text: |-
        <div class="relative left-1/2 w-[calc(100vw-3rem)] max-w-5xl -translate-x-1/2 grid grid-cols-1 md:grid-cols-[10rem_1fr] gap-4 md:gap-6">
          <div>
            <h2 class="text-3xl font-bold text-gray-900 dark:text-white">Research Highlight</h2>
          </div>
          <div class="grid grid-cols-1 gap-5 lg:grid-cols-2 text-base leading-6">
            <div class="rounded-xl border border-gray-200 dark:border-gray-700 border-l-4 border-l-primary-500 dark:border-l-primary-400 bg-white/60 dark:bg-gray-800/40 p-5 shadow-sm">
              <h3 class="m-0 text-lg font-bold text-gray-900 dark:text-white"><em class="not-italic text-primary-700 dark:text-primary-300">Method View:</em> Evolving AI for EDA Paradigms</h3>
              <div class="mt-4 space-y-4">
                <div>
                  <p class="m-0"><mark class="bg-yellow-100 dark:bg-yellow-300/15 text-gray-900 dark:text-yellow-100 px-1.5 py-0.5 rounded font-semibold">4. Agentic AI for EDA<br>&mdash; Agentic Design Automation</mark></p>
                  <ul class="mt-2 mb-0 space-y-1.5 list-disc pl-5 marker:text-primary-500 dark:marker:text-primary-400">
                    <li class="text-sm text-gray-700 dark:text-gray-300">
                      Self-improving agentic RTL optimization:
                      <a class="inline-flex items-center whitespace-nowrap px-2 py-0.5 ml-1 rounded-md text-xs font-medium bg-primary-50 dark:bg-primary-900/40 text-primary-700 dark:text-primary-200 hover:bg-primary-100 dark:hover:bg-primary-900/60 no-underline transition-colors" href="https://arxiv.org/abs/2604.14989">Arxiv'26</a>
                    </li>
                  </ul>
                </div>
                <div>
                  <p class="m-0"><mark class="bg-yellow-100 dark:bg-yellow-300/15 text-gray-900 dark:text-yellow-100 px-1.5 py-0.5 rounded font-semibold">3. Foundation AI for EDA<br>&mdash; Circuit Foundation Model</mark></p>
                  <ul class="mt-2 mb-0 space-y-1.5 list-disc pl-5 marker:text-primary-500 dark:marker:text-primary-400">
                    <li class="text-sm text-gray-700 dark:text-gray-300">
                      Survey and position paper:
                      <a class="inline-flex items-center whitespace-nowrap px-2 py-0.5 ml-1 rounded-md text-xs font-medium bg-primary-50 dark:bg-primary-900/40 text-primary-700 dark:text-primary-200 hover:bg-primary-100 dark:hover:bg-primary-900/60 no-underline transition-colors" href="https://arxiv.org/abs/2504.03711">Survey</a>
                      <a class="inline-flex items-center whitespace-nowrap px-2 py-0.5 ml-1 rounded-md text-xs font-medium bg-primary-50 dark:bg-primary-900/40 text-primary-700 dark:text-primary-200 hover:bg-primary-100 dark:hover:bg-primary-900/60 no-underline transition-colors" href="https://link.springer.com/journal/11432">SCIS'24</a>
                    </li>
                    <li class="text-sm text-gray-700 dark:text-gray-300">
                      Circuit encoder:
                      <a class="inline-flex items-center whitespace-nowrap px-2 py-0.5 ml-1 rounded-md text-xs font-medium bg-primary-50 dark:bg-primary-900/40 text-primary-700 dark:text-primary-200 hover:bg-primary-100 dark:hover:bg-primary-900/60 no-underline transition-colors" href="https://arxiv.org/abs/2504.09260">DAC'25</a>
                      <a class="inline-flex items-center whitespace-nowrap px-2 py-0.5 ml-1 rounded-md text-xs font-medium bg-primary-50 dark:bg-primary-900/40 text-primary-700 dark:text-primary-200 hover:bg-primary-100 dark:hover:bg-primary-900/60 no-underline transition-colors" href="https://openreview.net/forum?id=rbnf7oe6JQ">ICLR'25</a>
                      <a class="inline-flex items-center whitespace-nowrap px-2 py-0.5 ml-1 rounded-md text-xs font-medium bg-primary-50 dark:bg-primary-900/40 text-primary-700 dark:text-primary-200 hover:bg-primary-100 dark:hover:bg-primary-900/60 no-underline transition-colors" href="https://dl.acm.org/doi/abs/10.1145/3658617.3697597">ASPDAC'25</a>
                    </li>
                    <li class="text-sm text-gray-700 dark:text-gray-300">
                      LLM decoder:
                      <a class="inline-flex items-center whitespace-nowrap px-2 py-0.5 ml-1 rounded-md text-xs font-medium bg-primary-50 dark:bg-primary-900/40 text-primary-700 dark:text-primary-200 hover:bg-primary-100 dark:hover:bg-primary-900/60 no-underline transition-colors" href="https://arxiv.org/abs/2504.09485">ICCAD'25</a>
                      <a class="inline-flex items-center whitespace-nowrap px-2 py-0.5 ml-1 rounded-md text-xs font-medium bg-primary-50 dark:bg-primary-900/40 text-primary-700 dark:text-primary-200 hover:bg-primary-100 dark:hover:bg-primary-900/60 no-underline transition-colors" href="https://arxiv.org/abs/2402.00386">ASPDAC'25</a>
                      <a class="inline-flex items-center whitespace-nowrap px-2 py-0.5 ml-1 rounded-md text-xs font-medium bg-primary-50 dark:bg-primary-900/40 text-primary-700 dark:text-primary-200 hover:bg-primary-100 dark:hover:bg-primary-900/60 no-underline transition-colors" href="https://zhiyaoxie.com/files/ICCAD24_OpenLLM.pdf">ICCAD'24</a>
                    </li>
                  </ul>
                </div>
                <div>
                  <p class="m-0"><mark class="bg-yellow-100 dark:bg-yellow-300/15 text-gray-900 dark:text-yellow-100 px-1.5 py-0.5 rounded font-semibold">2. Supervised AI for EDA<br>&mdash; Task-Specific Learning</mark></p>
                  <ul class="mt-2 mb-0 space-y-1.5 list-disc pl-5 marker:text-primary-500 dark:marker:text-primary-400">
                    <li class="text-sm text-gray-700 dark:text-gray-300">
                      RTL register timing slack prediction:
                      <a class="inline-flex items-center whitespace-nowrap px-2 py-0.5 ml-1 rounded-md text-xs font-medium bg-primary-50 dark:bg-primary-900/40 text-primary-700 dark:text-primary-200 hover:bg-primary-100 dark:hover:bg-primary-900/60 no-underline transition-colors" href="https://dl.acm.org/doi/abs/10.1145/3649329.3655671">DAC'24</a>
                    </li>
                    <li class="text-sm text-gray-700 dark:text-gray-300">
                      RTL overall PPA prediction:
                      <a class="inline-flex items-center whitespace-nowrap px-2 py-0.5 ml-1 rounded-md text-xs font-medium bg-primary-50 dark:bg-primary-900/40 text-primary-700 dark:text-primary-200 hover:bg-primary-100 dark:hover:bg-primary-900/60 no-underline transition-colors" href="https://ieeexplore.ieee.org/abstract/document/10577671/">TCAD'24</a>
                      <a class="inline-flex items-center whitespace-nowrap px-2 py-0.5 ml-1 rounded-md text-xs font-medium bg-primary-50 dark:bg-primary-900/40 text-primary-700 dark:text-primary-200 hover:bg-primary-100 dark:hover:bg-primary-900/60 no-underline transition-colors" href="https://ieeexplore.ieee.org/abstract/document/10323951">ICCAD'23</a>
                    </li>
                  </ul>
                </div>
                <div>
                  <p class="m-0"><mark class="bg-yellow-100 dark:bg-yellow-300/15 text-gray-900 dark:text-yellow-100 px-1.5 py-0.5 rounded font-semibold">1. EDA Algorithm Development</mark></p>
                  <ul class="mt-2 mb-0 space-y-1.5 list-disc pl-5 marker:text-primary-500 dark:marker:text-primary-400">
                    <li class="text-sm text-gray-700 dark:text-gray-300">
                      CPU symbolic simulation:
                      <a class="inline-flex items-center whitespace-nowrap px-2 py-0.5 ml-1 rounded-md text-xs font-medium bg-primary-50 dark:bg-primary-900/40 text-primary-700 dark:text-primary-200 hover:bg-primary-100 dark:hover:bg-primary-900/60 no-underline transition-colors" href="https://link.springer.com/chapter/10.1007/978-3-031-30820-8_2">TACAS'23</a>
                      <a class="inline-flex items-center whitespace-nowrap px-2 py-0.5 ml-1 rounded-md text-xs font-medium bg-primary-50 dark:bg-primary-900/40 text-primary-700 dark:text-primary-200 hover:bg-primary-100 dark:hover:bg-primary-900/60 no-underline transition-colors" href="https://ieeexplore.ieee.org/abstract/document/10178019/">TCAD'23</a>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
            <div class="rounded-xl border border-gray-200 dark:border-gray-700 border-l-4 border-l-primary-500 dark:border-l-primary-400 bg-white/60 dark:bg-gray-800/40 p-5 shadow-sm">
              <h3 class="m-0 text-lg font-bold text-gray-900 dark:text-white"><em class="not-italic text-primary-700 dark:text-primary-300">Task View:</em> VLSI Design and Verification</h3>
              <div class="mt-4 space-y-4">
                <div>
                  <p class="m-0"><mark class="bg-yellow-100 dark:bg-yellow-300/15 text-gray-900 dark:text-yellow-100 px-1.5 py-0.5 rounded font-semibold">- Design Quality: PPA Evaluation &amp; Optimization</mark></p>
                  <ul class="mt-2 mb-0 space-y-1.5 list-disc pl-5 marker:text-primary-500 dark:marker:text-primary-400">
                    <li class="text-sm text-gray-700 dark:text-gray-300">
                      <span>RTL stage:</span>
                      <span class="inline-flex flex-wrap items-center gap-x-1 gap-y-1 align-baseline">
                        <span class="font-medium text-gray-900 dark:text-gray-100 whitespace-nowrap">MasterRTL</span>
                        <a class="inline-flex items-center whitespace-nowrap px-2 py-0.5 rounded-md text-xs font-medium bg-primary-50 dark:bg-primary-900/40 text-primary-700 dark:text-primary-200 hover:bg-primary-100 dark:hover:bg-primary-900/60 no-underline transition-colors" href="https://ieeexplore.ieee.org/abstract/document/10577671/">TCAD'24</a>
                        <a class="inline-flex items-center whitespace-nowrap px-2 py-0.5 rounded-md text-xs font-medium bg-primary-50 dark:bg-primary-900/40 text-primary-700 dark:text-primary-200 hover:bg-primary-100 dark:hover:bg-primary-900/60 no-underline transition-colors" href="https://ieeexplore.ieee.org/abstract/document/10323951">ICCAD'23</a><span>,</span>
                        <span class="font-medium text-gray-900 dark:text-gray-100 whitespace-nowrap">RTL-Timer</span>
                        <a class="inline-flex items-center whitespace-nowrap px-2 py-0.5 rounded-md text-xs font-medium bg-primary-50 dark:bg-primary-900/40 text-primary-700 dark:text-primary-200 hover:bg-primary-100 dark:hover:bg-primary-900/60 no-underline transition-colors" href="https://dl.acm.org/doi/abs/10.1145/3649329.3655671">DAC'24</a><span>,</span>
                        <span class="font-medium text-gray-900 dark:text-gray-100 whitespace-nowrap">CircuitEncoder</span>
                        <a class="inline-flex items-center whitespace-nowrap px-2 py-0.5 rounded-md text-xs font-medium bg-primary-50 dark:bg-primary-900/40 text-primary-700 dark:text-primary-200 hover:bg-primary-100 dark:hover:bg-primary-900/60 no-underline transition-colors" href="https://dl.acm.org/doi/abs/10.1145/3658617.3697597">ASPDAC'25</a><span>,</span>
                        <span class="font-medium text-gray-900 dark:text-gray-100 whitespace-nowrap">CircuitFusion</span>
                        <a class="inline-flex items-center whitespace-nowrap px-2 py-0.5 rounded-md text-xs font-medium bg-primary-50 dark:bg-primary-900/40 text-primary-700 dark:text-primary-200 hover:bg-primary-100 dark:hover:bg-primary-900/60 no-underline transition-colors" href="https://openreview.net/forum?id=rbnf7oe6JQ">ICLR'25</a><span>,</span>
                        <span class="font-medium text-gray-900 dark:text-gray-100 whitespace-nowrap">Dr. RTL</span>
                        <a class="inline-flex items-center whitespace-nowrap px-2 py-0.5 rounded-md text-xs font-medium bg-primary-50 dark:bg-primary-900/40 text-primary-700 dark:text-primary-200 hover:bg-primary-100 dark:hover:bg-primary-900/60 no-underline transition-colors" href="https://arxiv.org/abs/2604.14989">ICCAD'26</a>
                      </span>
                    </li>
                    <li class="text-sm text-gray-700 dark:text-gray-300">
                      <span>Netlist/Layout stage:</span><br>
                      <span class="font-medium text-gray-900 dark:text-gray-100 whitespace-nowrap">NetTAG</span>
                      <a class="inline-flex items-center whitespace-nowrap px-2 py-0.5 rounded-md text-xs font-medium bg-primary-50 dark:bg-primary-900/40 text-primary-700 dark:text-primary-200 hover:bg-primary-100 dark:hover:bg-primary-900/60 no-underline transition-colors" href="https://arxiv.org/abs/2504.09260">DAC'25</a>
                    </li>
                  </ul>
                </div>
                <div>
                  <p class="m-0"><mark class="bg-yellow-100 dark:bg-yellow-300/15 text-gray-900 dark:text-yellow-100 px-1.5 py-0.5 rounded font-semibold">- Functionality: Correctness Verification</mark></p>
                  <ul class="mt-2 mb-0 space-y-1.5 list-disc pl-5 marker:text-primary-500 dark:marker:text-primary-400">
                    <li class="text-sm text-gray-700 dark:text-gray-300">
                      <span>Hardware formal verification:</span>
                      <span class="inline-flex flex-wrap items-center gap-x-1 gap-y-1 align-baseline">
                        <span class="font-medium text-gray-900 dark:text-gray-100 whitespace-nowrap">AssertLLM</span>
                        <a class="inline-flex items-center whitespace-nowrap px-2 py-0.5 rounded-md text-xs font-medium bg-primary-50 dark:bg-primary-900/40 text-primary-700 dark:text-primary-200 hover:bg-primary-100 dark:hover:bg-primary-900/60 no-underline transition-colors" href="https://arxiv.org/abs/2402.00386">ASPDAC'25</a>
                        <a class="inline-flex items-center whitespace-nowrap px-2 py-0.5 rounded-md text-xs font-medium bg-primary-50 dark:bg-primary-900/40 text-primary-700 dark:text-primary-200 hover:bg-primary-100 dark:hover:bg-primary-900/60 no-underline transition-colors" href="https://zhiyaoxie.com/files/ICCAD24_OpenLLM.pdf">ICCAD'24</a><span>,</span>
                        <span class="font-medium text-gray-900 dark:text-gray-100 whitespace-nowrap">WASIM</span>
                        <a class="inline-flex items-center whitespace-nowrap px-2 py-0.5 rounded-md text-xs font-medium bg-primary-50 dark:bg-primary-900/40 text-primary-700 dark:text-primary-200 hover:bg-primary-100 dark:hover:bg-primary-900/60 no-underline transition-colors" href="https://link.springer.com/chapter/10.1007/978-3-031-30820-8_2">TACAS'23</a><span>,</span>
                        <span class="font-medium text-gray-900 dark:text-gray-100 whitespace-nowrap">r-map</span>
                        <a class="inline-flex items-center whitespace-nowrap px-2 py-0.5 rounded-md text-xs font-medium bg-primary-50 dark:bg-primary-900/40 text-primary-700 dark:text-primary-200 hover:bg-primary-100 dark:hover:bg-primary-900/60 no-underline transition-colors" href="https://ieeexplore.ieee.org/abstract/document/10178019/">TCAD'23</a>
                      </span>
                    </li>
                    <li class="text-sm text-gray-700 dark:text-gray-300">
                      <span>Functional reasoning:</span>
                      <span class="inline-flex flex-wrap items-center gap-x-1 gap-y-1 align-baseline">
                        <span class="font-medium text-gray-900 dark:text-gray-100 whitespace-nowrap">NetTAG</span>
                        <a class="inline-flex items-center whitespace-nowrap px-2 py-0.5 rounded-md text-xs font-medium bg-primary-50 dark:bg-primary-900/40 text-primary-700 dark:text-primary-200 hover:bg-primary-100 dark:hover:bg-primary-900/60 no-underline transition-colors" href="https://arxiv.org/abs/2504.09260">DAC'25</a><span>,</span>
                        <span class="font-medium text-gray-900 dark:text-gray-100 whitespace-nowrap">CircuitEncoder</span>
                        <a class="inline-flex items-center whitespace-nowrap px-2 py-0.5 rounded-md text-xs font-medium bg-primary-50 dark:bg-primary-900/40 text-primary-700 dark:text-primary-200 hover:bg-primary-100 dark:hover:bg-primary-900/60 no-underline transition-colors" href="https://dl.acm.org/doi/abs/10.1145/3658617.3697597">ASPDAC'25</a><span>,</span>
                        <span class="font-medium text-gray-900 dark:text-gray-100 whitespace-nowrap">GenEDA</span>
                        <a class="inline-flex items-center whitespace-nowrap px-2 py-0.5 rounded-md text-xs font-medium bg-primary-50 dark:bg-primary-900/40 text-primary-700 dark:text-primary-200 hover:bg-primary-100 dark:hover:bg-primary-900/60 no-underline transition-colors" href="https://arxiv.org/abs/2504.09485">ICCAD'25</a>
                      </span>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
    design:
      columns: '1'
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
      text: "(first-authored publications)"
      count: 100
      filters:
        folders:
          - publication
        featured_only: true
      archive:
        enable: true
        text: "See all publications →"
        link: "/publication/"
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
  - block: resume-experience
    id: experience
    content:
      username: admin
    design:
      date_format: Jan 2006
      show_education: false
  - block: markdown
    id: awards
    content:
      title: ''
      subtitle: ''
      text: |-
        <div class="relative left-1/2 w-[calc(100vw-3rem)] max-w-5xl -translate-x-1/2 grid grid-cols-1 md:grid-cols-[10rem_1fr] gap-4 md:gap-6">
          <div>
            <h2 class="text-3xl font-bold text-gray-900 dark:text-white">Awards</h2>
          </div>
          <div>
            <ul class="space-y-3">
              <li>HKUST RedBird Academic Excellence Award for Continuing PhD Students, 2026</li>
              <li>Inaugural <a href="https://iclad.ai/lad25-fellows">LAD Fellowship</a>, 2025</li>
              <li>2nd Place Award of <a href="https://src.acm.org/winners/2026">ACM SIGDA Student Research Competition (SRC)</a>, ICCAD, 2025</li>
              <li>ICCAD Student Scholar Program Grant, 2023, 2025</li>
              <li>IEEE CASS Student Travel Grant, 2025</li>
              <li>IEEE CEDA Student Travel Grant, 2025</li>
              <li>DAC Young Fellow, 2024, 2025</li>
              <li>ISLAD Best Paper Nomination, 2024</li>
              <li>ISLAD Travel Grant, 2024</li>
              <li>Full Postgraduate Studentship of HKUST, 2024-Now</li>
              <li>3rd Place Award of <a href="https://sites.google.com/view/ceda-hk/edathon-2023">EDAthon Contest</a>, 2023</li>
              <li>Full Postgraduate Studentship of HKUST(GZ), 2022-2024</li>
              <li>Infineon Technology Scholarship, 2020</li>
              <li>First Class Scholarship of NUAA, 2017-2021</li>
            </ul>
          </div>
        </div>
    design:
      columns: '1'

  - block: markdown
    id: talks
    content:
      title: ''
      subtitle: ''
      text: |-
        <div class="relative left-1/2 w-[calc(100vw-3rem)] max-w-5xl -translate-x-1/2 grid grid-cols-1 md:grid-cols-[10rem_1fr] gap-4 md:gap-6">
          <div>
            <h2 class="text-3xl font-bold text-gray-900 dark:text-white">Talks</h2>
          </div>
          <div>
            <ul class="space-y-5">
              <li>
                <strong>Advancing AI for EDA: from Supervised Learning to Circuit Foundation Models</strong>
                <ul>
                  <li>ACM SIGDA Student Research Competition (SRC) @ ICCAD, 2025</li>
                  <li>Institute of Microelectronics of the Chinese Academy of Science, 2025</li>
                </ul>
              </li>
              <li>
                <strong>RTL-Stage PPA Prediction for Early Optimization</strong>
                <ul>
                  <li>Synopsys, 2025</li>
                  <li>Southeast University, 2025</li>
                </ul>
              </li>
              <li>
                <strong>Towards Automatic and Scalable Hardware Formal Verification</strong>
                <ul>
                  <li>Intel, 2024</li>
                  <li>MPhil thesis defence, 2024</li>
                </ul>
              </li>
            </ul>
          </div>
        </div>
    design:
      columns: '1'

  - block: markdown
    id: service
    content:
      title: ''
      subtitle: ''
      text: |-
        <div class="relative left-1/2 w-[calc(100vw-3rem)] max-w-5xl -translate-x-1/2 grid grid-cols-1 md:grid-cols-[10rem_1fr] gap-4 md:gap-6">
          <div>
            <h2 class="text-3xl font-bold text-gray-900 dark:text-white">Services</h2>
          </div>
          <div>
            <ul class="space-y-5">
              <li>
                <strong>Journal Reviewer</strong>
                <ul>
                  <li>IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (<strong>TCAD</strong>)</li>
                  <li>ACM Transactions on Design Automation of Electronic Systems (<strong>TODAES</strong>)</li>
                  <li>IEEE Transactions on Circuits and Systems Part II: Express Briefs (<strong>TCAS-II</strong>)</li>
                </ul>
              </li>
              <li>
                <strong>Conference Reviewer</strong>
                <ul>
                  <li>ICLR 2026 Workshop on AI with Recursive Self-Improvement</li>
                </ul>
              </li>
            </ul>
          </div>
        </div>
        
    design:
      columns: '1'
      
    
  - block: markdown
    id: teaching
    content:
      title: ''
      subtitle: ''
      text: |-
        <div class="relative left-1/2 w-[calc(100vw-3rem)] max-w-5xl -translate-x-1/2 grid grid-cols-1 md:grid-cols-[10rem_1fr] gap-4 md:gap-6">
          <div>
            <h2 class="text-3xl font-bold text-gray-900 dark:text-white">Teaching</h2>
          </div>
          <div>
            <ul class="space-y-5">
              <li>
                <strong>Teaching Assistant</strong>
                <ul>
                  <li>Introduction to Computer Organization and Design, HKUST</li>
                  <li>Electronic Design Automation for VLSI Design, HKUST</li>
                  <li>Logic Design Automation of Digital Systems, HKUST(GZ)</li>
                </ul>
              </li>
            </ul>
          </div>
        </div>
        
    design:
      columns: '1'
        
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
