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
      title: '🔬 관심 분야'
      subtitle: ''
      text: |-
        drug.svg
    design:
      columns: '1'
  - block: markdown
    content:
      title: '🗺️ 연구실 위치'
      text: |-
        <iframe 
          src="https://www.google.com/maps/embed/v1/place?key=YOUR_API_KEY&q=35.8461404,127.1314466"
          width="600" 
          height="450" 
          style="border:0;" 
          allowfullscreen="" 
          loading="lazy" 
          referrerpolicy="no-referrer-when-downgrade">
        </iframe>
    design:
      columns: '1'

  - block: collection
    id: news
    content:
      title: 최근 소식
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
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
---
