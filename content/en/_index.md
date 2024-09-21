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
      button:
        text: Certification
        url: uploads/certi.pdf
      # Show a call-to-action button under your biography? (optional)
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

  - block: features
    id: features
    content:
      title: 🔍 My Interests
      text: Currently, I am interested in the following areas
      items:
        - name: AI
          icon: "custom/brain"
          description: Interested in the field of applying natural language processing to the development of new drugs
        - name: Drug_Discovery
          icon: "custom/drug"
          description: Interested in predicting target protein or cytotoxicity
        - name: FrontEnd
          icon: "custom/laptop"
          description: Use React to development
  - block: features
      id: lang
      content:
        title: Main Programming Language
        text: Currently, My main programming language
        items:
          - name: Python
            icon: "custom/python"
            description: Python's Pandas and Pytorch frameworks are used in data analysis and NLP
          - name: JavaScript
            icon: "custom/js"
            description: Mainly used when using the front end

  - block: markdown
    content:
      title: '🗺️ LAB Position'
      text: |-
        <p>Contact : jbnu20@jbnu.ac.kr</p>
        <p>Position : 전북대학교 학생군사교육단 3층 315호 </p>
        <iframe 
          src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3162.885343216497!2d127.1314466!3d35.8461404!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x357026f82e1f5771%3A0x10d7417d8b173a87!2sJeonbuk%20National%20University!5e0!3m2!1sen!2skr&zoom=18"
          width="600" 
          height="450" 
          style="border:0;" 
          allowfullscreen="" 
          loading="lazy" 
          referrerpolicy="no-referrer-when-downgrade">
        </iframe>
    design:
      columns: '1'

  - block : collection
    id: news
    content:
      title: Recent News
      filters:
        folders:
          - news
    design:
      view: article-grid
      rows: 3
      columns: 3
---
