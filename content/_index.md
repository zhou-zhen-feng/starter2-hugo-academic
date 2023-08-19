---
# Leave the homepage title empty to use the site title
title: zhou zhen feng
date: 2022-10-24
type: landing
sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin         
   - block: collection
     id：research
     content:
      title: Research
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: collection
    id: experience
    content:
      title: Experience
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: collection
    id: certificate
    content:
      title: Certificate
      text: |-
       <font size=5>●&nbsp;&nbsp;Outstanding graduates</font>\
       <font size=5>●&nbsp;&nbsp;Excellent Student Model</font>\
       <font size=5>●&nbsp;&nbsp;Excellent League Member</font>\
       <font size=5>●&nbsp;&nbsp;Outstanding Student Cadre</font>\
       <font size=5>●&nbsp;&nbsp;National Inspirational Scholarship</font>\
       <font size=5>●&nbsp;&nbsp;Bronze Award of "Internet plus" Trials</font>\
       <font size=5>●&nbsp;&nbsp;IGEM International Competition Gold Medal</font>\
       <font size=5>●&nbsp;&nbsp;Bronze Award in Youth Volunteer Service Project Competition</font>\
     # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
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
      columns: '2'
  - block: markdown
    id: gallery
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle: ''
      text: ''
      # Contact (add or remove contact options as necessary)
      email: 1179531536@qq.com
      phone: 13919209218
      #appointment_url: 'https://calendly.com'
      address:
        street: 南京大学仙林校区
        city: 南京
        region: 江苏
        #postcode: '94305'
        country: 中国
        country_code: china
      #directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      office_hours:
        - 'weekday 8:00 to 20:00'
        - 'weekend rest'
      contact_links:
        #- icon: twitter
          #icon_pack: fab
          #name: DM Me
          #link: 'https://twitter.com/Twitter'
        #- icon: skype
          #icon_pack: fab
          #name: Skype Me
          #link: 'skype:echo123?call'
         - icon: video
           icon_pack: fas
           name: Zoom Me
           link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      #form:
        #provider: netlify
        #formspree:
          #id:
        #netlify:
          # Enable CAPTCHA challenge to reduce spam?
          #captcha: false
    design:
      columns: '2'
---
