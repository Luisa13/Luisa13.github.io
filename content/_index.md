---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  ## BLOCK - BIO
  #
  - block: resume-biography-3
    content: # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: '
        I am a software engineer with solid fundation building and operating cloud-native, distributed systems and event-driven architectures, with hands-on ownership across the full software development lifecycle. My background spans on consumer platforms, fintech-like systems and real-time software.
        Comfortable working in cross-functional, product-driven teams, contributing to architectural decisions and technical planning. <br><br>

        I got hands on experience in machine learning developing projects and prototypes based on speech recognition and computer vision. <br>
        I previously worked in <a href="https://sy-dep-bi.web.cern.ch/sw" style="color : blue;"> Beans Intrumentation department at CERN </a> where I developed real time software and interactive tools for data visualization. <br><br>

        '


      button:
        text: Download my CV
        url: uploads/resume.pdf

      headings:
        about: 'About me'
        education: 'Education'
        interests: ''

    design:
      background:
        gradient_mesh: 
          enable: true

      name: # Name heading sizing to accommodate long or short names
        size: md # Options: xs, sm, md, lg (default), xl

      avatar:  # Avatar customization
        size: medium # Options: small (150px), medium (200px, default), large (320px), x(400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded

  ## BLOCK - EXPERIENCE
  #
  - block: resume-experience
    id: experience
    content:
      username: me
    design:
      columns: 2
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  
  ## BLOCK - FEATURES
  #

  # - block: features
  #   content:
  #     title: "Languages"
  #     items:
  #       - name: "Spanish"
  #         description: "Lightning-fast load times for better user experience"
  #         icon: "bolt"
  #       - name: "English"
  #         description: "Intuitive interface that anyone can master"
  #         icon: "heart"
  #       - name: "French"
  #         description: "Enterprise-grade security built-in"
  #         icon: "shield-check"
  #   design:
  #     columns: "3"
  #     background:
  #       color: "gray-50"
  

  

  # NEWS content
  # - block: collection
  #   id: news
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: blog
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 10
  #     # Filter on criteria
  #     filters:
  #       author: ''
  #       category: ''
  #       tag: ''
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ''
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: card
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]
  
---
