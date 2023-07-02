---
# Leave the homepage title empty to use the site title
title:
date: 2023-07-02
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: ''
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: publications
    content:
      title: Publications
      # text: |-
      #   {{% callout note %}}
      #   Quickly discover relevant content by [filtering publications](./publication/).
      #   {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: experience
    id: experience
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
        - title: Undergraduate researcher
          company: Optimization & Machine Learning Lab (OptiML Lab)
          company_url: https://chulheeyun.github.io
          company_logo: ''
          location: KAIST AI, South Korea
          date_start: '2022-01-01'
          date_end: ''
          description: Under supervision of Prof. [Chulhee Yun](https://chulheeyun.github.io)
        - title: AI Research Engineer
          company: Upstage AI
          company_url: https://www.upstage.ai
          company_logo: ''
          location: South Korea
          date_start: '2022-09-01'
          date_end: '2022-11-30'
          description: Designed real-time recommendation models using contextual bandit algorithms and applied them to e-commerce service.
        - title: Undergraduate researcher
          company: Applied Artificial Intelligence Lab (AAI Lab)
          company_url: https://aailab.kaist.ac.kr/xe2/
          company_logo: ''
          location: KAIST ISysE, South Korea
          date_start: '2021-06-01'
          date_end: '2021-12-31'
          description: Under supervision of Prof. [Il-Chul Moon](https://aailab.kaist.ac.kr/xe2/members_professor/6749)
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
