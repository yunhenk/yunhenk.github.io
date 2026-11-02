---
layout: archive
title: "Programming"
permalink: /programming/
author_profile: false
---

Projects, code, and technical notes.

{% assign programming_posts = site.categories.programming %}
{% if programming_posts %}
  {% for post in programming_posts %}
    {% include archive-single.html %}
  {% endfor %}
{% else %}
  <p>No programming posts yet.</p>
{% endif %}
