---
# A section created with the Portfolio widget.
# This section displays content from `content/project/`.
# See https://wowchemy.com/docs/widget/portfolio/
widget: portfolio

# This file represents a page section.
headless: false

# Order that this section appears on the page.
weight: 20

title: 'Projects'
subtitle: ''

content:
  page_type: project
  folders:
    - project
  filter_default: 0

  filter_button:
    - name: All
      tag: '*'
    - name: Principal Investigator
      tag: host
    - name: Participate
      tag: participate

design:
  columns: '1'
  view: compact
  flip_alt_rows: false
  background: {}
  spacing: {padding: [0, 0, 0, 0]}
---