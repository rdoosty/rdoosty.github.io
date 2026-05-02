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

        ## Selected Publications

        - **Many-antenna massive MIMO platforms and real-time baseband.**
          From hardware architectures that scale to hundreds of coherent
          radio chains, to software-only baseband processing on commodity
          servers:
          [Agora](/publications/ding2020agora/) (ACM CoNEXT'20),
          [ArgosV3](/publications/shepard2017argosv3/) (ACM MobiCom'17).

        - **Open testbeds and wireless research methodology.** Reflections
          on the new wave of open, programmable, large-scale wireless
          experimentation:
          [Good Times for Wireless Research](/publications/doost2020wintech/) (ACM WiNTECH'20).

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
