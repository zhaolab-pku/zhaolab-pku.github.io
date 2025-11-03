---
# Leave the homepage title empty to use the site title
title:
date: 2025-11-04
type: landing

sections:
  - block: hero
    content:
      # title: ZhaoLab
      image:
        filename: lab.png
      text: |
        
        Our laboratory is committed to elucidating the holistic molecular and structural details of organisms that governing physiological and pathological changes by developing integrated 3D spatial multi-omics technologies, which combining novel probe design, whole-organ tissue transparency, advanced imaging systems (e.g. light sheet fluorescence microscopy), and deep-learning-based analysis for a wide range of biomedical studies including neuroscience, cancer, and quantitative medicine.
  
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
