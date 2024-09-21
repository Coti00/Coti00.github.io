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
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false        

  - block: features
    id: features
    content:
      title: 관심 분야
      text: 현재 저는 다음과 같은 분야에 관심이 있습니다
      items:
        - name: 인공지능
          icon: "custom/brain"
          description: 신약개발에 자연어처리를 적용하는 분야에 관심이 있음
        - name: 신약개발
          icon: "custom/drug"
          description: 타겟 단백질 또는 세포 독성 예측에 관심이 있음
        - name: 프런트엔드
          icon: "custom/laptop"
          description: 리액트를 활용하여 프런트엔드 개발
  - block: features
    id: lang
    content:
      title: 주 사용 프로그래밍 언어
      text: 현재 제가 주로 다루는 프로그래밍 언어입니다
      items:
        - name: 파이썬
          icon: "custom/python"
          description: 파이썬의 판다스, 파이토치 등의 프레임워크를 데이터 분석과 NLP에서 사용함
        - name: 자바스크립트
          icon: "custom/js"
          description: 프런트엔드를 사용할 때 주로 사용함

  
  - block: markdown
    content:
      title: '🗺️ 연구실 위치'
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
      title: 최근 소식
      filters:
        folders:
          - news
    design:
      view: article-grid
      rows: 3
      columns: 3
---
