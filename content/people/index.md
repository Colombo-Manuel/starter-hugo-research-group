---
title: People
date: 2022-10-24

type: landing

sections:
  - block: people
    content:
      title: |
        __Meet Us__ ... well for now only me :smile:
      subtitle: #{{< figure src="icon.png" width="150" height="150">}} Biogeochemistry Across BoundariesLab

      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - Principal Investigator
          - Lab Associate
          - Postdocs & Grad Students
          - Undergrad Students
          - Alumni
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true
      spacing:
        padding: ['20px', '25px', '5px', '25px']
  - block: markdown
    content:
      title: 
      text: |
        ### I am starting the new lab on March 2024, so it is not so crowded for now, __BUT__ it will not last long as we are currently hiring. Please check the ["Current Opportunities"]({{< ref "opportunities#curropp" >}}) tab to find out more!
        {style="color: darkblue"}
    design:
      # Choose an optional background color, gradient, image, or video
      background:
        image:
          filename: #rect817.png 
          size: #cover
          position: #center
          # Use a fun parallax-like fixed background effect on desktop? true/false
          parallax: #true
        gradient_end: '	#F5F5F5'
        gradient_start: '	#F5F5F5'
      spacing:
        padding: ['0px', '0px', '0px', '0px']
---