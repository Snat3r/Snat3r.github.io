---
# Leave the homepage title empty to use the site title
title: 'Coen van der Geest'
date: 2023-12-09
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
      title: 'Teaching'
      subtitle:
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: ' '
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.

      # Start date is required, but not shown on the web page.
      items:
        - certificate_url: ''
          date_end: ''
          date_start: '2023-01-01'
          description: |-
            Coordinator and lecturer, The aim of the course is to familiarize students with quantitative research and statistical models (e.g., T-tests, ANOVAs, OLS regressions, and PCA). The course walks students through the most important concepts relating to quantitative research, starting with the need for academic research and science, through what a theory entails, to the different statistical models.
          icon: 
          organization: Executive Master
          organization_url: 
          title: Methods and Techniques Quantitative
          url: ''
        - certificate_url: 
          date_end: ''
          date_start: '2022-01-01'
          description: |-
            Co-coordinator and lecturer on the topics of Standards and Dominant Designs, and Platforms and Ecosystems. In this course, students learn to understand and apply basic theories behind the processes of technology-based innovation in organizations and their environments, the development of innovation strategies, and the organizational implementation of innovation strategies. Theoretical understanding is applied in an online simulation and real-life cases focusing on managerial dilemmas in the management of technology. 
          icon: 
          organization: Third-year Bachelor Elective
          organization_url: 
          title: Strategic Management of Technology and Innovation
          url: 
        - certificate_url: 
          date_end: ''
          date_start: '2021-01-01'
          description: |-
            Tutorial teacher, in the course we cover the basic research designs and methods for conducting rigorous quantitative research. The objective of the course is to enable students to understand, select, and apply the proper methods for their research questions. At the end of the course, students will have a comprehensive overview of the most used methodologies and will be able to apply them to real-world data using their statistical software of choice.
          icon: 
          organization: Compulsary Master Course
          organization_url: 
          title: 'Research Design and Methods Quantitative'
          url: ''
        - certificate_url: 
          date_end: ''
          date_start: '2022-01-01'
          description: |-
            Guest lecturer, on the topic of Application Programming Interfaces (APIs) and IT Architectures. The lecture focusses on the use of APIs and IT architectures in digital businesses, specifically, how APIs can be leveraged in the creation of new products and services, how APIs are supported by different types of IT architecture, and the emergence of the asynchronous Event-Driven Architecture. 
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
