---
layout: default
---

Welcome to my blog.

I write about PowerShell, Azure, Windows, Linux, and infrastructure automation.

# Blog Posts

<ul>
{% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a> – {{ post.date | date: "%Y-%m-%d" }}
  </li>
{% endfor %}
</ul>