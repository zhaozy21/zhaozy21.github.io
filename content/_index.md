---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: aboutMe
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      


#  - block: portfolio
#    id: myProjects
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
      
#  - block: collection
#    id: myPublications
#    content:
#      title: Featured Publications
#      filters:
#        folders:
#          - publication #must be in publication folder to show the cite correctly.
#        featured_only: true
#    design:
#      columns: '2'
#      view: Card
      

  - block: collection
    id: myPublications
    content:
      title: Selected Publications
#      text: |-
#        {{% callout note %}}
#        Quickly discover relevant content by [filtering publications](./publication/).
#        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '1'
      view: Compact
      

  - block: collection
    id: myProjects
    content:
      title: Projects
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 0
      # Filter on criteria
      filters:
        folders:
          - myProjects
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'
      
#  - block: experience
#    content:
#      title: Experience
#      # Date format for experience
#      #   Refer to https://docs.hugoblox.com/customization/#date-format
#      date_format: Jan 2006
#      # Experiences.
#      #   Add/remove as many `experience` items below as you like.
#      #   Required fields are `title`, `company`, and `date_start`.
#      #   Leave `date_end` empty if it's your current employer.
#      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
#      items:
#        - title: CEO
#          company: GenCoin
#          company_url: ''
#          company_logo: org-gc
#          location: California
#          date_start: '2021-01-01'
#          date_end: ''
#          description: |2-
#              Responsibilities include:
#
#              * Analysing
#              * Modelling
#              * Deploying
#        - title: Professor of Semiconductor Physics
#          company: University X
#          company_url: ''
#          company_logo: org-x
#          location: California
#          date_start: '2016-01-01'
#          date_end: '2020-12-31'
#          description: Taught electronic engineering and researched semiconductor physics.
#    design:
#      columns: '2'

  - block: skills
    id: mySkills
    content:
      title: Skills
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '1'      

  - block: accomplishments
    id: myAwards 
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Featured Honors & Awards'
      subtitle: Refer to [my resumé {{< icon name="file" pack="fas" >}}](uploads/resume.pdf) for more.
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
          date_start: '2023-10-01'
          description: 
          icon: 
          organization: Ministry of Education of the People's Republic of China
          organization_url: http://www.moe.gov.cn/
          title: National Scholarship for Postgraduates (Top 2%) 
          url: 
          
        - certificate_url: publication/iciea/best.png
          date_end: ''
          date_start: '2023-08-19'
          description: ''
          icon: 
          organization: 2023 IEEE 18th Conference on Industrial Electronics and Applications (ICIEA) 
          organization_url: https://ieeexplore.ieee.org/xpl/conhome/10241359/proceeding
          title: Best Paper Award
          url: 
            
        - certificate_url: myprojects/project_car/EDC_prize.jpg
          date_end: ''
          date_start: '2021-12-12'
          description: ''
          icon: 
          organization: Meituan
          organization_url: https://www.meituan.com/en-US/about-us
          title: Special Prize (1st Place) of Meituan Cup 23rd Electronic Design Competition
          url: 
            
#        - certificate_url: myprojects/project_car/TI_prize.jpg
#          date_end: ''
#          date_start: '2021-10-01'
#          description: ''
#          icon: 
#          organization: Texas Instruments
#          organization_url: https://www.ti.com/
#          title: First prize of the 11th TI-Cup Digital System Innovation Design Competition
#          url: 
          
        - certificate_url: awards/bjyx.jpg
          date_end: ''
          date_start: '2021-07-01'
          description: ''
          icon: 
          organization: Beijing Municipal Education Commission
          organization_url: https://jw.beijing.gov.cn/
          title: Beijing Outstanding Undergraduate Award (Top 5%) 
          url: ''
          
#        - certificate_url: awards/qhyl.jpg
#          date_end: ''
#          date_start: '2021-06-02'
#          description: ''
#          icon: 
#          organization: Tsinghua University
#          organization_url: https://www.tsinghua.edu.cn/en/
#          title: Tsinghua Excellent Undergraduate Award (Top 10%)
#          url: ''
          
        - certificate_url: awards/yxlw.jpg
          date_end: ''
          date_start: '2021-06-01'
          description: ''
          icon: 
          organization: Tsinghua University
          organization_url: https://www.tsinghua.edu.cn/en/
          title: Excellent Graduation Thesis of Tsinghua University
          url: 
    design:
      columns: '2'
      

      

  - block: contact
    id: contactMe
    content:
      title: Contact Me
      subtitle:
      text:
      email: zhaoziyanTHU@gmail.com
      phone: +86 188 1121 1889
      
      contact_links:
        - icon: weixin
          icon_pack: fab
          name: "WeChat: CaptainViridian 🔍"
          link: uploads/WeChat.jpg
          
        - icon: location-dot
          icon_pack: fas
          name: A803-3 Lee Shau Kee Science and Technology Building, Tsinghua University, Haidian District, Beijing, China 100084.
          link: "javascript:void"
          
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: '39.995356'
        longitude: '116.323752' 
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
#      form:
#        provider: netlify
#        formspree:
#          id:
#        netlify:
#          # Enable CAPTCHA challenge to reduce spam?
#          captcha: false
    design:
      columns: '2'



      


#  - block: markdown
#    content:
#      title: Gallery
#      subtitle: ''
#      text: |-
#        {{< gallery album="demo" >}}
#    design:
#      columns: '1'
      


#  - block: collection
#    id: talks
#    content:
#      title: Recent & Upcoming Talks
#      filters:
#        folders:
#          - event
#    design:
#      columns: '2'
#      view: compact
      

#  - block: tag_cloud
#    content:
#      title: Popular Topics
#    design:
#      columns: '2'
      

---
