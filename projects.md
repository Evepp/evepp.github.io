---
layout: page
title: "Projects"
permalink: /projects/
---

# My Projects

Here are the projects I'm currently working on:

<ul>
  {% for project in site.projects %}
    <li>
      <a href="{{ project.url | relative_url }}">{{ project.title }}</a>
      <span class="post-date">{{ project.date | date: "%B %d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>
