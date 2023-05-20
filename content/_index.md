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
        
        Wir sind Tobi & Hanna und haben uns auf den Weg gemacht, um mehr kleine und große Abenteuer zu erleben. Komm' gern mit...
  
  - block: collection
    content:
      title: Von kleinen Abenteuern...
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
      page_type: mikroabenteuer
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
  
  - block: markdown
    content:
      title:
      subtitle:
      text:
    design:
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./wir/" cta_text="Das sind wir →" %}}
    design:
      columns: '1'

  - block: hero
    content:
      title:
      image:
        # Reference an image in your `assets/media/` folder
        
      # Add your Call-To-Action (CTA) button and optional icon
      cta:
        label: Das große Abenteuer
        url: https://mikroundmakroabenteuer.netlify.app/makroabenteuer/
        #icon_pack: fas
        #icon: download
      # Optionally, add an alternative CTA link
      #cta_alt:
      #  label: Ask a question
      #  url: https://discord.gg/z8wNYzb
      # Optionally, add a note under the Call-To-Action button
      #cta_note:
      #  label: >-
      #              <div style="text-shadow: none;"><a class="github-button" href="https://github.com/wowchemy/wowchemy-hugo-themes" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star Wowchemy Website Builder</a></div><div style="text-shadow: none;"><a class="github-button" href="https://github.com/wowchemy/starter-hugo-academic" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star the Academic template</a></div>
      # Add your Hero text here
      text:      
    design:
      # Choose an optional background color, gradient, image, or video
      image:
      filename: bulli.jpg
---