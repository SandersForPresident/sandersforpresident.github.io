---
layout: page
title: Coders For Sanders
permalink: /
featured_pages:
  - name: Connect with Bernie
    alt: connect.berniesanders.com
    url: connect-with-bernie
    img: connectwithbernie
  - name: FeelTheBern.org
    alt: FeelTheBern.org
    url: FeelTheBern
    img: feelthebern
  - name: Bernie QR
    alt: Bernie QR
    url: bernie-qr
    img: bernie-qr
  - name: Field the Bern
    alt: Field the Bern
    url: field-the-bern
    img: field-the-bern
  - name: Bernie BNB
    alt: Bernie BNB
    url: bernie-bnb
    img: bernie-bnb
  - name: Bernie 2016 Events
    alt: Bernie 2016 Events
    url: Bernie2016Events
    img: event-map
---

Coders For Sanders is a loose collective of developers, designers, and creatives working to elect Bernie Sanders for President.

We originally began organizing on Reddit at [/r/codersforsanders](https://www.reddit.com/r/codersforsanders). We presently do nearly all of our organizing on Slack - you can join our Slack team [here](https://cfs-slack.forsanders.com/).

We are cross-platform and cross-interest - a cross-section of the technology community using the biggest and best tools and technologies to create web applications, mobile applications, and digital content. We are volunteers, united in our belief that America needs the progressive ideals espoused by Bernie Sanders to restore justice, equality, and prosperity to our country.

<h3>Featured Projects</h3>
<ul class="projects">
  {% for page in page.featured_pages %}
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
