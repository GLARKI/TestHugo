---
# An instance of the Contact widget.
widget: contact
active: true

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle: Master students are encouraged to mail when interested in an internship.

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
  email: Gijs.Luijten@uk-essen.de
  address:
    street: Institute for AI in Medicine,  Giradet Straße 2
    city: 
    region: 
    postcode: 45131, Essen, Germany
    country: Germany
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: Tio-IKIM
      link: "https://twitter.com/IkimTio"
    
design:
  columns: '2'
---
