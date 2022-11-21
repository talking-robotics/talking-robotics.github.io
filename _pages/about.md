---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
{% include base_path %}


Talking Robotics is a series of virtual seminars that aim to promote reflections and dialogues about Robotics and its interaction with adjacent fields. Talking Robotics happens virtually and bi-weekly, i.e., every other week, allocating 30 min for presentation and 30 min for Q&A and networking. Sessions have a roundtable format where everyone is welcome to share ideas. Recordings and materials are shared in this website.

Talks Schedule
======

{% for post in site.upcoming reversed %} 
  {% include display-single-talk.html %}
{% endfor %}
