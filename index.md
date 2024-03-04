---
layout: home
title: Home
background_image: "img/Template Wedding Invitations.svg"
---

<div style="float: left; margin-right: 20px; width: 400px; height: 400px; overflow: hidden;">
  <img src="img/PXL_20230913_035201957.jpg" alt="alt text" style="width: 100%; height: 100%; object-fit: cover; object-position: bottom;"/>
</div>

Hello dear friends and family,

You have been invited to our Indian wedding on November 17th to 19th. On this website you can find more details and recommendations. This page is designed to be your go-to resource for all necessary information to ensure a smooth and enjoyable visit.

&nbsp;

-------------------------
&nbsp;

## LATEST UPDATES

_Keep an eye out here for any new updates to the webpage. Don't worry we will send you an email if any major updates were to happen._ 😉


<div class="home">
  {% for post in site.posts %}
    <div class="post-summary">
      <h2>
        <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      </h2>
      <p>{{ post.excerpt | strip_html | truncate: 160 }}</p>
    </div>
  {% endfor %}
</div>

&nbsp;

-----------

&nbsp;


### [💟 **RSVP to the Wedding**](https://q630ndkzsds.typeform.com/to/XKYVjFL7)

&nbsp;

### [✈️ **UPDATE US**](https://docs.google.com/spreadsheets/d/1h9mWyQekZXURMZcXfFyGt-4aI2gpKfjHPcxJUZ4CoBY/edit?usp=sharing) about your arrival and departure times at Raipur Airport.
&nbsp;



