---
title: Everfree Northwest
permalink: /efnw

web: 
web-display: 

tagline: For Pegasi, By Unicorns!
description: Creative direction and website for a major fan convention.
lead: Seattle's My Little Pony convention, <strong>Everfree Northwest</strong>, reached out to me to develop and launch a site for their 2018 convention. This family-friendly event brings together fans of the <em>My Little Pony</em> franchise from around the world to share their passion for ponies, featuring show VIPs, hundreds of events, concerts, an artist alley, and more.

tags: [ design, dev, cutie, unicorns, website, 2018 ]
deliverables: [ Frontend, Backend, CMS, Design ]
technologies: [ Jekyll, Netlify, Sass, PHP, Ngninx ]
contributors: [ Taiko (IT), imdrunkontea (art), Talons of Ice and Fire (art), Christa D (art), KellyTheDrawingUnicorn (art) ]

accent: "#4EAEB9"
accent-light: "#CCEBFF"
header-text: white
pattern: hero-patterns/random-shapes-05.svg
preview: efnw/preview.png

stickers:
 - [ efnw/front.png, front ]
 - [ efnw/marina.png, marina ]
 - [ efnw/mocha.png, mocha ]

screenshots: true
screenshots-desktop: efnw/homepage-d.png
screenshots-mobile: efnw/homepage-m.png
---

{% include components/sticker.html sticker=0 float="right" top="-2em" %}

# An Art Collaboration

It's been a pleasure working with Everfree Northwest design team! Despite the timezone differences, I worked with artists to create art that both compliments content on the site and adaptable for other mediums (like print and television!) The flexibility of web development allows some rather creative adaptations of art - from individually animated layers to uniquely positioned characters. These details plugged into the site layout, which sped up the development process.

<blockquote class="text-center accent-light-bg">
	<grid grid column-count="2" phone-column-count="1">
		<a href="" target="_blank" class=""><img src="{{ site.baseurl }}/media/efnw/page-guests.png" alt=""></a>
		<a href="" target="_blank" class=""><img src="{{ site.baseurl }}/media/efnw/page-badge.png" alt=""></a>
		<a href="" target="_blank" class=""><img src="{{ site.baseurl }}/media/efnw/page-footer.png" alt=""></a>
		<a href="" target="_blank" class=""><img src="{{ site.baseurl }}/media/efnw/page-hotel.png" alt=""></a>
	</grid>
</blockquote>

We let visuals tell the tale, with accessible alt-text available for people unable to see or interpret visuals.

{% include components/sticker.html sticker=1 float="right" %}

# Easy to Navigate

Large event websites tend to continuously evolve with tons of content being added as the event draws closer. Trying to keep up with guest announcements, policy changes, application forms, ticket sales, and more can easily become overwhelming without a system to manage it.

The overall goal of this website is to make it easy to navigate by simplifying content. Unlike most event websites, we simplified our content to 6 simple categories and into as few pages as possible.

> ![Navigation bar]({{ site.baseurl }}/media/efnw/nav.png)

# Heavy on art, Light on data

We paid big attention to how this site feels from mobile devices to the largest displays on the market. Despite the heavy use of high-resolution art, we optimized the site for a buttery smooth and data-light experience. By taking advantage of new features in HTML5, such as the [picture tag](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/picture), we are able to display art in a resolution apporpriate for each device. This resulted in massive data savings across the board, depending on the device used:

<grid column-count="3" phone-column-count="1">
	<div class="brick accent-bg">
		<h2>10.1 MB</h2>
		<p class="lead">4000px 4K display</p>
	</div>
	<div class="brick accent-bg">
		<h2>5.4 MB</h2>
		<p class="lead">1920px HD Display</p>
	</div>
	<div class="brick accent-bg">
		<h2>3.1 MB</h2>
		<p class="lead">1600px Laptop Display</p>
	</div>
	<div class="brick accent-bg">
		<h2>2.4 MB</h2>
		<p class="lead">1200px Tablet Display</p>
	</div>
	<div class="brick accent-bg">
		<h2>0.9 MB</h2>
		<p class="lead">960px Mobile Display</p>
	</div>
</grid>

The site is also extremely light on animations, so we were able to achieve full 60fps scrolling on supported devices that we tested the site on (such as the iPad Pro!)

{% include components/sticker.html sticker=2 float="right" %}

# Results

Everyone seems to love the site! After the event, this page will be updated with usage statistics. :smile:

