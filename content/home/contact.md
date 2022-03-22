---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: True

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
  email: cafferychen7850@gmail.com
  phone: 13020952531
  address:
    city: Guangzhou
    region: Guangdong province
    postcode: '94305'
    country: China
    country_code: CN
design:
  columns: '2'
---
