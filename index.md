---
layout: home
title: CollabStack
---

# 🚀 CollabStack

Engineering the Control Plane of Collaboration Systems

---

## 📘 Latest Posts

{% for post in site.posts %}
### [{{ post.title }}]({{ post.url }})

- Date: {{ post.date | date: "%B %d, %Y" }}
- Categories: {{ post.categories | join: ", " }}

---
{% endfor %}

