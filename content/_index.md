---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: hero
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: Hugo Academic Theme
      image:
        filename: hero-academic.png
      cta:
        label: '**Get Started**'
        url: https://hugoblox.com/templates/
      cta_alt:
        label: Ask a question
        url: https://discord.gg/z8wNYzb
      cta_note:
        label: >-
          <div style="text-shadow: none;"><a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star Hugo Blox Builder</a></div><div style="text-shadow: none;"><a class="github-button" href="https://github.com/HugoBlox/theme-academic-cv" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star the Academic template</a></div>
      text: |-
        **Generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 500,000+ sites.**

        **Easily build anything with blocks - no-code required!**

        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.

        <!--Custom spacing-->
        <div class="mb-3"></div>
        <!--GitHub Button JS-->
        <script async defer src="https://buttons.github.io/buttons.js"></script>
    design:
      background:
        gradient_end: '#1976d2'
        gradient_start: '#004ba0'
        text_color_light: true
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: skills
    content:
      title: Skills
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '1'
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Senior Research Muhaqiq
          company: Habib University x SPARCO
          company_url: ''
          company_logo:
          location: Karachi, Pakistan
          date_start: '2023-06-01'
          date_end: '2023-08-15'
          description: The Project aims to create an IoT Node that can track and monitor the health of the agricultural crops. The initiative aims to work with small scale farmers and increase their crop produce. The project is successfully being carried out in capstone with aims of acheiving a working prototype by the end of April 2023. 
        - title: Junior Research Muhaqiq
          company: Habib University
          company_url: 
          company_logo: 
          location: Karachi, Pakistan
          date_start: '2022-06-01'
          date_end: '2022-08-15'
          description: The aim of the project was to "Modify the existing methods or develop new ones for activity recognition in the given context and generate alarm if need arises". The project was completed under the supervision of "Dr. Muhammad Farhan" within the time frame and a paper was published at IBCAST'23 which reported about the findings and the protytpe.
        - title: Lead Design Researcher
          company: Playground, Habib University
          company_url: 
          company_logo: 
          location: Karachi, Pakistan
          date_start: '2022-01-01'
          date_end: '2022-04-15'
          description: As a “Playground Researcher” I participated in all research activities with the playground which led to workshops, events, products and project publications by the playground. Projects which were hosted by the playground were provided support through facilities and feedback from the playground and CPE team and external design consultants.
        - title: Teaching Assistant (x7)
          company: Habib University
          company_url: 
          company_logo: 
          location: Karachi, Pakistan
          date_start: '2021-05-01'
          date_end: '2023-12-12'
          description: Taught Undergraduate level courses such as Programming Fundamentals, Data Structures and Algorithms, Calculus 2, Computer Architecture (x2), Digital Logic and Design and Micro-controllers and Interfacing
        
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url:
          date_end: ''
          date_start: '2022-01-01'
          description: 
          icon: habib
          organization: Habib University
          organization_url: https://habib.edu.pk/
          title: Dean’s List (x4), Spring 2022, Fall 2022, Spring 2023, Fall 2023
          url: ''
        - certificate_url:
          date_end: ''
          date_start: '2023-01-01'
          description:
          icon: habib
          organization: Habib University
          organization_url: https://habib.edu.pk/
          title: President’s List 2022, 2023
          url:
        - certificate_url: 
          date_end: ''
          date_start: '2022-07-01'
          description: ''
          icon: habib
          organization: Habib University
          organization_url: https://habib.edu.pk/
          title: High Academic Acheivement Scholarship Fall 2022, Fall 2023
          url: ''
        - certificate_url: 
          date_end: ''
          date_start: '2023-11-28'
          description: Prototypes for Humanity is the world's most diverse assembly of innovations that has the power to create a better future. It is the most competitive prototype competition that happens anually. My project IntelliCropPK got selected as the top project from 100+ countries and 3000 submissions. We were invited to present our project infront of world leaders and industry experts in COP28 UAE. 
          icon: habib
          organization: Prototypes for Humanity
          organization_url: https://www.prototypesforhumanity.com/
          title: Top 100 Prototypes in COP28
          url: ''
    design:
      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
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
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: collection
    content:
      title: Other Publications
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Connect with me to collaborate on amazing projects, discussions and ideas.
      # Contact (add or remove contact options as necessary)
      email: ak06865@st.habib.edu.pk / areeb.adnan.khan@gmail.com
      phone: +92 03341336686
      appointment_url: 'https://calendly.com'
      address:
        street: Green house 20/4A
        city: Karachi
        region: Sindh
        postcode: '74600'
        country: Pakistan
        country_code: PK
      #directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      # office_hours:
      #   - 'Monday 10:00 to 13:00'
      #   - 'Wednesday 09:00 to 10:00'
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: '24.9053'
        longitude: '67.1377'  
      contact_links:
        - icon: facebook
          icon_pack: fab
          name: Message Me
          link: 'https://www.facebook.com/profile.php?id=100008754222128'
        - icon: instagram
          icon_pack: fab
          name: DM Me
          link: 'https://www.instagram.com/aeeb.u?igsh=aGplbWZsaTN4d2hq&utm_source=qr'
        - icon: video
          icon_pack: fas
          name: Zoom Me
          link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
