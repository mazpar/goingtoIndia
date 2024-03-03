---
layout: default
title: Home
background_image: "img/Template Wedding Invitations.svg"
---

--------
&nbsp;

<div style="position: relative; z-index: 2; color: #000; padding: 1em;">

Hello dear friends and family,

As the dates November 17th to 19th approach, you can find details and recommendations for your upcoming trip to India. This page is designed to be your go-to resource for all necessary information to ensure a smooth and enjoyable visit.

&nbsp;
</div>

-------------------------

&nbsp;
&nbsp;


## LATEST UPDATES

**Keep an eye out here for any new updates to the webpage. Don't worry we will send you an email if any major updates were to happen. 😉**

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
&nbsp;

-----------
&nbsp;
### [**UPDATE US HERE**](https://docs.google.com/spreadsheets/d/1h9mWyQekZXURMZcXfFyGt-4aI2gpKfjHPcxJUZ4CoBY/edit?usp=sharing)
about your arrival and departure times in Raipur.
&nbsp;
