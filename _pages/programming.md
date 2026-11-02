---
layout: archive
title: "Programming"
permalink: /programming/
---

Projects, code, and technical notes.

## Projects

### [玄枢 · 六爻梅花小六壬](https://yunhenk.github.io/yi/)

六爻、梅花易数与小六壬排盘工具，支持系统随机、实体掷币和时间起课。

[打开应用](https://yunhenk.github.io/yi/) · [查看源码](https://github.com/yunhenk/yi)

## Notes

{% assign programming_posts = site.categories.programming %}
{% if programming_posts %}
  {% for post in programming_posts %}
    {% include archive-single.html %}
  {% endfor %}
{% else %}
  <p>No programming posts yet.</p>
{% endif %}
