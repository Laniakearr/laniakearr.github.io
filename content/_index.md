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

  - block: markdown
    content:
      title: '💬 Testimonials'
      subtitle: ''
      text: |
        > "Tina has very curious mind. This curiosity, along with her attention to detail, led her to identify areas of improvements in some elements of her tasks that were not outlined in the task description, and were very relevant."
        > "I feel that Tina is always looking for opportunities to learn and build up skills, which is an ideal attitude for both personal and professional development."
        >  "I felt my feedback was always welcome, and taken into account for the current and following tasks. Our exchanges were always pleasant and overall I liked working with her a lot."
        > "Tina was excellent to work with. She demonstrated enthusiasm, dedication, and strong technical skills, all of which will be critical skills for her success in future graduate studies and beyond. I believe she has the capacity to grow into a highly talented researcher."
        > "Tina is active in participating the discussion and development. She showed creativity in exploring different ways to implement an algorithm to make it perform better in our application."
        > "Tina was the key member in the team. Of the three students, Tina was the most knowledgeable about software development and the mathematics behind it."
    design:
      columns: '1'
---
