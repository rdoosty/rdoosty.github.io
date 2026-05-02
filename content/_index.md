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
        size: md
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
        research lies at the intersection of **wireless networking**,
        **machine learning**, and **reconfigurable computing and
        software-defined systems** — building intelligent, programmable
        wireless infrastructure for next-generation networks (5G/6G and
        Open RAN).

        I currently lead [**ETHOS**](https://ethos.rice.edu) — a
        multi-dimensional approach to ML-enabled RAN software testing
        (NTIA Public Wireless Supply Chain Innovation Fund, 2024–2028).
        Previously, I led [**3DML**](https://3dml.rice.edu) (NSF CCRI,
        2020–2023) and co-led [**RENEW**](https://renew.rice.edu) (NSF
        PAWR, 2018–2023) — an open-source software-defined massive MIMO
        platform deployed on the POWDER testbed.

        ## Selected Research (since 2020)

        My recent work spans a few interrelated themes:

        - **AI-driven resource allocation for wireless networks.** Real-time
          ML for scheduling, link adaptation, and beyond:
          [Deep RL Resource Scheduler](/publications/an2023drl/) (TMLCN'23),
          [Feedback-Free Adaptive MCS](/publications/an2023mcs/) (Asilomar'23).

        - **ML-based massive MIMO detection.** Sampling-based detectors
          that approach ML accuracy at far lower complexity:
          [Annealed Langevin Detector](/publications/zilberstein2022langevin/) (TWC'22),
          [Accelerated Underdamped Langevin Detector](/publications/zilberstein2023icassp/) (ICASSP'23).

        - **Software-defined massive MIMO baseband and platforms.** Real-time
          baseband processing on commodity CPUs and at-scale open testbeds:
          [Agora](/publications/ding2020agora/) (CoNEXT'20),
          [Scalable Massive MIMO](/publications/shepard2020openwireless/) (OpenWireless'20),
          [Good Times for Wireless Research](/publications/doost2020wintech/) (WiNTECH'20).

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
      view: card
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
      view: card
      spacing:
        padding: [0, 0, 0, 0]
---
