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

  - block: features
    id: hobbies
    content:
      title: 취미 & 관심사
      text: 저의 취미와 관심사는 아래와 같습니다!
      items:
        - name: 고양이
          icon: "custom/cat"
          description: 이름이 '티거'인 고양이를 키우고 있습니다!
        - name: 강아지
          icon: "custom/dog"
          description: 이름이 '코코'인 강아지를 키우고 있습니다!
        - name: 음악
          icon: "custom/music"
          description: 음악을 듣거나 피아노를 치면서 스트레스를 풉니다!

  - block : collection
    id: mainlang
    content:
      title: 주 사용 언어
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
    design:
      view: community/slider
      row: 1
      columns: 1

---
