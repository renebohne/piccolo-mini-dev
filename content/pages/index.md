---
layout: home
title: Home
white_header: true
sections:
  - type: hero_section
    section_id: hero_section
    background_image: images/Untitled design (5).png
    background_image_opacity: 65
    content: |
      # PICCOLO-MINI

      Schöne, nachhaltige Mode für unsere Kleinsten.
    actions:
      - title: Alle Produkte
        url: /store
        arrow: true
        style: primary
  - type: featured_products_section
    section_id: best_sellers_section
    title: Bestseller
    icon: true
    light_title: true
    featured_products:
      - content/pages/products/plant1.md
      - content/pages/products/plant2.md
      - content/pages/products/plant3.md
      - content/pages/products/plant4.md
  - type: featured_categories_section
    section_id: featured_categories_section
    featured_categories:
      - content/pages/category/pullover.md
      - content/pages/category/hosen.md
    title: piccolo-mini
  - type: promotion_section
    section_id: promotion_section
    title: Zukunft gestalten mit Kindermode
    image: images/Untitled design (3).png
    background_image: images/leaf.svg
    cta:
      title: Entdecken
      url: /store
      style: secondary
      arrow: true
seo:
  title: Planty Theme
  description: The preview of the Planty theme
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Planty Theme
      keyName: property
    - name: 'og:description'
      value: The preview of the Planty theme
      keyName: property
    - name: 'og:image'
      value: images/header.jpg
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
---
