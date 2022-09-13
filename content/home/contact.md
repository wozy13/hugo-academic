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
  autolink: false

  # Email form provider
  form:
    provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false

  # Contact details (edit or remove options as required)
  email: wozhy [at] outlook.com
  # phone: 888 888 88 88
  address:
    street: 2350 Hayward St
    city: Ann Arbor
    region: MI
    postcode: '48109'
    country: United States
    country_code: US
  coordinates:
    latitude: '37.4275'
    longitude: '-122.1697'
  directions: Enter GG Brown Building and take the stairs to Office 1124 on the basement floor
  office_hours:
    - 'Weekdays 9:00 to 17:00'

design:
  columns: '2'
---
