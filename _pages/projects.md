---
layout: content
title: projects
permalink: /projects/
---

projects I have worked on

{% for project in site.projects %}
[{{project.title}}]({{project.url}})
{% endfor %}

