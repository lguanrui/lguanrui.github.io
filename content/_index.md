---
title: Guanrui Li
type: landing

sections:
  # Full-screen looping lab footage (shared with the ACP Lab site). To refresh: replace
  # static/media/hero.mp4 and static/media/hero-poster.jpg (H.264 MP4, muted, keep it small).
  - block: video-hero
    id: hero
    content:
      video: media/hero.mp4
      poster: media/hero-poster.jpg
      kicker: Guanrui Li · Worcester Polytechnic Institute
      headline: Agile, safe aerial robots that work with people
      subline: I am an Assistant Professor of Robotics Engineering at WPI, where I direct the Aerial-robot Control and Perception (ACP) Lab. We develop the planning, control, perception, and learning that let flying robots navigate the world, interact with it physically, and collaborate with other robots and people.
      buttons:
        - text: Publications
          url: publication/
          primary: true
        - text: Visit the ACP Lab
          url: https://acp-lab.wpi.edu/

  - block: about.biography
    id: about
    content:
      title: Biography
      username: guanrui-li

  # Teaser of the three research pillars (the full venn diagram lives on the Research page).
  # Keep these entries in sync with content/research/_index.md.
  - block: pillars
    id: research
    content:
      title: Research
      subtitle: Three pillars. Click one to see the related publications.
      pillars:
        - title: Aerial Robot Agility, Intelligence and Safety
          description: Fast planning and control, robust perception and estimation, learning-based navigation, and safety guarantees that let aerial robots fly aggressively and reliably in complex environments.
          url: research/agility-intelligence-safety/
          icon: eagle-agile-b
          icon_pack: custom
          tint: '#f0bcc4'
          tint_light: '#fbe9ec'
          accent: '#b4303f'
        - title: Aerial Physical Intelligence
          description: Aerial robots that carry, manipulate, and make physical contact with the world, from cable-suspended payload transport and perching to tactile control and physical collaboration with people.
          url: research/aerial-physical-intelligence/
          icon: eagle-arm
          icon_pack: custom
          tint: '#aecdea'
          tint_light: '#e4eef8'
          accent: '#3c6e9f'
        - title: Multi-Robot Collaboration
          description: Teams of aerial robots that cooperatively transport and manipulate objects, self-assemble into modular structures, avoid each other safely, and collaborate with humans.
          url: research/multi-robot-collaboration/
          icon: eagle-trio
          icon_pack: custom
          tint: '#ecd49c'
          tint_light: '#faf1dc'
          accent: '#b07f10'
    design:
      columns: '1'
      show_venn: false

  - block: collection
    id: news
    content:
      title: Recent News
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
      view: compact
      columns: '1'

  - block: collection
    id: featured
    content:
      title: Recent Publications
      text: See the [full list](publication/) or my [Google Scholar profile](https://scholar.google.com/citations?user=v_bUoRAAAAAJ&hl=en).
      filters:
        folders:
          - journal
          - conference
        featured_only: false
      count: 5
      sort_by: 'Date'
      sort_ascending: false
    design:
      view: compact
      columns: '1'

  - block: contact
    id: contact
    content:
      title: Contact
      text: |-
        Prospective PhD students, postdocs, and WPI students: please read the ACP Lab's [Join Us](https://acp-lab.wpi.edu/join/) page before emailing. It explains how to apply and what to include.
      email: gli7@wpi.edu
      address:
        street: UH 246, Unity Hall, 100 Institute Road, Worcester Polytechnic Institute
        city: Worcester
        region: MA
        postcode: '01609'
        country: United States
        country_code: US
      contact_links:
        - icon: graduation-cap
          icon_pack: fas
          name: Join the ACP Lab
          link: https://acp-lab.wpi.edu/join/
      autolink: true
    design:
      columns: '1'
---
