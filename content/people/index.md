---
title: People
date: 2025-06-17

type: landing

sections:
  - block: people
    content:
      title: Principal Investigator
      user_groups:
          - Principal Investigator
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: true
      show_role: false
      show_social: true
      columns: '1'

  - block: people
    content:
      title: Team Members
      user_groups:
          - Members
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true
      columns: '3'
---