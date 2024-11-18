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
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '📚 My Goal'
      subtitle: ''
      text: |-
        As a passionate Computer Science student, my goal is to contribute to the advancement of robotics and machine learning by developing intelligent systems that can solve real-world problems. I aim to deepen my expertise in artificial intelligence, control systems, and embedded technologies, while leveraging my creativity and technical skills to design innovative and autonomous robotic solutions. By combining the power of robotics and machine learning, I aspire to work on projects that enhance automation, improve human lives, and pave the way for cutting-edge technological breakthroughs
        
        Please reach out to collaborate 😃
    design:
      columns: '1'
 
 
  - block: collection
    id: talks
    content:
      title: Certificate
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1

  - block: markdown
    id: papers
    content:
      title: contact me
      text: |-
        You can reach me out here
    
          email: ummahabibaeti@gmail.com    
          phone:017****76    
          GitHub: https://github.com/Umma-Habiba-Eti
    
    design:     
      columns: 1
  
---
