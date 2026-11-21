---
# Leave the homepage title empty to use the site title
title: "Myungsub Choi"
date: 2025-04-20
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
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
      # Tighter hero so the News section starts sooner (default section spacing is 6rem)
      spacing:
        padding: ["3rem", "0", "4rem", "0"]
  # Section order: Bio -> News -> Publications -> Talks -> Experience
  # (keep config/_default/menus.yaml in the same order)
  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: date-title-summary
  - block: collection
    id: publications
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: Talks
      text: ""
      count: 5
      filters:
        folders:
          - events
    design:
      view: date-title-summary
  - block: resume-experience
    id: experience # Add an ID to link to this section
    content:
      title: Experience # Add a title for the section
      username: admin
      # Hugo date format
      date_format: 'Jan 2006'
      # Education or Experience section first?
      is_education_first: false
    design:
      # Optional: Adjust spacing specific to this section
      spacing:
        padding: ["6rem", "0", "6rem", "0"] # top, right, bottom, left
---
