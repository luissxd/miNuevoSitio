---
layout: default
title: RubyWeb
---

# RubyWeb

Bienvenido a mi sitio web Ruby.

[Ir a About]({{ "/about/" | relative_url }})

## Posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">
        {{ post.date | date: "%b %d, %Y" }} — {{ post.title }}
      </a>
    </li>
  {% endfor %}
</ul>
