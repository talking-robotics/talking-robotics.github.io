---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
  - /upcoming/
---
{% include base_path %}


Talking Robotics is a series of virtual seminars that aim to promote reflections and dialogues about Robotics and its interaction with adjacent fields. Talking Robotics happens virtually and bi-weekly, i.e., every other week, allocating 30 min for presentation and 30 min for Q&A and networking. Sessions have a roundtable format where everyone is welcome to share ideas. Recordings and materials are shared in this website.

If you would like to nominate anyone (including yourself!) as a speaker, or have any feedback whatsoever about the format or content about our talks, please visit our [feedback](https://talking-robotics.github.io//feedback/) page.

Talks Schedule
======

{% for post in site.upcoming %}
  {% include display-single-talk.html %}
{% else %}
  <p>To be announced.</p>
{% endfor %}
