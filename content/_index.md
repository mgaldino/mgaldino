---
date: "2022-10-24"
sections:
- block: about.avatar
  content:
    text: null
    username: admin
  id: about
- block: features
  content:
    items:
    - description: 70%
      icon: r-project
      icon_pack: fab
      name: R
    - description: 80%
      icon: chart-line
      icon_pack: fas
      name: Statistics
    - description: 100%
      icon: person-booth
      icon_pack: fa
      name: Political Science
    title: Skills
- block: experience
  content:
    date_format: Jan 2006
    items:
    - company: Transparência Brasil
      company_logo: org-tb
      company_url: "transparencia.org.br"
      date_end: "2022-09-01"
      date_start: "2016-05-01"
      description: |2-
          Responsibilities include:

          * Leading advocacy
          * Modelling
          * Fundraising
      location: Brazil
      title: executive-director
   
  design:
    columns: "2"

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
      - post
      publication_type: ""
      tag: ""
    offset: 0
    order: desc
    subtitle: ""
    text: ""
    title: Recent Posts
  design:
    columns: "2"
    view: compact
  id: posts
- block: portfolio
  content:
    buttons:
    - name: All
      tag: '*'
    - name: Deep Learning
      tag: Deep Learning
    - name: Other
      tag: Demo
    default_button_index: 0
    filters:
      folders:
      - project
    title: Projects
  design:
    columns: "1"
    flip_alt_rows: false
    view: showcase
  id: projects
- block: markdown
  content:
    subtitle: ""
    text: '{{< gallery album="demo" >}}'
    title: Gallery
  design:
    columns: "1"
- block: collection
  content:
    filters:
      featured_only: true
      folders:
      - publication
    title: Featured Publications
  design:
    columns: "2"
    view: card
  id: featured
- block: collection
  content:
    filters:
      exclude_featured: true
      folders:
      - publication
    text: |-
      {{% callout note %}}
      Quickly discover relevant content by [filtering publications](./publication/).
      {{% /callout %}}
    title: Recent Publications
  design:
    columns: "2"
    view: citation
- block: collection
  content:
    filters:
      folders:
      - event
    title: Recent & Upcoming Talks
  design:
    columns: "2"
    view: compact
  id: talks
- block: tag_cloud
  content:
    title: Popular Topics
  design:
    columns: "2"
- block: contact
  content:
    address:
      city: São Paulo
      country: Brazil
      country_code: BR
      postcode: "05508-900"
      region: SP
      street: Av Professor Luciano Gualberto, 315 - Sala 2047 Cidade Universitária
    contact_links:
    - icon: twitter
      icon_pack: fab
      link: https://twitter.com/mgaldino
      name: DM Me
    directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
    email: mgaldino at usp br
    form:
      formspree:
        id: null
      netlify:
        captcha: false
      provider: netlify
    office_hours:
    - Thursday 10:00 to 13:00
    - Thursday 18:00 to 19:00
    phone: (11) 3091 3780
    subtitle: null
    text: Please, send a message and I will reply as soon as possible.
    title: Contact
  design:
    columns: "2"
  id: contact
title: null
type: landing
---
