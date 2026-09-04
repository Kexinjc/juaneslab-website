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
        postcode: '46024'
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
    id: contact-map
    content:
      title:
      text: |
        <div class="jl-contact-map">
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3080.7213230423513!2d-0.34690612330739723!3d39.453030271610764!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0xd6048faf9003313%3A0x2cc38dab22dacbe9!2sCIPF%20Centro%20de%20Investigaci%C3%B3n%20Pr%C3%ADncipe%20Felipe!5e0!3m2!1ses!2ses!4v1732114005509!5m2!1ses!2ses" width="100%" height="380" style="border:0" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade" title="Map showing the CIPF building location in Valencia"></iframe>
        </div>
    design:
      columns: '1'
      spacing:
        padding: ['0px', '0', '32px', '0']

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
