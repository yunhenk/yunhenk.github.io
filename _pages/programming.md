---
layout: archive
title: "Programming"
permalink: /programming/
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
