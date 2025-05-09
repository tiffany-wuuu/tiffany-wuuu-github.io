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
      text: ''
#  - block: skills
#    content:
#      title: Skills
#      text: ''
#      # Choose a user to display skills from (a folder name within `content/authors/`)
#      username: admin
#    design:
#      columns: '1'
  - block: markdown
    content:
      title: Experience 
      subtitle: 
      text: '
      <style>
        /* Container for flexboxes */
        .row {
          display: flex;
          flex-wrap: wrap;
          align-items: center;
          justify-content: center;
        }

        /* Create four equal columns */
        .column {
          flex: 25%;
          padding: 20px;
          text-align: center;
        }

        .centered-img {
          margin: 0 auto;
        }

        @media screen and (max-width: 600px) {
          .column {
            flex: 50%;
          }
        }
      </style>

      <div class="row">
        <div class="column">
          <h2>Data Collection</h2>
          <img class="centered-img" src="../uploads/people128.png">
        </div>
        
        <div class="column">
          <h2>Large-Scale Datasets</h2>
          <img class="centered-img" src="../uploads/spreadsheet.png">
        </div>
        
        <div class="column">
          <h2>Stata</h2>
          <img class="centered-img" src="../uploads/laptop.png">
        </div>
        
        <div class="column">
          <h2>Qualitative Analysis</h2>
          <img class="centered-img" src="../uploads/qual.png">
        </div>
      </div>
      '
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Funding'
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
          date_end: '2024-09-30'
          date_start: '2022-09-30'
          description: ''
          icon: 
          organization: Administration for Children and Families
          organization_url: 
          title: "Improving the Quality and Supply of Child Care and Development Fund (CCDF) Providers: Evaluating the Impacts of the 2014 CCDF Block Grant Reauthorization ($100,000, Co-Investigator)"
          url: ''
