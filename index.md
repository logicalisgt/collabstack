---
layout: default
title: CollabStack
---

# 🚀 CollabStack

Engineering the Control Plane of Collaboration Systems

## 📘 Latest Posts

<ul>
{% for post in site.posts %}
  <li>
    <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    <br>
        <small>{{ post.date | date: "%B %d, %Y" }}</small>
  </li>
{% endfor %}
</ul>

