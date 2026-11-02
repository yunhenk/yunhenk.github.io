---
layout: archive
title: "Writing"
permalink: /writing/
---

Essays, notes, and longer-form writing.

{% assign writing_posts = site.categories.writing %}
{% if writing_posts %}
  {% for post in writing_posts %}
    {% include archive-single.html %}
  {% endfor %}
{% else %}
  <p>No writing posts yet.</p>
{% endif %}
