---
title: Home
white_header: true
sections:
  - type: hero_section
    section_id: hero_section
    background_image: images/leaf.svg
    background_image_opacity: 15
    content: |
      # **MOVERs**
    actions:
      - title: See all items
        url: /store
        arrow: true
        style: primary
  - type: featured_categories_section
    section_id: featured_categories_section
    featured_categories:
      - src/pages/category/cactuses.md
  - type: testimonials_section
    section_id: testimonials_section
    title: Testimonials
    testimonials:
      - author:
          name: John Dope
          location: 'Colorado, USA'
        text: >-
          I didn't know the Elixirs guys were into herbs as well! How beautiful
          is that.
      - author:
          name: Major Payne
          location: 'VA, USA'
        text: >-
          Well I'll be d*mned. These plants really ARE greener than any of my
          recruits.
seo:
  title: MOVERs
  description: |
    MOVERs Elixirs
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: MOVERs
      keyName: property
    - name: 'og:description'
      value: |
        MOVERs Elixir
      keyName: property
    - name: 'og:image'
      value: /images/Movers_Logo%20large.png
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Planty Theme
    - name: 'twitter:description'
      value: The preview of the Planty theme
    - name: 'twitter:image'
      value: images/header.jpg
      relativeUrl: true
template: home
---
