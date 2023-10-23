---
# Leave the homepage title empty to use the site title
title: Manuel Colombo
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
       __<u>___B___</u>iogeochemistry <u>___A___</u>cross__ 
       {style="color: white"}
        
       __<u>___B___</u>oundaries (___B.A.B.___) Lab__
       {style="color: white"}
       
      image:
        filename: 
      text: |

        

        <br>

      cta:
        label: 'Principal Investigator: Manuel Colombo'
        url: ./author/manuel-colombo
    design:
      # Choose an optional background color, gradient, image, or video
      background:
        image:
          filename: rect817.png 
          size: cover
          position: center
          # Use a fun parallax-like fixed background effect on desktop? true/false
          parallax: true
        # gradient_end: '#00BFFF'
        # gradient_start: '#104E8B'
        text_color_light: false
      spacing:
        padding: ['100px', '150px', '480px', '0px']
  # - block: hero
  #   content:
  #     title: |
  #       <u>**B**</u>iogeochemistry <u>**A**</u>cross 

  #       <u>**B**</u>oundaries 
  #     image:
  #       filename: 
  #     text: |
  #       <br>
        
  #       The __B.A.B. Lab__ at [VIMS](https://www.vims.edu/index.php) and [W&M](https://www.wm.edu/) focuses on studying the processes (e.g., primary production, scavenging, degradation) that modulate __trace element__ and __organic carbon__ biogeochemistry across freshwater systems, coastal environments and the open ocean to gain a comprehensive understating of their cycling, fluxes, source-to-sink characterization and their role in the ecosystem.
  #       {style="color: #141414"}
        
  #       <style>body {text-align: left}</style>
        
  #       <br>

  #     cta:
  #       label: 'Principal Investigator: Manuel Colombo'
  #       url: ./author/manuel-colombo
  #   design:
  #     # Choose an optional background color, gradient, image, or video
  #     background:
  #       image:
  #         filename: rect817b.png 
  #         size: cover
  #         position: center
  #         # Use a fun parallax-like fixed background effect on desktop? true/false
  #         parallax: true
  #       # gradient_end: '#00BFFF'
  #       # gradient_start: '#104E8B'
  #       text_color_light: false
  #     spacing:
  #       padding: ['30px', '150px', '30px', '0px']
  - block: markdown
    content:
      title: |
        # __About__
        {style="color: white"}
      subtitle: 
      text: |
        ## The __B.A.B. Lab__ at <a href="https://www.vims.edu/index.php" style="color: lightgray; text-decoration: underline;text-decoration-style: line;">VIMS</a> and <a href=" https://www.wm.edu/" style="color: lightgray; text-decoration: underline;text-decoration-style: line;">W&M</a> focuses on studying the processes (e.g., primary production, scavenging, degradation) that modulate __trace element__ and __organic carbon__ biogeochemistry across freshwater systems, coastal environments and the open ocean to gain a comprehensive understating of their cycling, fluxes, source-to-sink characterization and their role in the ecosystem.
        {style="color: white"}
        <br>

        {{< figure src="Logo_All.png" width="800" height="800">}}

          
    design:
      columns: '1'
      background:
        image:
          filename: rect817dark.png 
          filters:
            brightness: 1
          size: cover
          position: center 
        gradient_end: '	white'
        gradient_start: '	white'
      spacing:
        padding: ['25px', '25px', '45px', '25px']
      #css_class: fullscreen
  - block: collection
    content:
      title: __News__
      subtitle: |
        ___Take a look at what is going on at B.A.B. Lab___
        {style="color: darkblue"}
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
        publication_type: ""
        featured_only: false
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      offset: 0
      order: desc
      page_type: post
    design:
      view: compact #compact,citation,card,showcase,masonry
      columns: '1'
      flip_alt_rows: false
      background:
        gradient_end: '	#F5F5F5'
        gradient_start: '	#F5F5F5'
      spacing:
        padding: ['0px', '25px', '20px', '25px']
  - block: markdown
    content:
      title: __Gallery - some field and lab work pictures__
    design:
      # Choose an optional background color, gradient, image, or video
      background:
        image:
          filename: #rect817.png 
          size: #cover
          position: #center
          # Use a fun parallax-like fixed background effect on desktop? true/false
          parallax: #true
        gradient_end: '	white'
        gradient_start: '	white'
      spacing:
        padding: ['25px', '0px', '0px', '0px']
  - block: slider
    content:
      slides:
      - title: #👋 Welcome to the group
        content: #Take a look at what we're working on...
        align: #left
        background:
          image:
            filename: Amazon.png
            filters:
              brightness: 0.9
          position: top
          color: 
      - title: 
        content: 
        align: 
        background:
          image:
            filename: Amazonb.png 
            filters:
              brightness: 0.9
          position: center
          color: 
    #     link:
    #       icon: graduation-cap
    #       icon_pack: fas
    #       text: Join Us
    #       url: ../contact/
      - title: 
        content: 
        align: 
        background:
          image:
            filename: Amazond.png
            filters:
              brightness: 0.9
          position: 
          color: 
      - title: 
        content: 
        align: 
        background:
          image:
            filename: Amazonf.jpg
            filters:
              brightness: 0.9
          position: center
          color: 
      - title: 
        content: 
        align: 
        background:
          image:
            filename: Arcticc.png
            filters:
              brightness: 0.9
          position: center
          color: 
      - title: 
        content: 
        align: 
        background:
          image:
            filename: Arctic.png
            filters:
              brightness: 0.9
          position: center
          color: 
      - title: 
        content: 
        align: 
        background:
          image:
            filename: RLP_sat.png
            filters:
              brightness: 0.9
          position: center
          color: 
      - title: 
        content: 
        align: 
        background:
          image:
            filename: RLP.png
            filters:
              brightness: 0.9
          position: center
          color: 
      - title: 
        content: 
        align: 
        background:
          image:
            filename: OClab.jpg
            filters:
              brightness: 0.9
          position: center
          color: 
      - title: 
        content: 
        align: 
        background:
          image:
            filename: OClabb.jpg
            filters:
              brightness: 0.9
          position: center
          color: 
      - title: 
        content: 
        align: 
        background:
          image:
            filename: TMlab.jpg
            filters:
              brightness: 0.9
          position: center
          color: 
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: #650px
      is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3000
      spacing:
        padding: ['0px', '40px', '20px', '40px']

  
    
  # - block: markdown
  #   content:
  #     title:
  #     subtitle:
  #     text: |
  #       {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
  #   design:
  #     columns: '1'
---