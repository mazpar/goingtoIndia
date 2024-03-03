---
layout: default
title: Home
background_image: "img/Template Wedding Invitations.svg"
---


&nbsp;
<div style="display: flex; align-items: center;">
  <img src="img/PXL_20230913_035201957.jpg" alt="imke_parry" style="width: auto; height: 300px; margin-right: 20px;">
  <div>
Hello dear friends and family,

As the dates November 17th to 19th approach, you can find details and recommendations for your upcoming trip to India. This page is designed to be your go-to resource for all necessary information to ensure a smooth and enjoyable visit.

&nbsp;

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

### [💟 **RSVP to the Wedding HERE**](https://q630ndkzsds.typeform.com/to/XKYVjFL7)

&nbsp;

### [➡️**UPDATE US HERE**⬅️](https://docs.google.com/spreadsheets/d/1h9mWyQekZXURMZcXfFyGt-4aI2gpKfjHPcxJUZ4CoBY/edit?usp=sharing)about your arrival and departure times in Raipur.
&nbsp;
  </div>
</div>



