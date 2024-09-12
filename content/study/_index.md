---
title: STUDY RECORD
summary: My Study Record
type: landing

cascade:
  - _target:
      kind: page
    params:
      show_breadcrumb: true

sections:
  - block: collection
    id: study
    content:
      title: Study Record
      filters:
        folders:
          - study
    design:
      view: article-grid
      columns: 2

  - block: collection
    id: front
    content:
      title: Front Basic Study
      filters:
        folders:
          - study/Front
    design:
      view: article-grid
      columns: 1
---
