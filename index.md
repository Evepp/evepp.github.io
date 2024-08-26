---
layout: default
title: Welcome to My Blog
description: A place where I share my thoughts and projects.
---

# Welcome to My Blog!

Hello! I'm Evelyn Pomasqui, and this is my personal blog. Here, I will share:

- **Learning experiences with Programming**
- **Research projects of my own**
- **Important concepts in Statistics, Data Science, Sociology, Psychology, Behavioral Economics, and sometimes Management insights**

Feel free to browse my [latest posts]({{ site.baseurl }}/category/blog/).

## Recent Posts

{% for post in site.posts limit:5 %}
  * [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

## About Me

I am a knowledge seeker and lifelong learner. This blog will serve as a record of my learning journeys and a guide for those looking to develop new skills.

Thanks for visiting!

