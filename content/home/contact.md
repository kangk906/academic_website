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
  email: kangk01.cee@gmail.com
  phone: +86 17612540300
  address:
    street: 2329 West Mall
    city: Vancouver
    region: BC
    postcode: 'V6T 1Z4'
    country: Canada
    country_code: CA
  coordinates:
    latitude: '37.4275'
    longitude: '-122.1697'

  office_hours:
    - 'Monday 09:00 to 17:00'
    
  appointment_url: 'https://calendly.com'
  contact_links:
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'https://zoom.com'

design:
  columns: '2'
---
