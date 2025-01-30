---
layout: default
---

<div class="post-list">
  {% for post in site.posts %}
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    <p>{{ post.excerpt }}</p>
  {% endfor %}
</div>
