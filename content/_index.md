---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: Теплопроводность и детерминированное горение
      subtitle: Групповой проект
        
      image:
        filename: group.jpg
      text: |
        <br>
        
        Проект посвящен математическому моделированию процессов теплопроводности и детерминированного горения. В работе исследовано влияние энергии активации на режимы горения, разработаны программы численного решения на Python и Julia.

  
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
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
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
