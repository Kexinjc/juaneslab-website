---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
        If you have any questions, please contact us by telephone or email and we'll get back to you as soon as possible. We look forward to hearing from you.
      email: majuanes@cipf.es
      phone: +34 963289680 ext. 2116
      address:
        street: 'Centro de Investigación Príncipe Felipe (CIPF), Calle de Eduardo Primo Yúfera, 3'
        city: Valencia
        postcode: '46012'
        country: Spain
        country_code: ES
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'

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
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image:
          filename: contact.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
