---
# Leave the homepage title empty to use the site title
title: ""
date: 2024-01-01
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download One-Pager
        url: uploads/winston-gan-projects-onepager.pdf
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

  - block: markdown
    content:
      title: '📋 Projects Overview'
      subtitle: ''
      text: |-
        I've led and contributed to integrations and growth initiatives across major e-commerce and consumer platforms. Below are selected highlights — click each project for full details.
    design:
      columns: '1'

  - block: collection
    id: projects
    content:
      title: Featured Projects
      filters:
        folders:
          - project
    design:
      view: article-grid
      columns: 3

  - block: resume-experience
    content:
      username: me
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false

  - block: resume-skills
    content:
      title: Skills & Expertise
      username: me
    design:
      show_skill_percentage: false

  - block: resume-awards
    content:
      title: Education
      username: me

  - block: resume-interests
    content:
      title: Interests
      username: me

  - block: cta-card
    demo: true
    content:
      title: "📁 Full Project One-Pager"
      text: A consolidated overview of all projects — Klaviyo, Shopify, Shop App, Meta LVA, and Instacart integrations.
      button:
        text: Coming Soon
        url: "#"
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
