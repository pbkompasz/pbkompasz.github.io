---
layout: content
title: blog
permalink: /blog/
---

---


{% for post in site.posts %}
### [{{post.title}}]({{post.url}}) 
<sup>{{post.description}}  </sup>  
<sup>{{ post.date | date: '%B %-d, %Y' }}</sup>

---
{% endfor %}
