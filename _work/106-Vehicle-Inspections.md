---
title: Vehicle Inspections
permalink: /inspections

web: #
web-display: (not live yet)

tagline: Yes we can!!
description: A major on-demand transportation company goes paperless.
lead: I architected and built a user-friendly inspection system for a major on-demand transportation company.

tags: [ design, dev, react, backend, serverless, website, 2018 ]
deliverables: [ Frontend, Backend ]
technologies: [ React, AWS Lambda, AWS S3 ]

accent: "#5245c2"
accent-light: "#f1deff"
header-text: white
pattern: hero-patterns/cage-05.svg
preview: inspections/preview.png

stickers:
 - [ twemoji/car.svg, car ]
 - [ twemoji/eye.svg, eye ]
 - [ twemoji/mechanic.svg, mechanic ]

screenshots: true
screenshots-desktop: inspections/home-d.png
screenshots-mobile: inspections/home-m.png
screenshot-mobile-position: left
---

{% include components/sticker.html sticker=0 float="right" top="-4em" %}

## A Solution for Mobile + Tablet + Desktop

I worked with a major on-demand transportation to create a digital vehicle inspection system, using AWS (Lambda, S3), and React. It is designed to be used by vehicle inspectors on various input devices, whether it's from a personal phone, a company-provided tablet, or a desktop computer. Once live, this system will save countless hours of manual paperwork.

> ![Stock photo]({{ site.baseurl }}/media/inspections/stock.jpeg)

{% include components/sticker.html sticker=1 float="right" %}

## Power Through Inspections

Each vehicle inspection consists of a form and a 19-point checklist. With the explosive growth of on-demand transportation services, a single inspector may have to inspect dozens of vehicles per day. In order to assist inspectors in quickly and accurately completing inspections, I designed a user interface that makes easy to input data:

- On desktop and laptop devices, keyboard shortcuts are used for speed, and the highlighting of active fields are used for accuracy. The `tab` or `enter` key allows inspectors to move between fields, and the `P`/`F` keys can toggle between pass or fail buttons.

- On mobile and tablet devices, buttons and input fields are larger, making it easier to tap the correct form fields.

<blockquote class="text-center">
  <row>
    <column class="no-margin-bottom"><i>Desktop keyboard input</i><img src="{{ site.baseurl }}/media/inspections/input-d.png" alt=""></column>
    <column class="no-margin-bottom"><i>Mobile touch input</i><img src="{{ site.baseurl }}/media/inspections/input-m.png" alt=""></column>
  </row>
</blockquote>

## No Papers

After form submission, it generates an image of a filled form, and formats the data for export elsewhere. There's no need to send papers around, unless if it's printed of course!

![Image of a filled form]({{ site.baseurl }}/media/inspections/form-filled.png)

{% include components/sticker.html sticker=2 float="right" %}

## No Servers

_:warning: Warning: technical jargon ahead!_

Unlike traditional servers which run 24/7 whether it's used or not, serverless operates with specific functions that are only run when they are needed. **The use case of this project primarily serves inspection shops that operate during business hours.**

Because of that, it sees spikes of activity during, but see no to very little use in the evening and night hours. The uneven distribution of activity means that it doesn't make much sense to run a traditional server 24/7. Additionally, spikes of activity can often be unpredictable, so a serverless architecture allows us to automatically scale up or down as demand rises and falls throughout the day without any intervention.