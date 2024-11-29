---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        BEAMS Lab
      image:
        filename: old_logo_hero.png
      text: |
        <br>
        
        The _**B**ioprospecting and **E**ngineering of **A**dvanced **M**icrobial **S**olutions_ (**BEAMS**) Laboratory is a research group run by <a href="/author/matin-nuhamunada/">Matin Nuhamunada</a> at the Faculty of Biology, UGM. 
        
        <span style="font-size: smaller;">

        Our group focus on exploring and bioprospecting biological systems for biotechnology applications. We implement genome mining approaches combined with modern data stacks to find interesting natural products, enzymes, and pathways.
        
        We are always interested to find students with interdiscplinary skills to join our group! If you like biology, data, programming, or mathematics and would like to know more about our research, please drop by or send an email to [matin_nuhamunada@ugm.ac.id](mailto:matin_nuhamunada@ugm.ac.id).
        
        </span>
  - block: markdown
    content:
      title:
      subtitle: ''
      text: |
        <div style="display: flex; justify-content: center; align-items: center; min-height: 50vh;">
          <a href="./people/" style="font-size: 1.5em; padding: 15px 30px; display: inline-block; margin-top: 50vh; text-align: center; background-color: #007bff; color: white; text-decoration: none; border-radius: 5px;">
            Meet the team →
          </a>
        </div>
    design:
      columns: '1'
      background:
        image: 
          filename: igem-ugm-2023.jpg
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

  - block: collection
    content:
      title: Latest Publications
      text: ""
      count: 3
      filters:
        folders:
          - publication
        publication_type: 'article-journal'
    design:
      view: citation
      columns: '1'
  
  - block: tag_cloud
    content:
      title: Popular Topics
      subtitle:
      text:
      # Choose a taxonomy from the `taxonomies` list in `config.yaml` to display (e.g. tags, categories, authors)
      taxonomy: tags
      # Choose how many tags you would like to display (0 = all tags)
      count: 20
    design:
      # Minimum and maximum font sizes (1.0 = 100%).
      font_size_min: 0.7
      font_size_max: 2.0
---
