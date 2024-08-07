---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "4rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download my CV
        url: uploads/Academic_CV.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: collection
    id: research
    content:
      title: Research
      header:
        image: uploads/bandeau_research.jpg
      text: "My current research revolves around the impact of macroeconomic shocks on asset prices and, conversely, how asset prices reflect expectations of macroeconomic variables, accounting for financial market microstructure frictions."
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: teaching
    content:
      title: Teaching
      text: "I am a Teaching Assistant in Macroeconomics (Graduate) and Finance (Undergraduate) for the Department of Economics and the Saïd Business School at the University of Oxford. During my classes, I have had the opportunity to deeply engage with students and contribute to their academic and personal development. My commitment to teaching is centered around inclusiveness, a dual approach combining mathematical rigor and intuitive understanding, and providing students with additional resources and career guidance. My teaching has been distinguished by a teaching award."
      button:
        text: "Full teaching statement"
        url: uploads/Teaching_statement.pdf
      filters:
        folders:
          - teaching
      design:
        # Choose how many columns the section has. Valid values: '1' or '2'.
        columns: '1'
        # Choose your content listing view - here we use the `showcase` view
        view: showcase
        # For the Showcase view, do you want to flip alternate rows?
        flip_alt_rows: true
  - block: resume-experience
    id: vita
    content:
      title: Vita
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false

---
