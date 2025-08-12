---
# Leave the homepage title empty to use the site title
title: 'Coen van der Geest'
date: 2025-01-27
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
#  - block: skills
#    content:
#      title: Skills
#      text: ''
#      # Choose a user to display skills from (a folder name within `content/authors/`)
#      username: admin
#    design:
#      columns: '1'
#  - block: experience
#    content:
#      title: Experience
#      # Date format for experience
#      #   Refer to https://docs.hugoblox.com/customization/#date-format
#      date_format: Jan 2006
#      # Experiences.
#      #   Add/remove as many `experience` items below as you like.
#      #   Required fields are `title`, `company`, and `date_start`.
#      #   Leave `date_end` empty if it's your current employer.
#      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
#      items:
#        - title: CEO
#          company: GenCoin
#          company_url: ''
#          company_logo: org-gc
#          location: California
#          date_start: '2021-01-01'
#          date_end: ''
#          description: |2-
#              Responsibilities include:
#
#              * Analysing
#              * Modelling
#              * Deploying
#        - title: Professor of Semiconductor Physics
#          company: University X
#          company_url: ''
#          company_logo: org-x
#          location: California
#          date_start: '2016-01-01'
#          date_end: '2020-12-31'
#          description: Taught electronic engineering and researched semiconductor physics.
#    design:
#      columns: '2'
#  - block: collection
#    id: posts
#    content:
#      title: Recent Posts
#      subtitle: ''
#      text: ''
#      # Choose how many pages you would like to display (0 = all pages)
#      count: 5
#      # Filter on criteria
#      filters:
#        folders:
#          - post
#        author: ""
#        category: ""
#        tag: ""
#        exclude_featured: false
#        exclude_future: false
#        exclude_past: false
#        publication_type: ""
#      # Choose how many pages you would like to offset by
#      offset: 0
#      # Page order: descending (desc) or ascending (asc) date.
#      order: desc
#    design:
#      # Choose a layout view
#      view: compact
#      columns: '2'
#  - block: markdown
#    content:
#      title: Gallery
#      subtitle: ''
#      text: |-
#        {{< gallery album="demo" >}}
#    design:
#      columns: '1'
  - block: collection
    id: research
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
      title: Published & Work-in-progress
      text:
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: citation
  - block: accomplishments
    id: teaching
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Teaching Experience'
      subtitle:
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: '2006'
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.

      # Start date is required, but not shown on the web page.
      items:
        - certificate_url: ''
          date_end: 'Ongoing'
          date_start: '2025-01-01'
          description: ''
          icon: 
          organization: MSc in Information Systems
          organization_url: 
          title: Applied Machine Learning
          url: ''
        - certificate_url: ''
          date_end: 'Ongoing'
          date_start: '2025-01-01'
          description: ''
          icon: 
          organization: MSc in Information Systems
          organization_url: 
          title: Internet of Things
          url: ''
        - certificate_url: ''
          date_end: 'Ongoing'
          date_start: '2025-01-01'
          description: ''
          icon: 
          organization: BSc in Information Systems
          organization_url: 
          title: Big Data Analytics for Managers
          url: '' 
        - certificate_url: ''
          date_end: '2024-01-01'
          date_start: '2022-01-01'
          description: ''
          icon: 
          organization: Executive Master and MSc in Digital Business and Innovation
          organization_url: 
          title: Methods and Techniques - Quantitative
          url: ''
        - certificate_url: 
          date_end: '2024-01-01'
          date_start: '2021-01-01'
          description: ''
          icon: 
          organization: Third-year Bachelor Elective
          organization_url: 
          title: Strategic Management of Technology and Innovation
          url: 
        - certificate_url: 
          date_end: '2023-01-01'
          date_start: '2022-01-01'
          description: ''
          icon: 
          organization: Third-year Bachelor Elective
          organization_url: 
          title: 'Information Systems in E-Business and Online Commerce'
          url: ''
    design:
      columns: '2'
#  - block: portfolio
#    id: teaching
#    content:
#      title: Teaching
#      filters:
#        folders:
#          - teaching
#      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
#      default_button_index: 0
#      # Filter toolbar (optional).
#      # Add or remove as many filters (`filter_button` instances) as you like.
#      # To show all items, set `tag` to "*".
#      # To filter by a specific tag, set `tag` to an existing tag name.
#      # To remove the toolbar, delete the entire `filter_button` block.
#      buttons:
#        - name: All
#          tag: '*'
#        - name: Information Systems
#          tag: IS
#        - name: Innovation Management
#          tag: IM
#        - name: Research Methods
#          tag: Methods
#    design:
#      # Choose how many columns the section has. Valid values: '1' or '2'.
#      columns: '2'
#      view: showcase
#      # For Showcase view, flip alternate rows?
#      flip_alt_rows: false
#  - block: collection
#    id: talks
#    content:
#      title: Recent & Upcoming Talks
#      filters:
#        folders:
#          - event
#    design:
#      columns: '2'
#      view: compact
---
