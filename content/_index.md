---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Apply a gradient background
      css_class: hbx-bg-gradient
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
    
  - block: prose           # ← change type
    id: working-papers
    content:
      title: "Working Papers"
      text: |              # ← key MUST be `text:` for prose
        * **Financial-Regulation Pass-through in the U.S. Life-Insurance Industry**  
          with Paul Kim — *latest draft: Oct 2025*  
          [PDF](/files/zhu_kim_rbc_pass_through.pdf)

        * **Health & Well-being Impacts of Self-Directed Care Programs**  
          with Eilidh Geddes & Alison Morantz — *work in progress*  
          [Abstract](/files/sdc_abstract.pdf)

  - block: prose
    id: works-in-progress
    content:
      title: "Works in Progress"
      text: |
        * **Structural Demand–Supply Model of Nursing-Home Markets**  
          Job-market paper — replication code coming soon

        * **Private-Credit & RBC Charges in U.S. Life Insurers**  
          Data construction phase
    
---
