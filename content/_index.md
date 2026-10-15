---
title: Guanrui Li
type: landing

sections:
  # Portrait-first opener: photo, name, role, icon row and bio come from content/authors/guanrui-li.
  - block: about.biography
    id: about
    content:
      title: ''
      username: guanrui-li

  - block: markdown
    id: research
    content:
      title: Research
      subtitle: ''
      text: |-
        My research develops the planning, control, perception, and learning that let flying robots navigate the world, interact with it physically, and collaborate with other robots and people. At the [ACP Lab](https://acp-lab.wpi.edu/) we organize this work around three pillars:

        - [**Aerial robot agility, intelligence and safety**](https://acp-lab.wpi.edu/research/agility-intelligence-safety/): fast planning and control, robust perception and estimation, learning-based navigation, and safety guarantees that let aerial robots fly aggressively and reliably in complex environments.
        - [**Aerial physical intelligence**](https://acp-lab.wpi.edu/research/aerial-physical-intelligence/): aerial robots that carry, manipulate, and make contact with the world, from cable-suspended payload transport and perching to tactile control and physical collaboration with people.
        - [**Multi-robot collaboration**](https://acp-lab.wpi.edu/research/multi-robot-collaboration/): teams of aerial robots that cooperatively transport and manipulate objects, self-assemble into modular structures, avoid each other safely, and work alongside humans.

        Our work is supported by the National Science Foundation and Amazon Robotics. The [lab website](https://acp-lab.wpi.edu/) has the [people](https://acp-lab.wpi.edu/people/), [student projects](https://acp-lab.wpi.edu/projects/), and [flight videos](https://www.youtube.com/@ACPLab-wpi). If you are interested in joining the lab as a PhD student, postdoc, or WPI student, please read the [Join Us](https://acp-lab.wpi.edu/join/) page first.
    design:
      columns: '1'

  # Hand-picked papers: set `featured: true` in a paper's index.md to list it here.
  - block: collection
    id: featured
    content:
      title: Selected Publications
      text: See the [full list](publication/) or my [Google Scholar profile](https://scholar.google.com/citations?user=v_bUoRAAAAAJ&hl=en).
      filters:
        folders:
          - journal
          - conference
          - preprint
        featured_only: true
      count: 0
      sort_by: 'Date'
      sort_ascending: false
    design:
      view: compact
      columns: '1'

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
