---
layout: home
title: 生活的碎碎念
---
# Benny's 生活的碎碎念


# 📝 文章归档

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a> 
      <small>({{ post.date | date: "%Y-%m-%d" }})</small>
    </li>
  {% endfor %}
</ul>
