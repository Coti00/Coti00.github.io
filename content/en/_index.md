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
        text: Certification
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
      title: Interests
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
      title: Hobby
      text: My Hobby!
      items:
        - name: Cat
          icon: "custom/cat"
          description: I have a cat named 'Tigger'!
        - name: Dog
          icon: "custom/dog"
          description: I have a dog named 'Coco'!
        - name: Music
          icon: "custom/music"
          description: I relieve stress by listening to music or playing the piano!

  - block : collection
    id: mainlang
    content:
      title: Main Language
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
      title: Recent News
      filters:
        folders:
          - news
    design:
      view: community/custom_card2
      columns: '1'

  - block: collection
    content:
      title: '🗺️ School Position'
      filters:
        folders:
          - map
    design:
      view: community/mapcard
      row: 1
      columns: 1

---
