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
 email: haocheng1999@g.ucla.edu
  phone: 213-550-8472
  address:
    street: 2 chenile
    city: Irvine
    region: CA
    postcode: '92614'
    country: United States
    country_code: US
  coordinates:
    latitude: '37.4275'
    longitude: '-122.1697'
  directions: to be add
  office_hours:
    - 'Monday-Friday 10:30 to 12:00'
    - 'Weekend 11:00 to 10:00'
  appointment_url: 'https://calendly.com'
  contact_links:
    - icon: weixin
      icon_pack: fab
      name: lhc-1999
      
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'https://zoom.com'


design:
  columns: '2'
---
