---
title: General enquiries
sections:
  - type: hero_section
    title: Vedd fel velünk a kapcsolat
    subtitle: >-
      A gyors válaszra van szükséged a lenti űrlap segítségével vedd fel velünk
      a kapcsolat.
    align: center
    padding_top: medium
    padding_bottom: medium
    background_color: none
  - type: form_section
    content: |
      ## Címünk

      7460 Kaposvár, Szent István tér 7.

      ## Elérhetőségeink

      info@elekesdental.hu

      \+36 30 444 5555

      ## Rendelési idő

      H-P: 08:00-20:00

      Szombaton előzetes bejelentkezés alapján.

      Vasárnap: Zárva
    content_align: left
    form_position: right
    form_width: fifty
    form_layout: stacked
    enable_card: true
    form_id: contact-form
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Név
        default_value: Teljes név
        is_required: true
      - input_type: email
        name: email
        label: E-mail
        default_value: pelda@gmail.com
        is_required: true
      - input_type: select
        name: subject
        label: Tárgy
        default_value: Válasszon a lehetőségek közül
        options:
          - Általános információ
          - Időpontfoglalás
          - Egyéb
      - input_type: textarea
        name: message
        label: Üzenet
        default_value: Üzenet tartalama
      - input_type: checkbox
        name: consent
        is_required: true
        label: >-
          Tudomásul veszem, hogy ez az űrlap tárolja a beküldött adataimat, hogy
          kapcsolatba léphessenek velem.
    submit_label: Üzenet küldése
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: primary
seo:
  title: General Enquiries
  description: This is the general enquiries page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: General Enquiries
      keyName: property
    - name: 'og:description'
      value: This is the general enquiries page
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: General Enquiries
    - name: 'twitter:description'
      value: This is the general enquiries page
layout: advanced
---
