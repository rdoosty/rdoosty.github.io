---
title: ''
summary: ''
date: 2026-05-01
type: landing

design:
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: xs
      avatar:
        size: medium
        shape: circle
  - block: markdown
    content:
      title: ''
      subtitle: ''
      text: |-
        ## About

        I am an Assistant Research Professor in the Department of
        Electrical and Computer Engineering at Rice University. My
        research is at the intersection of **computer systems** and
        **wireless networking** — building programmable, intelligent
        infrastructure for 5G/6G and Open RAN, with a focus on
        **algorithm and system design across FPGA, GPU, and CPU**. This
        spans **software-defined massive MIMO baseband**, **scalable
        many-antenna platforms**, **virtualized RAN systems**, and
        **machine-learning-driven scheduling**.

        I currently lead [**ETHOS**](https://ethos.rice.edu) — a
        multi-dimensional approach to ML-enabled RAN software design
        (NTIA Public Wireless Supply Chain Innovation Fund, 2024–2028) —
        and co-lead [**Houdini**](https://houdini-sdr.org), an
        open-access multi-band software-defined radio platform (NSF
        CNS-2346550), and [**3DML**](https://3dml.rice.edu), a
        community platform for ML-driven wireless research (NSF CCRI,
        2020–2026). Previously, I co-led [**RENEW**](https://renew.rice.edu)
        (NSF PAWR, 2018–2023) — an open-source software-defined massive
        MIMO platform deployed on the POWDER testbed.

        ## Selected Publications

        - **Many-antenna massive MIMO platforms and real-time baseband.**
          From hardware architectures that scale to hundreds of coherent
          radio chains, to software-only baseband processing on commodity
          servers:
          [Agora](/publications/ding2020agora/) (ACM CoNEXT'20),
          [ArgosV3](/publications/shepard2017argosv3/) (ACM MobiCom'17).

        - **AI-driven scheduling and RAN slicing.** Real-time ML and
          slice-aware schedulers for massive MIMO:
          [Helix](/publications/an2024helix/) (ACM CoNEXT'24),
          [Deep RL Resource Scheduler](/publications/an2023drl/) (IEEE TMLCN'23).

        - **ML-based massive MIMO detection.** Sampling-based detectors
          that approach ML accuracy at far lower complexity:
          [Annealed Langevin Detector](/publications/zilberstein2022langevin/) (IEEE TWC'22).

        - **Virtualized Open RAN systems.** Measurement and design for
          5G O-RAN on commodity infrastructure:
          [ETHOS](/publications/wu2025ethos/) (ACM WiNTECH'25).

        - **Wireless physical-layer security.** PHY techniques that
          protect legitimate transmissions against eavesdroppers:
          [M3A](/publications/liu2023m3a/) (ACM MobiCom'23).

        ## Group

        **Postdoctoral Researchers**
        - [Milin Zhang](https://scholar.google.com/citations?user=P-zS4FwAAAAJ)
        - Zongshen Wu

        **Graduate Students**
        - Sergio Lavao (PhD)

        **Alumni**
        - Qing An — PhD'25, MS'23 → Apple
        - Mehdi Zafari — MS'24 → UC Irvine

        I am always happy to discuss collaborations — feel free to reach out.
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: All Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - events
    design:
      view: date-title-summary
  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      page_type: blog
      count: 10
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      offset: 0
      order: desc
    design:
      view: date-title-summary
      spacing:
        padding: [0, 0, 0, 0]
---
