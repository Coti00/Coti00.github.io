---
# Leave the homepage title empty to use the site title
title: ""

type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: collection
    id: framework
    content:
      title: 프레임워크
      filters:
        folders:
          - test
        featured_only: true
    design:
      view: article-grid
      columns: 2
---