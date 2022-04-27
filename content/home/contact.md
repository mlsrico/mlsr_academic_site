---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle:

content:
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

  # Contact details (edit or remove options as required)
  email: marinals@ucm.es
  address:
    city: Paris
    region: Île-de-France
    postcode: '92130'
    country: France
    country_code: FR
  contact_links:
    - icon: skype
      icon_pack: fas
      name: Message me in Skype
      link: 'https://join.skype.com/invite/lpwUrKIODmWp'

design:
  columns: '2'
---
