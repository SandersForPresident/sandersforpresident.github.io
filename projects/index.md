---
layout: page
title: Projects
permalink: /projects/
pages:
  - name: Bernie 2016 Events
    alt: Bernie2016Events.org
    url: Bernie2016Events
    img: event-map
  - name: Bernie BNB
    alt: Bernie BNB
    url: bernie-bnb
    img: bernie-bnb
  - name: Bernie's Bills
    alt: Bernie's Bills
    url: bernies-bills
    img: bernies-bills
  - name: Bernie QR
    alt: Bernie QR
    url: bernie-qr
    img: bernie-qr
  - name: BernieSelfie
    alt: BernieSelfie
    url: bernie-selfie
    img: bernie-selfie
  - name: BernieStrap
    alt: BernieStrap
    url: berniestrap
    img: berniestrap
  - name: BernRate
    alt: BernRate.com
    url: BernRate
    img: bernrate
  - name: Calling Tool
    alt: Calling Tool
    url: calling-tool
    img: calling-tool
  - name: Connect with Bernie
    alt: connect.berniesanders.com
    url: connect-with-bernie
    img: connectwithbernie
  - name: '#DebateWithBernie'
    alt: '#DebateWithBernie'
    url: DebateWithBernie
    img: debatewithbernie
  - name: Donate App
    alt: Donate App
    url: donate-app
    img: donate-app
  - name: FeelTheBern.org
    alt: FeelTheBern.org
    url: FeelTheBern
    img: feelthebern
  - name: Field the Bern
    alt: Field the Bern
    url: field-the-bern
    img: field-the-bern
  - name: Signup App
    alt: Signup App
    url: signup-app
    img: signup-app
  - name: Wordpress Multisite
    alt: Wordpress Multisite
    url: wordpress-multisite
    img: wordpress-multisite
---

<p>
  Web applications, mobile applications, and digital content built by Coders For Sanders to support the Sanders campaign.
</p>
<ul class="projects">
  {% for page in page.pages %}
    <li>
      <a href="/projects/{{ page.url }}">
        <div class="img-wrapper">
          <img src="/img/thumbs/{{ page.img }}.png" alt="{{ page.alt }}" />
        </div>
        <h4>{{ page.name }}</h4>
      </a>
    </li>
  {% endfor %}
</ul>
