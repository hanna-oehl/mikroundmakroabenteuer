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
      text: |
        {{% cta cta_link="./makroabenteuer/" cta_text="Das große Abenteuer →" %}}
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
      text: |
        {{% cta cta_link="./wir/" cta_text="Das sind wir →" %}}
    design:
      columns: '1'
---