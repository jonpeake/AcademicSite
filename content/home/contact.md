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
    street: 2725 Montlake Blvd E
    city: Seattle
    region: WA
    postcode: '98112'
    country: United States
    country_code: US
  directions: 316E
  coordinates:
    latitude: '47.645340'
    longitude: '-122.304703'
  office_hours:
    # - 'Monday 10:00 to 13:00'
    # - 'Wednesday 09:00 to 10:00'
  appointment_url: 
  contact_links:
    - icon: bluesky
      icon_pack: fab
      name: Follow me on BlueSky
      link: 'https://bsky.app/profile/peakeecology.science'

design:
  columns: '1'
---
