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
disableKinds:
  - RSS
  - taxonomy
  - taxonomyTerm
  - accessibility  
cascade:
- _target:
    path: /publication/_index.md
  outputs:
    - html
    - pagejs
- _target:
    path: /report/_index.md
  outputs:
    - html
    - pagejs
---
