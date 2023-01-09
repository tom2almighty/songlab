---
title: 科研项目
type: landing

sections:
  - block: portfolio
    id: projects
    content:
      title: 科研项目
      subtitle: 
      text:
      filters:
        # Folders to display content from
        folders:
          - project
        # Only show content with these tags
        #tags: []
        # Exclude content with these tags
        #exclude_tags: []
        # Which Hugo page kinds to show (https://gohugo.io/templates/section-templates/#page-kinds)
        kinds:
          - page
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
      # Default portfolio filter button
      # 0 corresponds to the first button below and so on
      # For example, 0 will default to showing all content as the first button below shows content with *any* tag
      default_button_index: 0
      # Filter button toolbar (optional).
      # Add or remove as many buttons as you like.
      # To show all content, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the button toolbar, delete the entire `buttons` block.
      buttons:
        - name: 所有项目
          tag: '*'
        - name: 主持项目
          tag: 'host'
        - name: 参与项目
          tag: 'participate'
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      # Choose a listing view
      view: list
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
---
      
      
      
