---
title: Publications
date: 2023-06-01 

type: landing

sections:
  - block: portfolio
    id: pubsec
    content:
      title: __Publications__
      subtitle: |
        Publications listed below can be filtered by subject area: Trace Elements (TEs), Organic Carbon Geochemistry (OC), Rivers & Estuaries, Coastal & Ocean, Environmental Chemistry (Envir. Chem.) and Environmental Health (Envir. Health)
        {style="color: darkblue"}
      filters:
        folders:
          - publications
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: TEs
          tag: TEs
        - name: OC
          tag: OC
        - name: Rivers & Estuaries
          tag: Rivers
        - name: Coastal & Ocean
          tag:  Coastal
        - name: Envir. Chem.
          tag: EnvirChem
        - name: Envir. Health
          tag: EnvirHealth
        
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: compact #compact,citation,card,showcase,masonry, stream
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
      spacing:
        padding: ['20px', '25px', '20px', '25px']


  # - block: slider
  #   content:
  #     slides:
  #     - title: 👋 Welcome to the group
  #       content: Take a look at what we're working on...
  #       align: center
  #       background:
  #         image:
  #           filename: coders.jpg
  #           filters:
  #             brightness: 0.7
  #         position: top
  #         fit: contain
  #         color: '#666'
  #     - title: Lunch & Learn ☕️
  #       content: 'Share your knowledge with the group and explore exciting new topics together!'
  #       align: left
  #       background:
  #         image:
  #           filename: contact.jpg
  #           filters:
  #             brightness: 0.7
  #         position: center
  #         color: '#555'
  #     - title: World-Class Semiconductor Lab
  #       content: 'Just opened last month!'
  #       align: right
  #       background:
  #         image:
  #           filename: rect817.png
  #           filters:
  #             brightness: 0.5
  #         position: center
  #         color: '#333'
  #       link:
  #         icon: graduation-cap
  #         icon_pack: fas
  #         text: Join Us
  #         url: ../contact/
  #   design:
  #     # Slide height is automatic unless you force a specific height (e.g. '400px')
  #     slide_height: #'800px'
  #     is_fullscreen: true
  #     # Automatically transition through slides?
  #     loop: false
  #     # Duration of transition between slides (in ms)
  #     interval: 2000
  
---
