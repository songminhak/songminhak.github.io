---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: ''
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: featured
    content:
      title: Publications
      # text: |-
      #   {{% callout note %}}
      #   Quickly discover relevant content by [filtering publications](./publication/).
      #   {{% /callout %}}
      # filters:
      #   folders:
      #     - publication
      #   exclude_featured: true
    design:
      columns: '2'
      view: citation
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
        - title: Undergraduate Researcher
          company: Optimization & Machine Learning Lab (OptiML Lab)
          company_url: 'https://chulheeyun.github.io'
          location: KAIST, South Korea
          date_start: '2022-01-01'
          date_end: ''
          description: |2-
          Under the supervision of Prof. Chulhee Yun
        - title: AI Research Engineer Intern
          company: Upstage AI
          company_url: 'https://en.upstage.ai'
          company_logo: org-x
          location: California
          date_start: '2021-09-01'
          date_end: '2020-11-31'
          description: |2-
          I designed real-time recommendation models using contextual bandit algorithms and applied them to e-commerce service.
    design:
      columns: '2'
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     columns: '2'
  #     view: compact
---
