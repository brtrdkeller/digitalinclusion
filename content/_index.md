---
title: Digital Accessibility Inclusion
subtitle: 
seo_title:

primary_cta_page: "about"
secondary_cta_page: "projects"

posts_section_heading: Recent Posts
projects_section_heading: Projects

outputs:
  - html
  - pagejs
  - presentation
disableKinds:
  - RSS
  - taxonomy
  - taxonomyTerm
  - accessibility  
cascade:
- _target:
    path: /publication/**
  outputs:
    - html
    - pagejs
    - presentation
- _target:
    path: /report/_index.md
  outputs:
    - html
    - pagejs
    - presentation
---
