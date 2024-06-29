---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: markdown
    content:
      title: Activities
      text: June 2024 - Chair for a panel at EAMT titled "LLMs and Machine Translation for Low-Resource Languages Bridging Gaps or Widening Divides?"
    # text: March 2024 - Organiser of First Workshop on NLP for Indigenous Languages of Lusophone Countries, co-located with PROPOR 2024
    design:
      view: compact
  - block: collection
    content:
      title: Publications
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
---
