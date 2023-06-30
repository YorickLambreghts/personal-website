---
date: "2022-10-24"
sections:
- block: markdown
  id: cover
  content:
    title: "Yorick Lambreghts"
    subtitle: "Evolution and Behavioural Biology"
  design:
    spacing:
      padding: ["460px", "0", "460px", "0"]
    columns: "1"
    background:
      image: 
        filename: rock-pose.jpg
        filters:
          brightness: 1.2 # determines transparancy (1=transparent; 0=opaque)
        size: cover
        parallax: true
        text_color_light: true
- block: about.avatar
  id: about
  content:
    username: admin
  # design:
  #   background:
  #     image: 
  #       filename: map.jpg
  #       filters:
  #         brightness: 1.2 # determines transparancy (1=transparent; 0=opaque)
  #       size: cover
  #       parallax: true
  #       text_color_light: true
# - block: about.biography
#   content:
#     title: 
#     username: admin
#   id: about
# - block: experience
#   content:
#     date_format: Jan 2006
#     items:
#     - company: GenCoin
#       company_logo: org-gc
#       company_url: ""
#       date_end: ""
#       date_start: "2021-01-01"
#       description: |2-
#           Responsibilities include:

#           * Analysing
#           * Modelling
#           * Deploying
#       location: California
#       title: CEO
#     - company: University X
#       company_logo: org-x
#       company_url: ""
#       date_end: "2020-12-31"
#       date_start: "2016-01-01"
#       description: Taught electronic engineering and researched semiconductor physics.
#       location: California
#       title: Professor of Semiconductor Physics
#     title: Experience
#   design:
#     columns: "2"
# - block: accomplishments
#   content:
#     date_format: Jan 2006
#     items:
#     - certificate_url: https://www.coursera.org
#       date_end: ""
#       date_start: "2021-01-25"
#       description: ""
#       organization: Coursera
#       organization_url: https://www.coursera.org
#       title: Neural Networks and Deep Learning
#       url: ""
#     - certificate_url: https://www.edx.org
#       date_end: ""
#       date_start: "2021-01-01"
#       description: Formulated informed blockchain models, hypotheses, and use cases.
#       organization: edX
#       organization_url: https://www.edx.org
#       title: Blockchain Fundamentals
#       url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
#     - certificate_url: https://www.datacamp.com
#       date_end: "2020-12-21"
#       date_start: "2020-07-01"
#       description: ""
#       organization: DataCamp
#       organization_url: https://www.datacamp.com
#       title: Object-Oriented Programming in R
#       url: ""
#     subtitle: null
#     title: Accomplish&shy;ments
#   design:
#     columns: "2"
- block: collection
  content:
    count: 5
    filters:
      author: ""
      category: ""
      exclude_featured: false
      exclude_future: false
      exclude_past: false
      folders:
      - research-info
      publication_type: ""
      tag: ""
    offset: 0
    order: desc
    text: ""
    title: Research
    subtitle: 'Find out more about my research'
  design:
    columns: "2"
    view: card
  id: posts
# - block: portfolio
#   content:
#     buttons:
#     - name: All
#       tag: '*'
#     - name: Deep Learning
#       tag: Deep Learning
#     - name: Other
#       tag: Demo
#     default_button_index: 0
#     filters:
#       folders:
#       - project
#     title: Projects
#   design:
#     columns: "1"
#     flip_alt_rows: false
#     view: showcase
#   id: projects
# - block: markdown
#   content:
#     subtitle: ""
#     text: '{{< gallery album="main_gallery" >}}'
#     title: Gallery
#   design:
#     columns: "1"
# - block: collection
#   content:
#     filters:
#       featured_only: true
#       folders:
#       - publication
#     title: Featured Publications
#   design:
#     columns: "2"
#     view: card
#   id: featured
- block: collection
  content:
    filters:
      exclude_featured: false
      folders:
      - publication
    text:
    title: Publications
  design:
    columns: "2"
    view: citation
  id: publications
# - block: collection
#   content:
#     filters:
#       folders:
#       - event
#     title: Recent & Upcoming Talks
#   design:
#     columns: "2"
#     view: compact
#   id: talks
# - block: tag_cloud
#   content:
#     title: Popular Topics
#   design:
#     columns: "2"
- block: contact
  content:
    address:
      city: Sydney
      country: Australia
      country_code: AU
      postcode: "2109"
      region: NSW
      street: 205B Culloden Rd
    # appointment_url: https://calendly.com
    # autolink: true
    # contact_links:
    # - icon: twitter
    #   icon_pack: fab
    #   link: https://twitter.com/Twitter
    #   name: DM Me
    # - icon: skype
    #   icon_pack: fab
    #   link: skype:echo123?call
    #   name: Skype Me
    # - icon: video
    #   icon_pack: fas
    #   link: https://zoom.com
    #   name: Zoom Me
    # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
    email: yorick.lambreghts@utas.edu.au
    # form:
    #   formspree:
    #     id: null
    #   netlify:
    #     captcha: false
    #   provider: netlify
    # office_hours:
    # - Monday 10:00 to 13:00
    # - Wednesday 09:00 to 10:00
    # phone: 888 888 88 88
    # subtitle: null
    # text: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis
    #   ut magna et, vehicula efficitur enim.
    coordinates:
      latitude: '-33.76927'
      longitude: '151.1116'
    title: Contact
  design:
    columns: "2"
  id: contact
title: null
type: landing
---
