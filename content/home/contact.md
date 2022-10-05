---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

active: true

# Order that this section appears on the page.
weight: 50

title: Contact Me
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
      captcha: true

  # Contact details (edit or remove options as required)
  email: 
  phone: 
  address:
    street: 830 1st St S
    city: St. Petersburg
    region: FL
    postcode: '33705'
    country: United States
    country_code: US
  directions: MSL 227
  coordinates:
    latitude: '27.760749'
    longitude: '-82.632407'
  office_hours:
    # - 'Monday 10:00 to 13:00'
    # - 'Wednesday 09:00 to 10:00'
  appointment_url: 
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: Follow me on Twitter
      link: 'https://twitter.com/PeakeEcology'

design:
  columns: '1'
---
