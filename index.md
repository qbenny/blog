---
layout: default
---
# Benny's 生活的碎碎念

## 📝 文章归档

{% for post in site.posts %}
<div style="margin-bottom: 1.5rem; border-bottom: 1px solid #eee; padding-bottom: 1rem;">
  <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
  <small>发布日期：{{ post.date | date: "%Y-%m-%d" }}</small>
</div>
{% endfor %}
