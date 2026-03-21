---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Молекулярная динамика

        Групповой проект
      image:
        filename: group.jpg
      text: |
        <br>
        
        Исследовательская группа по математическому моделированию занимается изучением метода молекулярной динамики - компьютерного моделирования движения атомов и молекул на атомном уровне. Метод применяется в физике, химии, материаловедении и биофизике. Наша группа основана в 2026 году. 

  
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
