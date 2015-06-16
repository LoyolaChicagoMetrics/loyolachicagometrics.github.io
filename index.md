---
title: Welcome
layout: default-vertical

categories:
- general
- site

tags: general site home
published: true
summary: metrics dashboard project in the Department of Computer Science, Loyola University Chicago
---



#### Recent Updates
{% for post in site.posts limit: 5 %}
* {{ post.date | date_to_string }} | [{{ post.title }}]({{ post.url }})

  {{ post.summary }}
{% endfor %}




