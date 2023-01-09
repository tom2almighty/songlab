---
type: widgt_page
title: 科研项目
headless: false
widget: portfolio
weight: 10
subtitle: ''

content:
  # Choose which content to display in the widget
  filters:
    # Folders to display content from
    folders:
      - project
    # Uncomment below to only show content with specific tags:
#    tags:
#      - Machine Learning
    # Uncomment below to exclude content with specific tags:
#    exclude_tags:
#      - preface    
    # Uncomment below to show specific Hugo Page kinds
    kinds:
      - page
#      - section


  sort_by: 'Date'
  sort_ascending: false


  filter_button:
    - name: 所有项目
      tag: '*'
    - name: 主持项目
      tag: host
    - name: 参与项目
      tag: participate

  # Default filter toolbar button (e.g. 0 corresponds to the first `filter_button` instance above)
  filter_default: 0

design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '2'
  # Choose a listing view
  view: compact
  # For Showcase view, flip alternate rows?
  flip_alt_rows: false
---