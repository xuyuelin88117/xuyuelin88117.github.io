---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

# design:
#   # Default section spacing
#   spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
  - block: collection
    id: Publications
    content:
      title: Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
---
