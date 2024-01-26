---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Willkommen!
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        Wir haben uns auf den Weg gemacht, um mehr kleine und große Abenteuer zu erleben.
        <br>
  
  - block: collection
    content:
      title: Die kleinen Abenteuer <br> <br>
      subtitle:
      text:
      count: 3
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: mikroabenteuer
    design:
      view: compact
      columns: '1'

  - block: tag_cloud
    content:
      title:
      subtitle:
      text:
      # Choose a taxonomy from the `taxonomies` list in `config.yaml` to display (e.g. tags, categories, authors)
      taxonomy: tags
      # Choose how many tags you would like to display (0 = all tags)
      count: 0
    design:
      # Minimum and maximum font sizes (1.0 = 100%).
      font_size_min: 1.0
      font_size_max: 2.0
      
  - block: markdown
    content:
      title:
      subtitle:
      text: <div class="button-wrapper-cta"> <a class="button-cta cta-button" href="https://www.mikroundmakroabenteuer.de/makroabenteuer">Das große Abenteuer</a> <link rel="stylesheet" href="style.css"> </div>
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: <iframe style="border-radius:12px" src="https://open.spotify.com/embed/track/0cX8lVW9hM3n7BwnDPN2L5?utm_source=generator&theme=0" width="100%" height="80" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
---