---
title: ""
date: 2024-01-01
type: landing

design:
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ""
      button:
        text: Download One-Pager
        url: uploads/winston-gan-projects-onepager.pdf
    design:
      css_class: dark
      background:
        color: "#1a1a2e"

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
      date_format: 'January 2006'
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

  - block: markdown
    content:
      title: Interests
      text: |-
        Product Management · AI & Machine Learning · Go-to-Market Strategy · E-commerce & Platform Integrations · Growth Analytics
    design:
      columns: '1'

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
        css_class: "bg-primary-700"
        css_style: ""
---
