---
title: Development - Notes
layout: default-vertical
permalink: /development/notes/

categories:
- development
- notes

tags: development notes
published: true
summary: development notes for the loyola chicago metrics project
---

Current development notes include the following,

<ul>
{% for post in site.categories.development limit: 10 %}
<li class="{% if post_location == post.menu %}active{% endif %}"><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>



