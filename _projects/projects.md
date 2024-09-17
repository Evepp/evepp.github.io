---
layout: page
title: "My Projects"
permalink: /projects/
---

## Current Projects 2

{% for project in site.projects %}
  ### {{ project.title }}
  {{ project.excerpt }}
{% endfor %}
