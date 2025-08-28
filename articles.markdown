---
layout: page
title: Articles Blog
permalink: /articles.html
---

<div class="articles-container">
  <div class="posts-list">
    {% for post in site.posts %}
      <div class="post-item">
        <span class="post-date">{{ post.date | date: "%B %d, %Y" }}</span>
        <div class="post-content">
          <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
          <p>{{ post.excerpt | strip_html | truncate: 150 }}</p>
          <a href="{{ post.url | relative_url }}" class="read-more">Read More &rsaquo;</a>
        </div>
      </div>
    {% endfor %}
  </div>
</div>