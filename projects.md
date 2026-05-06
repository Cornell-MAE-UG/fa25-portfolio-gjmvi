---
layout: default
title: Projects
permalink: /projects/
---

## Projects

{% for project in site.projects %}
  <p>
    <a href="{{ project.url | relative_url }}">{{ project.title }}</a>
  </p>
{% endfor %}
