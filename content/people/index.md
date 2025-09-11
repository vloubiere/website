---
title: People
date: 2022-10-24

type: landing

sections:
  - block: markdown
    content:
      title: 
      subtitle: 
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: "2025_group_picture.png"
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['10px', '0', '10px', '0']
      css_class: people-banner

  - block: people
    content:
      title: Current members 
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - Current members
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true
      show_organizations: false
      spacing:
        padding: ['20px', '0', '100px', '0']

  - block: people
    content:
      title: Alumni
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - Alumni
      sort_by: Params.weight
      sort_ascending: false
    design:
      show_interests: false
      show_role: true
      show_social: true
      show_organizations: false
      spacing:
        padding: ['20px', '0', '100px', '0']
---