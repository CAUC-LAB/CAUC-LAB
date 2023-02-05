---
widget: slider
weight: 1
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: ''
  is_fullscreen: true
  # Automatically transition through slides?
  loop: false
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title: 欢迎来到数据智能实验室
      content: 来看一看我们的团队近况吧...
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: welcome.jpg
    - title: 
      content: 
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: welcome.jpg
    - title:
      content:
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: welcome.jpg
      link:
        icon: graduation-cap
        icon_pack: fas
        text: 联系我们
        url: ../contact/
---
