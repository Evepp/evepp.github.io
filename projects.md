---
layout: default
title: "My Projects"
permalink: /projects/
---

## Current Projects

{% for project in site.projects %}
  ### {{ project.title }}
  {{ project.excerpt }}
{% endfor %}
