---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
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
          # filename: stacked-peaks.svg
          filename: bg.jpg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '📚 My Research/Work Interest'
      subtitle: ''
      text: |-
        I have worked as a research assistant in the Computer Motion Group, led by Prof. Christopher Batty. Our focus was on the re-meshing process in surface tracking, where we explored promising techniques that preserve shapes more effectively than traditional methods. This experience has deepened my interest in graphics and geometry.

        After attending SGI and completing several exiting projects, I have also developed an interest in the applications of computer graphics, computer vision, and geometry processing, particularly in how they integrate with trending technologies such as VR/AR.

        Please feel free to reach out if there are any co-op or research opportunities! 😃
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Projects
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    id: papers
    content:
      title: Featured Projects2
      filters:
        folders:
          - project
        featured_only: true
    design:
      view: article-grid
      columns: 2
---
