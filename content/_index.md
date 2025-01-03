---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing
text-align: justify

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
      banner:
        filename: "bandeau_research.jpg"
      title: Research
      text: "My current research revolves around the impact of macroeconomic shocks on asset prices and, conversely, how asset prices reflect expectations of macroeconomic variables, accounting for financial market microstructure frictions."
      button:
        text: "Download my Research Statement"
        url: uploads/Research_statement.pdf
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: resume-teaching
    id: teaching
    content:
      banner:
        filename: "oxford.jpg"
      title: Teaching
      text: "I am a Teaching Assistant in Macroeconomics (Graduate) and Finance (Undergraduate) for the Department of Economics and the Saïd Business School at the University of Oxford. During my classes, I have had the opportunity to deeply engage with students and contribute to their academic and personal development. My commitment to teaching is centered around inclusivity, a dual approach combining mathematical rigor and intuitive understanding, and providing students with additional resources and career guidance. My teaching has been distinguished by a teaching award."
      button:
        text: "Download my Teaching Statement"
        url: uploads/Teaching_statement.pdf
  - block: resume-experience
    id: vita
    content:
      banner:
        filename: "francfort.jpeg"
      title: Vita
      username: admin
      button:
        text: Download my CV
        url: uploads/Academic_CV.pdf
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  - block: markdown
    id: disclaimer
    content:
      text: "{{% callout class='callout' %}}
**Disclaimer:** Any views expressed are solely mine. In particular, these views should therefore not be reported as representing the views of the Bank of England or members of the Monetary Policy Committee, Financial Policy Committee, or Prudential Regulation Committee.
{{% /callout %}}"

---

