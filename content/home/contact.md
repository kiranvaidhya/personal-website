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
  email: kiranvaidhya.venkadesh@radboudumc.nl
  address:
    street: Geert Groeteplein
    city: Nijmegen
    region: Gelderland
    postcode: '6525 GA'
    country: Netherlands
    country_code: NL
  coordinates:
    latitude: '51.8236'
    longitude: '5.8612'
  directions: Route 767, Room 32
  office_hours:
    - 'Monday 10:00 to 17:00 CET'
    - 'Tuesday 10:00 to 17:00 CET'
    - 'Friday 10:00 to 17:00 CET'
  appointment_url: 'https://calendly.com/kiranvaidhya93'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/kiranvaidhya93'

design:
  columns: '2'
---