#        - certificate_url: https://www.edx.org
#          date_end: ''
#          date_start: '2021-01-01'
#          description: Formulated informed blockchain models, hypotheses, and use cases.
#          icon: edx
#          organization: edX
#          organization_url: https://www.edx.org
#          title: Blockchain Fundamentals
#          url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
#        - certificate_url: https://www.datacamp.com
#          date_end: '2020-12-21'
#          date_start: '2020-07-01'
#          description: ''
#          icon: datacamp
#          organization: DataCamp
#          organization_url: https://www.datacamp.com
#          title: 'Object-Oriented Programming in R'
#          url: ''
#    design:
#      columns: '2'
#  - block: collection
#    id: posts
#    content:
#      title: Recent Posts
#      subtitle: ''
#      text: ''
#      # Choose how many pages you would like to display (0 = all pages)
#      count: 5
#      # Filter on criteria
#      filters:
#        folders:
#          - post
#        author: ""
#        category: ""
#        tag: ""
#        exclude_featured: false
#        exclude_future: false
#        exclude_past: false
#        publication_type: ""
#      # Choose how many pages you would like to offset by
#      offset: 0
#      # Page order: descending (desc) or ascending (asc) date.
#      order: desc
#    design:
#      # Choose a layout view
#      view: compact
#      columns: '2'
#  - block: portfolio
#    id: projects
#    content:
#      title: Projects
#      filters:
#        folders:
#          - project
#      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
#      default_button_index: 0
#      # Filter toolbar (optional).
#      # Add or remove as many filters (`filter_button` instances) as you like.
#      # To show all items, set `tag` to "*".
#      # To filter by a specific tag, set `tag` to an existing tag name.
#      # To remove the toolbar, delete the entire `filter_button` block.
#      buttons:
#        - name: All
#          tag: '*'
#        - name: Deep Learning
#          tag: Deep Learning
#        - name: Other
#          tag: Demo
#    design:
#      # Choose how many columns the section has. Valid values: '1' or '2'.
#      columns: '1'
#      view: showcase
#      # For Showcase view, flip alternate rows?
#      flip_alt_rows: false
#  - block: markdown
#    content:
#      title: Gallery
#      subtitle: ''
#      text: |-
#        {{< gallery album="demo" >}}
#    design:
#      columns: '1'
#  - block: collection
#    id: featured
#    content:
#      title: Featured Publications
#      filters:
#        folders:
#          - publication
#        featured_only: true
#    design:
#      columns: '2'
#      view: card
#  - block: collection
#    id: papers
#    content:
#      title: Publications
#      text: |-
#        {{% callout note %}}
#        Quickly discover relevant content by [filtering publications](./publication/).
#        {{% /callout %}}
#      filters:
#        folders:
#          - publication
#        exclude_featured: true
#    design:
#      columns: '2'
#      view: citation
  - block: markdown
    id: papers
    content:
      title: Publications
      subtitle: 
      text: '<p><b>Wu T.</b>, Villavicencio, A., Ponce Soria, V. <u>Racial attitudes among Asian American parents and their influence on school choice.</u> <i> Harvard Educational Review 94</i>(4), 491-514. https://doi.org/10.17763/1943-5045-94.4.491</p>
      <p><b>Wu T.</b>, Jenkins, J.M., & Whitaker, A. <u>Policy impacts of reimbursement rate reform: Evidence from the Child Care and Development Fund.</u> <i> (Working paper available: https://doi.org/10.26300/011p-sh36)</i></p>
      <p>Villavicencio, A., Ponce Soria, V., <b>Wu T.</b> <u>Counter-narratives from Spanish and Chinese-speaking parents navigating school choice in the United States.</u> <i> Race Ethnicity and Education, </i>1-23. https://doi.org/10.1080/13613324.2025.2488754</p>
      <p>Bailey, D.H., <b>Wu T.</b>, Jenkins, J.M., & Duncan, G.J. <u>Expert forecasts of future impacts of early childhood interventions.</u> <i>Under review</i></p>'

      
      
  - block: experience
    id: teaching
    content:
      title: Teaching
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:   
        - title: Applied Regression Analysis 
          company: UCI Educ 265 (PhD Course)
          company_url: ''
          company_logo: 
          location: Lab Instructor
          date_start: '2025-01-01'
          date_end: '2025-03-01'
          description:        
        - title: Educational, Social, and Behavioral Statistics 
          company: UCI Educ 288A (PhD Course)
          company_url: ''
          company_logo: 
          location: Lab Instructor
          date_start: '2024-09-01'
          date_end: '2024-12-01'
          description:       
        - title: Policy and Teaching 
          company: UCI Educ 243 (Master's Course/MAT)
          company_url: ''
          company_logo: 
          location: Teaching Assistant, 2 sections
          date_start: '2021-06-01'
          date_end: '2021-08-01'
          description: 
        - title: Multicultural Education in K-12 Schools
          company: UCI Educ 124 (Undergraduate Course)
          company_url: ''
          company_logo: 
          location: Teaching Assistant, 2 quarters
          date_start: '2021-01-01'
          date_end: '2021-06-01'
          description: 
        - title: Introduction to Early Childhood Education
          company: UCI Educ 106 (Undergraduate Course)
          company_url: ''
          company_logo: 
          location: Teaching Assistant
          date_start: '2020-09-01'
          date_end: '2020-12-01'
          description:           
    design:
      columns: '2'
#  - block: collection
#    id: talks
#    content:
#      title: Public Engagement
#      filters:
#        folders:
#          - event
#    design:
#      columns: '2'
#      view: compact
  #- block: tag_cloud
  #  content:
  #    title: Popular Topics
  #  design:
  #    columns: '2'
#  - block: contact
#    id: contact
#    content:
#      title: Contact
#      subtitle:
#      text: |-
#        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
#      # Contact (add or remove contact options as necessary)
#      email: tiffanw6@uci.edu
#      phone: 
#      appointment_url: ''
#      address:
#        street: 450 Serra Mall
#        city: Irvine
#        region: CA
#        postcode: '92617'
#        country: United States
#        country_code: US
#      directions: 
#      office_hours:
#        - 'Monday 10:00 to 13:00'
#        - 'Wednesday 09:00 to 10:00'
#      # Choose a map provider in `params.yaml` to show a map from these coordinates
#      coordinates:
#        latitude: '37.4275'
#        longitude: '-122.1697'  
#      contact_links:
#        - icon: twitter
#          icon_pack: fab
#          name: DM Me
#          link: 'https://twitter.com/Twitter'
#        - icon: skype
#          icon_pack: fab
#          name: Skype Me
#          link: 'skype:echo123?call'
#        - icon: video
#          icon_pack: fas
#          name: Zoom Me
#          link: 'https://zoom.com'
#      # Automatically link email and phone or display as text?
#      autolink: true
#      # Email form provider
#      form:
#        provider: netlify
#        formspree:
#          id:
#        netlify:
#          # Enable CAPTCHA challenge to reduce spam?
#          captcha: false
#    design:
#      columns: '2'
---
