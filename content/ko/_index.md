---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "1rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      button:
        text: 수료증
        url: uploads/certi.pdf
      # Show a call-to-action button under your biography? (optional)
    design:
      css_class: dark
      background: 
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: galaxy.jpg
          filters:
            brightness: 0.5
          size: cover
          position: center
          parallax: false

  - block: collection
    content:
      title: ""
      filters:
        folders:
          - test
    design:
      view: community/slider
      rows: 1

  - block : collection
    id: interests
    content:
      title: 관심분야
      filters:
        folders:
          - interests
    design:
      view: community/custom_card3
      rows: 3
      columns: 3

  - block: skills
    content:
      title: 취미 & 언어
      username: admin

  - block : collection
    id: mainlang
    content:
      title: 주 사용 프로그래밍 언어
      filters:
        folders:
          - mainlang
    design:
      view: community/custom_card
      columns: '1'
      row: '3'

  - block : collection
    id: news
    content:
      title: 최근 소식
      filters:
        folders:
          - news
    design:
      view: community/custom_card2
      columns: '1'

  - block: collection
    content:
      title: '🗺️ 학교 위치'
      filters:
        folders:
          - map
    design:
      view: community/mapcard
      row: 1
      columns: 1

---
