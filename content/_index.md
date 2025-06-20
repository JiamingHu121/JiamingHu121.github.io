---
# Leave the homepage title empty to use the site title
title:
date: 2025-06-12
type: landing

sections:
  - block: hero
    content:
      title: |
        Materials Modeling and Design Lab
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        The research of our group focuses on the fundamental understanding and design of advanced functional materials using computational and data-driven approaches. By employing quantum mechanical calculations, atomistic simulations, and machine learning, we aim to provide fundamental insights into structure-property relationships in complex functional materials, as well as accelerate the discovery of new materials through computational and machine learning-assisted design.
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
