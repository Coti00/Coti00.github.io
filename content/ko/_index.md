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

  - block: slider
    content:
      slides:
      - title: <span style="font-size:70%">AI 신약개발</span>
        content: <span style="font-size:70%">타겟 단백질 예측 & 세포 독성 예측</span>
        align: center
        background:
          image:
            filename: 
            filters:
              brightness: 0.4
          position: center
          color: '#000'
      - title: <span style="font-size:70%">프런트</span>
          content: <span style="font-size:70%">래액트를 활용</span>
          align: center
          background:
            image:
              filename: 
              filters:
                brightness: 0.4
            position: center
            color: '#000'
      - title: <span style="font-size:70%">학부연구생</span>
        content: <span style="font-size:70%">적응형 AI 연구실에서 자연어처리 공부</span>
        align: center
        background:
          image: 
            filename: 
            filters:
              brightness: 0.4
          position: center
          color: '#000'
    design:
        # Slide height is automatic unless you force a specific height (e.g. '400px')
        slide_height: '350px'
        slide_width: '100px'
        is_fullscreen: false
        # Automatically transition through slides?
        loop: true
        # Duration of transition between slides (in ms)
        interval: 3000
        
  - block: markdown
    content:
      title: '🔬 연구 분야'
      subtitle: ''
      text: |-
        <b>자연어처리 기반으로 타겟 단백질 또는 세포 독성을 예측하는 분야를 공부 중 입니다.</b>
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
