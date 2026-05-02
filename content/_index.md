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
      title: '📚 Research'
      subtitle: ''
      text: |-
        My research lies at the intersection of **wireless networking**,
        **machine learning**, and **reconfigurable computing and
        software-defined systems**. I am interested in building intelligent,
        programmable wireless infrastructure for next-generation networks
        (5G/6G and Open RAN), with a focus on AI-driven resource
        allocation, RAN virtualization, and large-scale MIMO architectures.

        I currently lead [ETHOS](https://ethos.rice.edu) — a
        multi-dimensional approach to ML-enabled RAN software testing,
        funded by the NTIA Public Wireless Supply Chain Innovation Fund.
        Previously, I led [3DML](https://3dml.rice.edu) (NSF CCRI) and
        co-led [RENEW](https://renew.rice.edu) (NSF PAWR), an open-source
        massive MIMO software-defined radio platform deployed on POWDER.

        Please reach out if you are interested in collaborating.
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Recent Publications
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
