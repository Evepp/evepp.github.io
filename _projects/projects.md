---
layout: page
title: "Projects"
permalink: /projects/
---

## Current Projects 2

{% for project in site.projects %}
  ### {{ project.title }}
  {{ project.excerpt }}
{% endfor %}
