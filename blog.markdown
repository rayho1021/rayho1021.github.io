---
layout: page
title: "Blog"
permalink: /blog/
---

{% for post in site.posts %}
  * <h3>{{ post.date | date: "%Y-%m-%d" }} &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></h3> 
{% endfor %}  