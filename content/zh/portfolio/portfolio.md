---
# A section created with the Portfolio widget.
# This section displays content from `content/project/`.
# See https://wowchemy.com/docs/widget/portfolio/
widget: portfolio

# This file represents a page section.
headless: false

# Order that this section appears on the page.
weight: 20

title: '科研项目'
subtitle: ''

content:
  page_type: project
  folders:
    - project
  filter_default: 0

  filter_button:
    - name: 所有项目
      tag: '*'
    - name: 主持项目
      tag: host
    - name: 参与项目
      tag: participate

design:
  columns: '1'
  view: compact
  flip_alt_rows: false
  background: {}
  spacing: {padding: [0, 0, 0, 0]}
---